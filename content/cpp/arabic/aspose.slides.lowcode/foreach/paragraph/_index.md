---
title: Paragraph()
second_title: مرجع API Aspose.Slides للـ C++
description: "تكرار كل ForEach::Paragraph في العرض التقديمي."
type: docs
weight: 53
url: /ar/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) طريقة

تكرار كل [ForEach::Paragraph](./) في [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) لتكرار الفقرات |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | دالة رد النداء التي سيتم استدعاؤها لكل فقرة |

## ملاحظات

سيتم تكرار الأشكال في جميع أنواع الشرائح - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) و [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) طريقة

تكرار كل [ForEach::Paragraph](./) في [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) لتكرار الفقرات |
| includeNotes | **bool** | علامة تشير إلى ما إذا كان يجب تضمين شرائح الملاحظات في المعالجة. |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | دالة رد النداء التي سيتم استدعاؤها لكل فقرة |

## ملاحظات

سيتم تكرار الأشكال في جميع أنواع الشرائح - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) و [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ForEachParagraphCallback](../foreachparagraphcallback/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [ForEach](../)
* نطاق [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)