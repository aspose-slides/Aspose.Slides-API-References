---
title: Paragraph()
second_title: Aspose.Slides voor C++ API-referentie
description: "Itereer elk ForEach::Paragraph in de Presentatie."
type: docs
weight: 53
url: /nl/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) methode


Itereer elk [ForEach::Paragraph](./) in de [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) om alinea's te itereren |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Callback die wordt aangeroepen voor elke alinea |
## Opmerkingen


Vormen worden doorlopen in alle typen dia's - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) en [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) methode


Itereer elk [ForEach::Paragraph](./) in de [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) om alinea's te itereren |
| includeNotes | **bool** | Vlag die aangeeft of NotesSlides moeten worden opgenomen in de verwerking. |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Callback die wordt aangeroepen voor elke alinea |
## Opmerkingen


Vormen worden doorlopen in alle typen dia's - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) en [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachParagraphCallback](../foreachparagraphcallback/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)