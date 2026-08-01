---
title: Portion()
second_title: Aspose.Slides voor C++ API-referentie
description: "Itereer elk ForEach::Portion in de Presentatie."
type: docs
weight: 66
url: /nl/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) methode


Itereer elk [ForEach::Portion](./) in de [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to iterate portions |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback that will be invoked for each portion |
## Opmerkingen


Portions worden geïtereerd in alle soorten dia’s - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) en [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) methode


Itereer elk [ForEach::Portion](./) in de [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) to iterate portions |
| includeNotes | **bool** | Flag that indicates whether NotesSlides should be included in processing. |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback that will be invoked for each portion |
## Opmerkingen


Portions worden geïtereerd in alle soorten dia’s - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) en [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ForEach](../)
* Naamruimte [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)