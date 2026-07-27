---
title: Shape()
second_title: Referência da API Aspose.Slides para C++
description: "Iterar cada ForEach::Shape na Apresentação."
type: docs
weight: 40
url: /pt/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) método

Iterar cada [ForEach::Shape](./) no [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para iterar formas de layout |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback que será invocado para cada forma |

## Observações

As formas serão iteradas em todos os tipos de slides - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) e [ForEach::LayoutSlide](../layoutslide/)

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

Iterar cada [ForEach::Shape](./) no [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) para iterar formas de layout |
| includeNotes | **bool** | Indicador que indica se NotesSlides devem ser incluídos no processamento. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback que será invocado para cada forma |

## Observações
As formas serão iteradas em todos os tipos de slides - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) e [NotesSlide](../../../aspose.slides/notesslide/) se necessário.

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

Iterar cada [ForEach::Shape](./) no [BaseSlide](../../../aspose.slides/baseslide/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) para iterar formas de layout |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Callback que será invocado para cada forma |

## Observações

[BaseSlide](../../../aspose.slides/baseslide/) é o tipo base para [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) e [ForEach::LayoutSlide](../layoutslide/)

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

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [ForEach](../)
* Classe [BaseSlide](../../../aspose.slides/baseslide/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)