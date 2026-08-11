---
title: Convert
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يمثل مجموعة من الطرق المخصصة لتحويل Presentation.
type: docs
weight: 27
url: /ar/aspose.slides.lowcode/convert/
---
## فئة التحويل


يمثل مجموعة من الطرق المخصصة لتحويل [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) باستخدام امتداد مسار الإخراج الممرّر لتحديد تنسيق التصدير المطلوب. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق JPEG. 

 إذا تم إعطاء اسم ملف الإخراج مثل \"myPath/myFilename.jpeg\"، فسيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.jpeg\"، حيث N هو رقم الشريحة. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق JPEG. 

 إذا تم إعطاء اسم ملف الإخراج مثل \"myPath/myFilename.jpeg\"، فسيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.jpeg\"، حيث N هو رقم الشريحة. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق JPEG. 

 إذا تم إعطاء اسم ملف الإخراج مثل \"myPath/myFilename.jpeg\"، فسيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.jpeg\"، حيث N هو رقم الشريحة. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق PNG. 

 إذا تم إعطاء اسم ملف الإخراج مثل \"myPath/myFilename.png\"، فسيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.png\"، حيث N هو رقم الشريحة. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق PNG. 

 إذا تم إعطاء اسم ملف الإخراج مثل \"myPath/myFilename.png\"، فسيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.png\"، حيث N هو رقم الشريحة. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق PNG. 

 إذا تم إعطاء اسم ملف الإخراج مثل \"myPath/myFilename.png\"، فسيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.png\"، حيث N هو رقم الشريحة. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | يقوم بتحويل [Presentation](../../aspose.slides/presentation/) إلى SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق TIFF. 

 إذا تم إعطاء اسم ملف الإخراج مثل \"myPath/myFilename.tiff\"، فسيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.tiff\"، حيث N هو رقم الشريحة. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | يقوم بتحويل العرض التقديمي المدخل إلى تنسيق TIFF مع خيارات مخصَّصة. إذا تم إعطاء اسم ملف الإخراج مثل \"myPath/myFilename.tiff\" و *multipage*  هو **false**، فسيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.tiff\"، حيث N هو رقم الشريحة. وإلا، إذا كان *multipage*  هو **true**، فستكون النتيجة مستند \"myPath/myFilename.tiff\" متعدد الصفحات. |

## أنواع التعريف

| نوع التعريف | الوصف |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | دالة رد نداء سيتم استدعاؤها لكل [Slide](../../aspose.slides/slide/)، ويُتوقع إرجاع مسار الإخراج. |
## ملاحظات



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## انظر أيضاً

* النطاق [Aspose::Slides::LowCode](../)
* المكتبة [Aspose.Slides](../../)