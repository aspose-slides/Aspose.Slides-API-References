---
title: AlignShapes
second_title: Aspose.Sildes для .NET API Справочник
description: Изменяет расположение всех фигур на слайде. Выравнивает фигуры по краям или границам слайда или выравнивает их относительно друг друга.
type: docs
weight: 10
url: /ru/aspose.slides.util/slideutil/alignshapes/
---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Изменяет расположение всех фигур на слайде. Выравнивает фигуры по краям или границам слайда или выравнивает их относительно друг друга.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Определяет, какой тип выравнивания будет применен. |
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

### Смотрите Также

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Изменяет расположение выбранных фигур на слайде. Выравнивает фигуры по краям или границам слайда или выравнивает их относительно друг друга.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Определяет, какой тип выравнивания будет применен. |
| alignToSlide | Boolean | Если true, фигуры будут выровнены относительно краев слайда. |
| slide | IBaseSlide | Родительский слайд. |
| shapeIndexes | Int32[] | Индексы фигур, которые нужно выровнять. |

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

### Смотрите Также

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Изменяет расположение всех фигур внутри группы. Выравнивает фигуры по краям или границам слайда или выравнивает их относительно друг друга.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Определяет, какой тип выравнивания будет применен. |
| alignToSlide | Boolean | Если true, фигуры будут выровнены относительно краев слайда. |
| groupShape | IGroupShape | Родительская группа фигур. |

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Смотрите Также

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Изменяет расположение выбранных фигур внутри группы. Выравнивает фигуры по краям или границам слайда или выравнивает их относительно друг друга.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Определяет, какой тип выравнивания будет применен. |
| alignToSlide | Boolean | Если true, фигуры будут выровнены относительно краев слайда. |
| groupShape | IGroupShape | Родительская группа фигур. |
| shapeIndexes | Int32[] | Индексы фигур, которые нужно выровнять. |

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Смотрите Также

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->