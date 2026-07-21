---
title: AlignShapes()
second_title: Справочник API Aspose.Slides для C++
description: Изменяет расположение всех фигур на слайде. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.
type: docs
weight: 27
url: /ru/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) метод

Изменяет расположение всех фигур на слайде. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Определяет, какой тип выравнивания будет применён. |
| alignToSlide | **bool** | Если true, фигуры будут выравнены относительно краёв слайда. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Родительский слайд. |

## Примечания

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) метод

Изменяет расположение выбранных фигур на слайде. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Определяет, какой тип выравнивания будет применён. |
| alignToSlide | **bool** | Если true, фигуры будут выравнены относительно краёв слайда. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Родительский слайд. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Индексы фигур, которые будут выравнены. |

## Примечания

Пример: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto slide = pres->get_Slides()->idx_get(0);
auto shape1 = slide->get_Shapes()->idx_get(0);
auto shape2 = slide->get_Shapes()->idx_get(1);
SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, false, pres->get_Slides()->idx_get(0),
    System::MakeArray<int32_t>({
        slide->get_Shapes()->IndexOf(shape1),
        slide->get_Shapes()->IndexOf(shape2)
    }));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) метод

Изменяет расположение всех фигур внутри групповой фигуры. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Определяет, какой тип выравнивания будет применён. |
| alignToSlide | **bool** | Если true, фигуры будут выравнены относительно краёв слайда. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Родительская групповая фигура. |

## Примечания

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) метод

Изменяет расположение выбранных фигур внутри групповой фигуры. Выравнивает фигуры по полям или краю слайда, либо относительно друг друга.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Определяет, какой тип выравнивания будет применён. |
| alignToSlide | **bool** | Если true, фигуры будут выравнены относительно краёв слайда. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Родительская групповая фигура. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Индексы фигур, которые будут выравнены. |

## Примечания

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Смотрите также

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Class [IGroupShape](../../../aspose.slides/igroupshape/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)