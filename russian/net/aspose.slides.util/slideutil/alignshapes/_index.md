---
title: AlignShapes
second_title: Справочник по API Aspose.Slides для .NET
description: Изменяет расположение всех фигур на слайде. Выравнивает фигуры по полям или краю слайда или выравнивает их относительно друг друга.
type: docs
weight: 10
url: /ru/net/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Изменяет расположение всех фигур на слайде. Выравнивает фигуры по полям или краю слайда или выравнивает их относительно друг друга.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Определяет, какой тип выравнивания будет применяться. |
| alignToSlide | Boolean | Если true, фигуры будут выровнены относительно краев слайда. |
| slide | IBaseSlide | Родительский слайд. |

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Смотрите также

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* пространство имен [Aspose.Slides.Util](../../slideutil)
* сборка [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Изменяет размещение выбранных фигур на слайде. Выравнивает фигуры по полям или краю слайда или выравнивает их относительно друг друга.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Определяет, какой тип выравнивания будет применяться. |
| alignToSlide | Boolean | Если true, фигуры будут выровнены относительно краев слайда. |
| slide | IBaseSlide | Родительский слайд. |
| shapeIndexes | Int32[] | Индексы фигур для выравнивания. |

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   ISlide slide = pres.Slides[0];
   IShape shape1 = slide.Shapes[0];
   IShape shape2 = slide.Shapes[1]; 

   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, false, pres.Slides[0], new int[]
   {
      slide.Shapes.IndexOf(shape1),
      slide.Shapes.IndexOf(shape2)
   });
}
```

### Смотрите также

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* пространство имен [Aspose.Slides.Util](../../slideutil)
* сборка [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Изменяет размещение всех фигур в групповой форме. Выравнивает фигуры по полям или краю слайда или выравнивает их относительно друг друга.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Определяет, какой тип выравнивания будет применяться. |
| alignToSlide | Boolean | Если true, фигуры будут выровнены относительно краев слайда. |
| groupShape | IGroupShape | Форма родительской группы. |

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Смотрите также

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* пространство имен [Aspose.Slides.Util](../../slideutil)
* сборка [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Изменяет размещение выбранных фигур внутри групповой фигуры. Выравнивает фигуры по полям или краю слайда или выравнивает их относительно друг друга.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Определяет, какой тип выравнивания будет применяться. |
| alignToSlide | Boolean | Если true, фигуры будут выровнены относительно краев слайда. |
| groupShape | IGroupShape | Форма родительской группы. |
| shapeIndexes | Int32[] | Индексы фигур для выравнивания. |

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Смотрите также

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* пространство имен [Aspose.Slides.Util](../../slideutil)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
