---
title: Paragraph()
second_title: Aspose.Slides C++ API referencia
description: "Iterálja a Presentation minden ForEach::Paragraph elemét."
type: docs
weight: 53
url: /hu/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) módszer


Iterálja az összes [ForEach::Paragraph](./)-t a [Presentation](../../../aspose.slides/presentation/)-ban.

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) a bekezdések iterálásához |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Visszahívás, amely minden bekezdéshez meghívásra kerül |
## Megjegyzések


Az alakzatok minden típusú dián iterálva lesznek - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) és [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) módszer


Iterálja az összes [ForEach::Paragraph](./)-t a [Presentation](../../../aspose.slides/presentation/)-ban.

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) a bekezdések iterálásához |
| includeNotes | **bool** | Jelző, amely jelzi, hogy a NotesSlides fel legyen-e véve a feldolgozásba. |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Visszahívás, amely minden bekezdéshez meghívásra kerül |
## Megjegyzések


Az alakzatok minden típusú dián iterálva lesznek - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) és [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ForEachParagraphCallback](../foreachparagraphcallback/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [ForEach](../)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)