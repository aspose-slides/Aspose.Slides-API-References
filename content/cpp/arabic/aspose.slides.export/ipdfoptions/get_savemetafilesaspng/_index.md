---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides لمرجع API C++
description: True لتحويل جميع ملفات الميتا المستخدمة في عرض إلى صور PNG. قراءة bool.
type: docs
weight: 287
url: /ar/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() طريقة


True لتحويل جميع ملفات الميتا المستخدمة في عرض إلى صور PNG. قراءة **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## ملاحظات


القيمة الافتراضية هي **true**. يمكن لمستند Pdf أن يحتوي على رسومات متجهية وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true فإن صورة Metafile المصدر تُحوَّل إلى صيغة Png وتُحفظ في Pdf كصورة نقطية. إذا تم تعيين SaveMetafilesAsPng إلى false فإن Metafile المصدر يُحوَّل إلى رسومات متجهية في Pdf. كل نهج له مزايا وعيوب. على سبيل المثال، إذا تم تحويل Metafile إلى PNG، قد يحدث فقدان بعض الجودة أثناء تحجيم المستند الناتج. إذا تم تحويل Metafile إلى رسومات متجهية في Pdf، قد تظهر مشكلات أداء في أداة عرض Pdf. 
## انظر أيضًا

* الفئة [IPdfOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)