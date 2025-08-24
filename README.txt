# Maintenance Dashboard — مصر تكنولوجى
هذه النسخة نهائية وجاهزة للنشر على GitHub Pages.

## الملفات
- manager-dashboard.html — لوحة المدير (فلترة، KPIs، إسناد، تصدير CSV/XLSX، تمييز المتأخر).
- engineer-dashboard.html — لوحة المهندس (بدء/تم، ملاحظات، قطع مسحوبة، رفع صور من الكاميرا، واتساب/اتصال، خريطة).
- config.json — مُعد مسبقًا بـ API_BASE/API_KEY واسم الشركة ورقم الدعم.
- manifest.json + sw.js — لدعم التثبيت كأيقونة (PWA).

## النشر
1) ارفع جميع هذه الملفات في جذر المستودع: maintenance-dashboard/.
2) افتح:
   - لوحة المدير: /manager-dashboard.html
   - لوحة المهندس: /engineer-dashboard.html?engineer=Ahmed
3) لو فضّلت إخفاء API_KEY من config.json، احذفه وافتح أي صفحة مرة واحدة بـ ?key=YOUR_API_KEY ليُحفظ محليًا.

## ملاحظات
- تأكد أن Web App في Apps Script متاح "Anyone with the link".
- لو بعدين نشرت نسخة إنتاجية (رابط /exec)، حدّث API_BASE في config.json.
