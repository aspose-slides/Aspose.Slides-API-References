---
title: Compress class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.lowcode/compress/
---
## فئة Compress

يمثل مجموعة من الطرق المقصودة لضغط [`Presentation`](/slides/python-net/ar/aspose.slides/presentation).

نوع Compress يكشف عن الأعضاء التالية:

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/ar/aspose.slides.lowcode/compress/compress_presentation/#presentation) | يقلل حجم العرض بتطبيق جميع خطوات الضغط المتاحة:<br/>            <br/>* Removes unused master slides **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Removes unused layout slides **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Keeps only the glyphs actually used in embedded fonts **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Reduces picture resolution to 150 DPI and deletes cropped areas of pictures **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/ar/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | يجري ضغط الـ [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) عن طريق إزالة الشرائح الرئيسة غير المستخدمة. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/ar/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | يجري ضغط الـ [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) عن طريق إزالة شرائح التخطيط غير المستخدمة. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/ar/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | يجري ضغط الـ [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) عن طريق إزالة الأحرف غير المستخدمة من الخطوط المضمنة. |
| [`compress_images(presentation, resolution)`](/slides/python-net/ar/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | يقلل دقة الصور في العرض ويُحذف المناطق المقصوصة منها،<br/>            مشابهًا لـ "Compress Pictures" في PowerPoint ويُطبق على جميع الصور.<br/>            يتم معالجة الصور على الشرائح، شرائح التخطيط والشرائح الرئيسة، بما في ذلك الصور داخل الأشكال المجمعة<br/>            وملأ الأشكال بالصور. |


### أنظر أيضًا
* الفئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* الوحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* المكتبة [`Aspose.Slides`](/slides/python-net)