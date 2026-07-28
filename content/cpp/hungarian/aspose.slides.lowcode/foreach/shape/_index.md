---
title: Shape()
second_title: Aspose.Slides C++ API Referenciája
description: "Iterálja a Presentation-ben található minden ForEach::Shape elemet."
type: docs
weight: 40
url: /hu/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) metódus


Iterálja a(z) [ForEach::Shape](./)-t a(z) [Presentation](../../../aspose.slides/presentation/)-ban.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) a layout alakzatok iterálásához |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Visszahívás, amely minden alakzatra meghívásra kerül |
## Megjegyzések


Alakzatok minden típusú dián iterálva lesznek - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) és [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) metódus


Iterálja a(z) [ForEach::Shape](./)-t a(z) [Presentation](../../../aspose.slides/presentation/)-ban.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) a layout alakzatok iterálásához |
| includeNotes | **bool** | Jelző, amely azt jelzi, hogy a NotesSlides fel legyen-e véve a feldolgozásba. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Visszahívás, amely minden alakzatra meghívásra kerül |
## Megjegyzések


Alakzatok minden típusú dián iterálva lesznek - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) és [NotesSlide](../../../aspose.slides/notesslide/) szükség esetén.



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) metódus


Iterálja a(z) [ForEach::Shape](./)-t a(z) [BaseSlide](../../../aspose.slides/baseslide/)-ban.

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) a layout alakzatok iterálásához |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Visszahívás, amely minden alakzatra meghívásra kerül |
## Megjegyzések


[BaseSlide](../../../aspose.slides/baseslide/) az alap típusa a(z) [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) és [ForEach::LayoutSlide](../layoutslide/) számára



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

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Class [BaseSlide](../../../aspose.slides/baseslide/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)