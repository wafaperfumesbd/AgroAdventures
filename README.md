# Chalan Beel Agro Ventures — Website Preview

এই ফোল্ডারের ফাইলগুলো GitHub Pages-এ আপলোড করলে একটা লাইভ লিংক পাবেন,
যেখান থেকে যেকোনো ডিভাইসে (ফোন/কম্পিউটার) ব্রাউজার দিয়ে পুরো ওয়েবসাইট
প্রিভিউ দেখা যাবে — কোনো extract/download সমস্যা ছাড়াই।

## GitHub Pages-এ আপলোড করার ধাপ

1. **github.com**-এ লগইন করুন এবং একটা নতুন **Public** repository বানান
   (যেমন নাম: `chalan-beel-preview`)

2. Repository পেজে **"Add file" → "Upload files"** ক্লিক করুন

3. এই ফোল্ডারের ভেতরের **সব ফাইল ও ফোল্ডার** (10টা `.html` ফাইল + `images/`
   ফোল্ডার পুরোটা) আপলোড করুন — ফোল্ডার স্ট্রাকচার ঠিক রেখে drag-and-drop করুন

4. **Commit changes** ক্লিক করুন

5. Repository-র **Settings → Pages**-এ যান

6. "Source" এর নিচে **"Deploy from a branch"** সিলেক্ট করুন,
   branch = **main**, folder = **/ (root)**, তারপর **Save**

7. ২-৩ মিনিট পর এই ঠিকানায় লাইভ লিংক পাবেন:
   ```
   https://আপনার-ইউজারনেম.github.io/chalan-beel-preview/
   ```

## ফাইল তালিকা

- `index.html` — Homepage (সব ৬টা প্রোডাক্ট, ৩টা সিজনাল, ৩টা টেস্টিমোনিয়াল)
- `products.html` — সব ৫টা ক্যাটেগরি
- `category-shutki.html` — Shutki ক্যাটেগরির ২টা প্রোডাক্ট
- `product-detail.html` — Ilish Shutki প্রোডাক্ট ডিটেইল
- `about.html` — About Us
- `contact.html` — Contact ফর্ম (preview only — submit করে না)
- `faq.html` — প্রশ্নোত্তর (ক্লিক করলে accordion খোলে)
- `privacy-policy.html`, `terms.html` — লিগ্যাল পেজ
- `404.html` — Not Found পেজ
- `images/` — সব রিয়েল প্রোডাক্ট ছবি (ব্র্যান্ড কালার দিয়ে জেনারেট করা placeholder)
