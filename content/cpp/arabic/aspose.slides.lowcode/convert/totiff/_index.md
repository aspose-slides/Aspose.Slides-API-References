---
title: ToTiff()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتحويل العرض التقديمي المُدخل إلى مجموعة من الصور بصيغة TIFF. إذا تم توفير اسم ملف الإخراج كـ \"myPath/myFilename.tiff\"، سيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.tiff\" حيث N هو رقم الشريحة.
type: docs
weight: 66
url: /ar/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) طريقة


يقوم بتحويل العرض التقديمي المُدخل إلى مجموعة من صور بصيغة TIFF. 

 إذا تم توفير اسم ملف الإخراج كـ \"myPath/myFilename.tiff\"، سيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.tiff\" حيث N هو رقم الشريحة.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المُدخل. |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج. |
## ملاحظات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) طريقة


يقوم بتحويل العرض التقديمي المُدخل إلى تنسيق TIFF مع خيارات مخصصة. إذا تم توفير اسم ملف الإخراج كـ \"myPath/myFilename.tiff\" وكان *multipage*  **false**، سيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.tiff\" حيث N هو رقم الشريحة. وإلا، إذا كان *multipage*  **true**، ستكون النتيجة مستندًا متعدد الصفحات \"myPath/myFilename.tiff\".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المُدخل. |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | خيارات حفظ TIFF. |
| multipage | **bool** | يحدد ما إذا كان مستند TIFF المُنشأ يجب أن يكون متعدد الصفحات. |
## ملاحظات




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [String](../../../system/string/)
* فئة [Convert](../)
* فئة [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* مساحة الأسماء [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)