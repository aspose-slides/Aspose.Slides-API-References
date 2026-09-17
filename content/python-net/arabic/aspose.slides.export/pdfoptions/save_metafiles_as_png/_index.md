---
title: save_metafiles_as_png property
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png خاصية
True لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG.
            قراءة/كتابة **bool**.

### ملاحظات

الافتراضي هو **true** .
            يمكن أن يحتوي مستند Pdf على رسومات متجهة وصور نقطية. 
            إذا تم تعيين SaveMetafilesAsPng إلى true فإن ملف Metafile المصدر 
            يتم تحويل الصورة إلى تنسيق Png وحفظها في Pdf كصورة نقطية 
            . إذا تم تعيين SaveMetafilesAsPng إلى false فإن ملف Metafile المصدر 
            يتم تحويلها إلى رسومات متجهة Pdf. كل نهج له مزايا 
            وعيوب. على سبيل المثال، إذا تم تحويل Metafile إلى PNG، 
            فقد يحدث فقدان بعض الجودة أثناء 
            توسيع المستند الناتج. إذا تم تحويل Metafile إلى رسومات متجهة Pdf، 
            قد تظهر مشاكل في الأداء في أداة عرض Pdf.

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
* فئة [`PdfOptions`](/slides/python-net/ar/aspose.slides.export/pdfoptions)
* وحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* مكتبة [`Aspose.Slides`](/slides/python-net)