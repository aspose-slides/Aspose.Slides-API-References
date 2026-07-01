---
title: AlignShapes
second_title: Aspose.Sildes för .NET API-referens
description: Ändrar placeringen av alla former på bilden. Justerar formerna till marginalerna eller bildens kant eller justerar dem i förhållande till varandra.
type: docs
weight: 10
url: /sv/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Ändrar placeringen av alla former på bilden. Justerar formerna till marginalerna eller bildens kant eller justerar dem i förhållande till varandra.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Anger vilken typ av justering som ska tillämpas. |
| alignToSlide | Boolean | Om true, kommer formerna att justeras i förhållande till bildens kanter. |
| slide | IBaseSlide | Överordnad bild. |

### Exempel

Exempel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Se även

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* gränssnitt [IBaseSlide](../../../aspose.slides/ibaseslide)
* klass [SlideUtil](../../slideutil)
* namnrymd [Aspose.Slides.Util](../../slideutil)
* samling [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Ändrar placeringen av valda former på bilden. Justerar formerna till marginalerna eller bildens kant eller justerar dem i förhållande till varandra.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Anger vilken typ av justering som ska tillämpas. |
| alignToSlide | Boolean | Om true, kommer formerna att justeras i förhållande till bildens kanter. |
| slide | IBaseSlide | Överordnad bild. |
| shapeIndexes | Int32[] | Index för former som ska justeras. |

### Exempel

Exempel:

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

### Se även

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* gränssnitt [IBaseSlide](../../../aspose.slides/ibaseslide)
* klass [SlideUtil](../../slideutil)
* namnrymd [Aspose.Slides.Util](../../slideutil)
* samling [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Ändrar placeringen av alla former inom gruppformen. Justerar formerna till marginalerna eller bildens kant eller justerar dem i förhållande till varandra.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Anger vilken typ av justering som ska tillämpas. |
| alignToSlide | Boolean | Om true, kommer formerna att justeras i förhållande till bildens kanter. |
| groupShape | IGroupShape | Överordnad gruppform. |

### Exempel

Exempel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Se även

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* gränssnitt [IGroupShape](../../../aspose.slides/igroupshape)
* klass [SlideUtil](../../slideutil)
* namnrymd [Aspose.Slides.Util](../../slideutil)
* samling [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Ändrar placeringen av valda former inom gruppformen. Justerar formerna till marginalerna eller bildens kant eller justerar dem i förhållande till varandra.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Anger vilken typ av justering som ska tillämpas. |
| alignToSlide | Boolean | Om true, kommer formerna att justeras i förhållande till bildens kanter. |
| groupShape | IGroupShape | Överordnad gruppform. |
| shapeIndexes | Int32[] | Index för former som ska justeras. |

### Exempel

Exempel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Se även

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* gränssnitt [IGroupShape](../../../aspose.slides/igroupshape)
* klass [SlideUtil](../../slideutil)
* namnrymd [Aspose.Slides.Util](../../slideutil)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->