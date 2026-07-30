---
title: Paragraph()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: "Iteruje každý ForEach::Paragraph v prezentaci."
type: docs
weight: 53
url: /cs/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) metoda

Iterujte každý [ForEach::Paragraph](./) v [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) k iteraci odstavců |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Zpětné volání, které bude vyvoláno pro každý odstavec |

## Poznámky

Tvary budou iterovány ve všech typech snímků - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) a [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) metoda

Iterujte každý [ForEach::Paragraph](./) v [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) k iteraci odstavců |
| includeNotes | **bool** | Příznak, který určuje, zda mají být NotesSlides zahrnuty do zpracování. |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Zpětné volání, které bude vyvoláno pro každý odstavec |

## Poznámky

Tvary budou iterovány ve všech typech snímků - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) a [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachParagraphCallback](../foreachparagraphcallback/)
* Třída [Presentation](../../../aspose.slides/presentation/)
* Třída [ForEach](../)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Knihovna [Aspose.Slides](../../../)