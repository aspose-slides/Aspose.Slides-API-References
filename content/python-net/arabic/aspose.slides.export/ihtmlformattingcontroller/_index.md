---
title: IHtmlFormattingController class
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController فئة

يتحكم في إنشاء ملف html.

يعرض نوع IHtmlFormattingController الأعضاء التالية:

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/ar/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | يتم استدعاؤه لكتابة رأس مستند html. يتم استدعاؤه مرة واحدة لكل تحويل عرض تقديمي. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/ar/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | يتم استدعاؤه لكتابة تذييل مستند html. يتم استدعاؤه مرة واحدة لكل تحويل عرض تقديمي. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/ar/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | يتم استدعاؤه لكتابة رأس شريحة html. يتم استدعاؤه مرة واحدة لكل شريحة. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/ar/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | يتم استدعاؤه لكتابة تذييل شريحة html. يتم استدعاؤه مرة واحدة لكل شريحة. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/ar/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | يتم استدعاؤه قبل عرض shape. يتم استدعاؤه مرة واحدة لكل shape. إذا كتبت هذه الدالة أي شيء إلى المُولِّد، سيتم الانتهاء من إنشاء صورة الشريحة الحالية، وستُدرج قطعة html المضافة وسيتم بدء صورة جديدة فوق السابقة. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/ar/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | يتم استدعاؤه قبل عرض shape. يتم استدعاؤه مرة واحدة لكل shape. إذا كتبت هذه الدالة أي شيء إلى المُولِّد، سيتم الانتهاء من إنشاء صورة الشريحة الحالية، وستُدرج قطعة html المضافة وسيتم بدء صورة جديدة فوق السابقة. |


### انظر أيضًا
* الوحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* المكتبة [`Aspose.Slides`](/slides/python-net)