معرض أبو ياسر للتبريد - نسخة قاعدة بيانات حقيقية

هذه النسخة تستخدم SQLite + Express.
1) ثبّت Node.js.
2) داخل مجلد المشروع شغّل: npm install
3) شغّل: npm start
4) افتح: http://localhost:3000
5) قاعدة البيانات store.db تُنشأ تلقائياً عند التشغيل.

API:
GET /api/products
POST/PUT/DELETE /api/products
POST /api/orders
GET /api/orders
PATCH /api/orders/:id

ملاحظة: قاعدة SQLite حقيقية، لكن النشر العام يحتاج استضافة تدعم Node.js وتخزيناً دائماً. 
