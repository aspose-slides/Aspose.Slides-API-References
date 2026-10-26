---
title: Shape()
second_title: Aspose.Slides für C++ API Referenz
description: "Durchlaufen Sie jedes ForEach::Shape in der Präsentation."
type: docs
weight: 40
url: /de/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) method


Durchlaufen Sie jedes [ForEach::Shape](./) im [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) zum Durchlaufen von Layout-Formen |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback, der für jede Form aufgerufen wird |
## Hinweise


Formen werden in allen Folientypen durchlaufen - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) und [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) method


Durchlaufen Sie jedes [ForEach::Shape](./) im [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) zum Durchlaufen von Layout-Formen |
| includeNotes | **bool** | Flag, das angibt, ob NotesSlides in die Verarbeitung einbezogen werden sollen. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback, der für jede Form aufgerufen wird |
## Hinweise


Formen werden in allen Folientypen durchlaufen - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) und [NotesSlide](../../../aspose.slides/notesslide/) falls nötig.



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) method


Durchlaufen Sie jedes [ForEach::Shape](./) im [BaseSlide](../../../aspose.slides/baseslide/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) zum Durchlaufen von Layout-Formen |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback, der für jede Form aufgerufen wird |
## Hinweise


[BaseSlide](../../../aspose.slides/baseslide/) ist der Basistyp für [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) und [ForEach::LayoutSlide](../layoutslide/).



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

ForEach::Slide(pres, std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> baseSlide, int32_t shapeIndex)
    {
        System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), shapeIndex);
    };

    auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> baseSlide, int32_t shapeIndex)>(lambda);

    ForEach::Shape(slide, callback);
}));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [ForEach](../)
* Klasse [BaseSlide](../../../aspose.slides/baseslide/)
* Namensraum [Aspose::Slides::LowCode](../../)
* Bibliothek [Aspose.Slides](../../../)