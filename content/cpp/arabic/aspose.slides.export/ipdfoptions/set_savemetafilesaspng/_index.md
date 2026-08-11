---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides لـ C++ مرجع API
description: True لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. اكتب bool.
type: docs
weight: 300
url: /ar/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) طريقة

True لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```
## ملاحظات

القيمة الافتراضية هي **true**. يمكن أن يحتوي مستند Pdf على رسومات متجهة وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true فإن صورة Metafile المصدر تُحول إلى صيغة Png وتُحفظ في Pdf كصورة نقطية. إذا تم تعيين SaveMetafilesAsPng إلى false فإن Metafile المصدر يُحول إلى رسومات متجهة في Pdf. كل نهج له مزايا وعيوب. على سبيل المثال، إذا تم تحويل Metafile إلى PNG، قد يحدث فقدان بعض الجودة أثناء تكبير/تصغير المستند الناتج. إذا تم تحويل Metafile إلى رسومات متجهة في Pdf، قد تظهر مشكلات أداء في أداة عرض Pdf. 

## انظر أيضًا

* الفئة [IPdfOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)