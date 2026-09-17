---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController فئة

التحكم في التنسيق لاستخدامه لتضمين جميع خطوط العرض التقديمي بصيغة WOFF.

نوع EmbedAllFontsHtmlController يعرّف الأعضا التالية:

## المنشئات

| المنشئ | الوصف |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | ينشئ مثيلًا جديدًا |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | ينشئ مثيلًا جديدًا |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | يتم استدعاؤه لكتابة ترويسة مستند html. يتم استدعاؤه مرة واحدة لكل تحويل عرض تقديمي. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | يتم استدعاؤه لكتابة تذييل مستند html. يتم استدعاؤه مرة واحدة لكل تحويل عرض تقديمي. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | يتم استدعاؤه لكتابة ترويسة شريحة html. يتم استدعاؤه مرة واحدة لكل شريحة. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | يتم استدعاؤه لكتابة تذييل شريحة html. يتم استدعاؤه مرة واحدة لكل شريحة. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | يتم استدعاؤه قبل عرض shape. يتم استدعاؤه مرة واحدة لكل shape. إذا كتبت هذه الدالة أي شيء إلى المولد، سيتم الانتهاء من توليد صورة الشريحة الحالية، سيتم إدراج جزء html المضاف وسيبدأ صورة جديدة فوق السابقة. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | يتم استدعاؤه قبل عرض shape. يتم استدعاؤه مرة واحدة لكل shape. إذا كتبت هذه الدالة أي شيء إلى المولد، سيتم الانتهاء من توليد صورة الشريحة الحالية، سيتم إدراج جزء html المضاف وسيبدأ صورة جديدة فوق السابقة. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | اكتب جميع الخطوط الموجودة في [`Presentation`](/slides/python-net/ar/aspose.slides/presentation). |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/ar/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | يكتب البيانات كـ base64 داخل مستند HTML نفسه |


### انظر أيضًا
* الوحدة [`aspose.slides.export`](/slides/python-net/ar/aspose.slides.export)
* المكتبة [`Aspose.Slides`](/slides/python-net)