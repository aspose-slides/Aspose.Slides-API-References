---
title: AlignShapes
second_title: Aspose.Sildes voor .NET API-referentie
description: Wijzigt de plaatsing van alle vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia, of lijnt ze ten opzichte van elkaar uit.
type: docs
weight: 10
url: /nl/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Wijzigt de plaatsing van alle vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia, of lijnt ze ten opzichte van elkaar uit.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | IBaseSlide | Bovenliggende dia. |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Zie ook

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* klasse [SlideUtil](../../slideutil)
* naamruimte [Aspose.Slides.Util](../../slideutil)
* assemblage [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Wijzigt de plaatsing van geselecteerde vormen op de dia. Lijnt vormen uit op de marges of de rand van de dia, of lijnt ze ten opzichte van elkaar uit.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | IBaseSlide | Bovenliggende dia. |
| shapeIndexes | Int32[] | Indexes of shapes to be aligned. |

### Voorbeelden

Voorbeeld:

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

### Zie ook

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* klasse [SlideUtil](../../slideutil)
* naamruimte [Aspose.Slides.Util](../../slideutil)
* assemblage [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Wijzigt de plaatsing van alle vormen binnen een groepvorm. Lijnt vormen uit op de marges of de rand van de dia, of lijnt ze ten opzichte van elkaar uit.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | IGroupShape | Bovenliggende groepsvorm. |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Zie ook

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* klasse [SlideUtil](../../slideutil)
* naamruimte [Aspose.Slides.Util](../../slideutil)
* assemblage [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Wijzigt de plaatsing van geselecteerde vormen binnen een groepvorm. Lijnt vormen uit op de marges of de rand van de dia, of lijnt ze ten opzichte van elkaar uit.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determines which type of alignment will be applied. |
| alignToSlide | Boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | IGroupShape | Bovenliggende groepsvorm. |
| shapeIndexes | Int32[] | Indexes of shapes to be aligned. |

### Voorbeelden

Voorbeeld:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Zie ook

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* klasse [SlideUtil](../../slideutil)
* naamruimte [Aspose.Slides.Util](../../slideutil)
* assemblage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->