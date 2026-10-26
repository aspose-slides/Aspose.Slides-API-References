---
title: ToJpeg()
second_title: Aspose.Slides لمرجع API للغة C++
description: يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق JPEG. إذا تم إعطاء اسم ملف الإخراج كـ \"myPath/myFilename.jpeg\"، سيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.jpeg\" حيث N هو رقم الشريحة.
type: docs
weight: 40
url: /ar/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) طريقة

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق JPEG.

 إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg", سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.jpeg"، حيث N هو رقم الشريحة.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل. |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج. |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) طريقة

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق JPEG.

 إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg", سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.jpeg"، حيث N هو رقم الشريحة.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم كل صورة مُولَّدة. |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) طريقة

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق JPEG.

 إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg", سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.jpeg"، حيث N هو رقم الشريحة.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل. |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج. |
| scale | **float** | عامل التحجيم المطبق على صور الإخراج نسبةً إلى الحجم الأصلي للشريحة. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات التصيير. |
## ملاحظات

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)