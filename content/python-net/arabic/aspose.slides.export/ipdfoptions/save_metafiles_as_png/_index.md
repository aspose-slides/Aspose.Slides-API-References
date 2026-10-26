---
title: save_metafiles_as_png property
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png خاصية
True لتقليل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG.
            قراءة/كتابة **bool**.

### ملاحظات

القيمة الافتراضية هي **true** .
مستند Pdf يمكن أن يحتوي على رسومات متجهية وصور نقطية. 
إذا تم تعيين SaveMetafilesAsPng إلى true فإن صورة Metafile المصدر تُحول إلى تنسيق Png وتُحفظ في Pdf كصورة نقطية. إذا تم تعيين SaveMetafilesAsPng إلى false فإن Metafile المصدر يُحول إلى رسومات متجهية Pdf. كل نهج له مزايا وعيوب. على سبيل المثال، إذا تم تحويل Metafile إلى PNG، قد يحدث فقدان بعض الجودة أثناء تحجيم المستند الناتج. إذا تم تحويل Metafile إلى رسومات متجهية Pdf، قد تحدث مشكلات أداء في أداة عرض Pdf.

### التعريف:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### انظر أيضًا
* فئة [`IPdfOptions`](/slides/python-net/ar/aspose.slides.export/ipdfoptions)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)