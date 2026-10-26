---
title: Process()
second_title: Aspose.Slides لـ C++ – مرجع API
description: يقوم بدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.
type: docs
weight: 1
url: /ar/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) طريقة

يقوم بدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | مصفوفة من أسماء ملفات العروض التقديمية الإدخالية. |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج للعرض التقديمي المدمج الناتج. |

## ملاحظات

```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) طريقة

يقوم بدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | مصفوفة من أسماء ملفات العروض التقديمية الإدخالية. |
| outputFileName | [System::String](../../../system/string/) | اسم ملف الإخراج للعرض التقديمي المدمج الناتج. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | الخيارات الإضافية التي تحدد كيفية حفظ العرض التقديمي المدمج. |

## ملاحظات

```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) طريقة

يقوم بدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | مصفوفة من أسماء ملفات العروض التقديمية الإدخالية. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإخراج. |

## ملاحظات

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) طريقة

يقوم بدمج عدة عروض تقديمية PowerPoint بنفس التنسيق في ملف عرض تقديمي واحد.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | مصفوفة من أسماء ملفات العروض التقديمية الإدخالية. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإخراج. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | الخيارات الإضافية التي تحدد كيفية حفظ العرض التقديمي المدمج. |

## ملاحظات

```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Merger](../)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)