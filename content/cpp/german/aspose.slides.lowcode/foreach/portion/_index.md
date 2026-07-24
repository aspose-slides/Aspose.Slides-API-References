---
title: Portion()
second_title: Aspose.Slides für C++ API-Referenz
description: "Durchlaufen jeder ForEach::Portion in der Präsentation."
type: docs
weight: 66
url: /de/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) method


Iteriere jedes [ForEach::Portion](./) in der [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) zum Durchlaufen von Portionen |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback, das für jede Portion aufgerufen wird |
## Bemerkungen


Portionen werden in allen Arten von Folien iteriert - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) und [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) method


Iteriere jedes [ForEach::Portion](./) in der [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) zum Durchlaufen von Portionen |
| includeNotes | **bool** | Flag, das angibt, ob NotesSlides in die Verarbeitung eingeschlossen werden sollen. |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback, das für jede Portion aufgerufen wird |
## Bemerkungen


Portionen werden in allen Arten von Folien iteriert - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) und [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)