# Accordion Component (FAQ)

مكوّن Accordion للأسئلة الشائعة بـ HTML و CSS و JavaScript فقط، بدون مكتبات.

## الميزات
- متاح للجميع: `aria-expanded` و `aria-controls` و `role="region"`، وتنقل كامل بلوحة المفاتيح (Enter / Space / ↑ ↓ / Home / End).
- حركة سلسة بـ `grid-template-rows` (بدون `max-height` ثابت، فلا يُقصّ المحتوى الطويل).
- وضع داكن تلقائي (`prefers-color-scheme`) واحترام `prefers-reduced-motion`.
- واجهة RTL عربية، وأيقونة SVG بدون الحاجة إلى Font Awesome.
- قابل لإعادة الاستخدام: `data-accordion` لعنصر واحد مفتوح، أو `data-accordion data-multiple="true"` لعدة عناصر.

## التشغيل محليًا
```bash
python3 -m http.server 8000
# افتح http://localhost:8000
```

## النشر على GitHub Pages
1. ارفع الملفات إلى مستودع على GitHub (فرع `main`).
2. من المستودع: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. تبويب **Actions** سيُشغّل *Deploy to GitHub Pages* تلقائيًا، وعند نجاحه يظهر الرابط:
   `https://<username>.github.io/accordion-component-task/`