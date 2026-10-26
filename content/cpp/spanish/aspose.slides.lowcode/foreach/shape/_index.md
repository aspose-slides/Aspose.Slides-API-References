---
title: Shape()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Itera cada ForEach::Shape en la Presentación."
type: docs
weight: 40
url: /es/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) método

Itera cada [ForEach::Shape](./) en el [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para iterar formas de diseño |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback que será invocado para cada forma |

## Observaciones

Las formas se iterarán en todos los tipos de diapositivas - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) y [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) método

Itera cada [ForEach::Shape](./) en el [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para iterar formas de diseño |
| includeNotes | **bool** | Indicador que indica si NotesSlides deben incluirse en el procesamiento. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback que será invocado para cada forma |

## Observaciones

Las formas se iterarán en todos los tipos de diapositivas - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) y [NotesSlide](../../../aspose.slides/notesslide/) si es necesario.

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) método

Itera cada [ForEach::Shape](./) en el [BaseSlide](../../../aspose.slides/baseslide/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) para iterar formas de diseño |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback que será invocado para cada forma |

## Observaciones

[BaseSlide](../../../aspose.slides/baseslide/) es el tipo base para [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) y [ForEach::LayoutSlide](../layoutslide/)

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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Clase [ForEach](../)
* Clase [BaseSlide](../../../aspose.slides/baseslide/)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)