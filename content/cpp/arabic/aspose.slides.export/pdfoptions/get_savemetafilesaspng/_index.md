---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides لـ C++ مرجع API
description: True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. قراءة bool.
type: docs
weight: 326
url: /ar/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() طريقة

True to convert all metafiles used in a presentation to the PNG images. قراءة **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## ملاحظات

القيمة الافتراضية هي **true**. يمكن لمستند Pdf أن يحتوي على رسومات متجهة وصور نمطية. إذا تم تعيين SaveMetafilesAsPng إلى true فإن صورة Metafile المصدر تُحوَّل إلى صيغة Png وتُحفظ في Pdf كصورة نمطية. إذا تم تعيين SaveMetafilesAsPng إلى false فإن Metafile المصدر يُحوَّل إلى رسومات متجهة في Pdf. كل نهج له مزايا وعيوب. على سبيل المثال، إذا تم تحويل Metafile إلى PNG، قد يحدث فقدان جزئي في الجودة أثناء تحجيم المستند الناتج. إذا تم تحويل Metafile إلى رسومات متجهة في Pdf، قد تحدث مشكلات في الأداء في أداة عرض Pdf.

## انظر أيضًا

* الفئة [PdfOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)