---
title: ToPng()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. إذا تم إعطاء اسم ملف الإخراج كـ \"myPath/myFilename.png\"، سيتم حفظ النتيجة كمجموعة من الملفات \"myPath/myFilename_N.png\" حيث N هو رقم الشريحة.
type: docs
weight: 53
url: /ar/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) طريقة

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. 

إذا تم تقديم اسم ملف الإخراج كـ "myPath/myFilename.png"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل. |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج. |
## ملاحظة




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) طريقة

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. 

إذا تم تقديم اسم ملف الإخراج كـ "myPath/myFilename.png"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | حجم كل صورة مُولَّدة. |
## ملاحظة




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) طريقة

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. 

إذا تم تقديم اسم ملف الإخراج كـ "myPath/myFilename.png"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | العرض التقديمي المدخل. |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج. |
| scale | **float** | عامل التحجيم المطبق على صور الإخراج بالنسبة إلى حجم الشريحة الأصلي. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | خيارات العرض. |
## ملاحظة




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [String](../../../system/string/)
* فئة [Convert](../)
* فئة [Size](../../../system.drawing/size/)
* فئة [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* نطاق [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)