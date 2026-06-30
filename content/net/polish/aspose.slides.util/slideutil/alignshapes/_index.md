---
title: AlignShapes
second_title: Aspose.Sildes dla .NET – referencja API
description: Zmienia rozmieszczenie wszystkich kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.
type: docs
weight: 10
url: /pl/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Zmienia rozmieszczenie wszystkich kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | IBaseSlide | Parent slide. |

### Przykłady

Przykład:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Zobacz także

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interfejs [IBaseSlide](../../../aspose.slides/ibaseslide)
* klasa [SlideUtil](../../slideutil)
* przestrzeń nazw [Aspose.Slides.Util](../../slideutil)
* zestaw [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Zmienia rozmieszczenie wybranych kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | IBaseSlide | Parent slide. |
| shapeIndexes | Int32[] | Indexes of shapes to be aligned. |

### Przykłady

Przykład:

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

### Zobacz także

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interfejs [IBaseSlide](../../../aspose.slides/ibaseslide)
* klasa [SlideUtil](../../slideutil)
* przestrzeń nazw [Aspose.Slides.Util](../../slideutil)
* zestaw [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Zmienia rozmieszczenie wszystkich kształtów wewnątrz grupy kształtów. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | IGroupShape | Parent group shape. |

### Przykłady

Przykład:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Zobacz także

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interfejs [IGroupShape](../../../aspose.slides/igroupshape)
* klasa [SlideUtil](../../slideutil)
* przestrzeń nazw [Aspose.Slides.Util](../../slideutil)
* zestaw [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Zmienia rozmieszczenie wybranych kształtów wewnątrz grupy kształtów. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | IGroupShape | Parent group shape. |
| shapeIndexes | Int32[] | Indexes of shapes to be aligned. |

### Przykłady

Przykład:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Zobacz także

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interfejs [IGroupShape](../../../aspose.slides/igroupshape)
* klasa [SlideUtil](../../slideutil)
* przestrzeń nazw [Aspose.Slides.Util](../../slideutil)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->