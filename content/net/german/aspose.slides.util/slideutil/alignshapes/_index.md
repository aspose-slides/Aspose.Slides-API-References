---
title: AlignShapes
second_title: Aspose.Slides für .NET API-Referenz
description: Ändert die Platzierung aller Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.
type: docs
weight: 10
url: /de/aspose.slides.util/slideutil/alignshapes/
---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Ändert die Platzierung aller Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | Boolean | Wenn wahr, werden die Formen relativ zu den Folienrändern ausgerichtet. |
| slide | IBaseSlide | Übergeordnete Folie. |

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Siehe Auch

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Ändert die Platzierung ausgewählter Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | Boolean | Wenn wahr, werden die Formen relativ zu den Folienrändern ausgerichtet. |
| slide | IBaseSlide | Übergeordnete Folie. |
| shapeIndexes | Int32[] | Indizes der auszurichtenden Formen. |

### Beispiele

Beispiel:

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

### Siehe Auch

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Ändert die Platzierung aller Formen innerhalb der Gruppierungsform. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | Boolean | Wenn wahr, werden die Formen relativ zu den Folienrändern ausgerichtet. |
| groupShape | IGroupShape | Übergeordnete Gruppierungsform. |

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Siehe Auch

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Ändert die Platzierung ausgewählter Formen innerhalb der Gruppierungsform. Richtet Formen an den Rändern oder am Rand der Folie aus oder richtet sie relativ zueinander aus.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | Boolean | Wenn wahr, werden die Formen relativ zu den Folienrändern ausgerichtet. |
| groupShape | IGroupShape | Übergeordnete Gruppierungsform. |
| shapeIndexes | Int32[] | Indizes der auszurichtenden Formen. |

### Beispiele

Beispiel:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Siehe Auch

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->