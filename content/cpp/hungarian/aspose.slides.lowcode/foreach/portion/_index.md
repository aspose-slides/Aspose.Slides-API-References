---
title: Portion()
second_title: Aspose.Slides C++ API-referencia
description: "Iterálja a Presentation-ben található minden ForEach::Portion elemet."
type: docs
weight: 66
url: /hu/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) metódus


Iteráljon minden [ForEach::Portion](./)-t a [Presentation](../../../aspose.slides/presentation/)-ban.

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) a szakaszok iterálásához |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Visszahívás, amely minden szakaszhoz meghívásra kerül |
## Megjegyzések


A szakaszok minden típusú dián iterálva lesznek – [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) és [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) metódus


Iteráljon minden [ForEach::Portion](./)-t a [Presentation](../../../aspose.slides/presentation/)-ban.

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) a szakaszok iterálásához |
| includeNotes | **bool** | Jelző, amely jelzi, hogy a NotesSlides legyenek beépítve a feldolgozásba. |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Visszahívás, amely minden szakaszhoz meghívásra kerül |
## Megjegyzések


A szakaszok minden típusú dián iterálva lesznek – [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) és [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [ForEach](../)
* Névterület [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)