---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides مرجع API لـ C++
description: True لتعديل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. اكتب bool.
type: docs
weight: 339
url: /ar/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) طريقة

True لتعديل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. اكتب **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## ملاحظات

Default is **true**. مستند Pdf يمكن أن يحتوي على رسومات متجهة وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true فإن صورة Metafile المصدر تُحول إلى تنسيق Png وتُحفظ في Pdf كصورة نقطية. إذا تم تعيين SaveMetafilesAsPng إلى false فإن Metafile المصدر يُحول إلى رسومات متجهة في Pdf. كل نهج له مزاياه وعيوبه. على سبيل المثال، إذا تم تحويل Metafile إلى PNG، قد يحدث فقدان بعض الجودة أثناء تكبير المستند الناتج. إذا تم تحويل Metafile إلى رسومات متجهة في Pdf، قد تظهر مشاكل في الأداء في أداة عرض Pdf. 

## انظر أيضا

* الفئة [PdfOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)