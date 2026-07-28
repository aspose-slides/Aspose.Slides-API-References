---
title: Shape()
second_title: Aspose.Slides dla C++ Referencja API
description: "Iteruj każdy ForEach::Shape w Presentation."
type: docs
weight: 40
url: /pl/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) metoda

Iteruj każdy [ForEach::Shape](./) w [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) do iteracji kształtów układu |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Wywoływane zwrotnie dla każdego kształtu |
## Uwagi

Kształty będą iterowane we wszystkich typach slajdów - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) i [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) metoda

Iteruj każdy [ForEach::Shape](./) w [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) do iteracji kształtów układu |
| includeNotes | **bool** | Flaga wskazująca, czy NotesSlides powinny być włączone w przetwarzanie. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Wywoływane zwrotnie dla każdego kształtu |
## Uwagi

Kształty będą iterowane we wszystkich typach slajdów - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) i [NotesSlide](../../../aspose.slides/notesslide/) w razie potrzeby.

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) metoda

Iteruj każdy [ForEach::Shape](./) w [BaseSlide](../../../aspose.slides/baseslide/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) do iteracji kształtów układu |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Wywoływane zwrotnie dla każdego kształtu |
## Uwagi

[BaseSlide](../../../aspose.slides/baseslide/) jest typem bazowym dla [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) i [ForEach::LayoutSlide](../layoutslide/)

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

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [ForEach](../)
* Klasa [BaseSlide](../../../aspose.slides/baseslide/)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)