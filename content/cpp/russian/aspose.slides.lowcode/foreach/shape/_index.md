---
title: Shape()
second_title: Aspose.Slides для C++ справочник API
description: "Перебрать каждый ForEach::Shape в презентации."
type: docs
weight: 40
url: /ru/aspose.slides.lowcode/foreach/shape/
---
## ForEach::Shape(System::SharedPtr\<Presentation\>, ForEach::ForEachShapeCallback) метод

Перебрать каждый [ForEach::Shape](./) в [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, ForEach::ForEachShapeCallback forEachShape)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) для перебора фигур макета |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Обратный вызов, который будет вызван для каждой фигуры |

## Примечания

Фигуры будут перебираться во всех типах слайдов - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) и [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, callback);
```

## ForEach::Shape(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachShapeCallback) метод

Перебрать каждый [ForEach::Shape](./) в [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachShapeCallback forEachShape)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) для перебора фигур макета |
| includeNotes | **bool** | Флаг, указывающий, следует ли включать NotesSlides в обработку. |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Обратный вызов, который будет вызван для каждой фигуры |

## Примечания

Фигуры будут перебираться во всех типах слайдов - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) и [NotesSlide](../../../aspose.slides/notesslide/) при необходимости.

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    System::Console::WriteLine(u"{0}, index: {1}", shape->get_Name(), index);
};
auto callback = std::function<void(SharedPtr<Shape> shape, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Shape(pres, true, callback);
```

## ForEach::Shape(System::SharedPtr\<BaseSlide\>, ForEach::ForEachShapeCallback) метод

Перебрать каждый [ForEach::Shape](./) в [BaseSlide](../../../aspose.slides/baseslide/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Shape(System::SharedPtr<BaseSlide> baseSlide, ForEach::ForEachShapeCallback forEachShape)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseSlide | [System::SharedPtr](../../../system/sharedptr/)\<[BaseSlide](../../../aspose.slides/baseslide/)\> | [Slide](../../../aspose.slides/slide/) для перебора фигур макета |
| forEachShape | [ForEach::ForEachShapeCallback](../foreachshapecallback/) | Обратный вызов, который будет вызван для каждой фигуры |

## Примечания

[BaseSlide](../../../aspose.slides/baseslide/) является базовым типом для [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) и [ForEach::LayoutSlide](../layoutslide/)

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

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachShapeCallback](../foreachshapecallback/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Класс [ForEach](../)
* Класс [BaseSlide](../../../aspose.slides/baseslide/)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)