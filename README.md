# PLF 2027 DZ — لوحة مشروع قانون المالية 2027

موقع ثابت (ملف `index.html` واحد) بدون خطوة بناء.

## النشر على Vercel
1. `npm i -g vercel`
2. داخل هذا المجلد: `vercel` ثم `vercel --prod`
   (Framework: Other، Build Command: فارغ، Output Directory: `.`)

## ربط النطاق الفرعي
في Vercel: Project → Settings → Domains → أضف `plf2027.osafcom.dz`
ثم أضف عند مزود DNS السجل الذي تعرضه Vercel (عادة CNAME إلى القيمة الظاهرة في اللوحة).

المصدر: مشروع قانون المالية لسنة 2027، ونص المواد من github.com/monaam/plf-2027-dz
