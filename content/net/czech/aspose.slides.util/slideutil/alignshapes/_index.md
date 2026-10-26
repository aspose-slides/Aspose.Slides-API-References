---
title: AlignShapes
second_title: Aspose.Sildes pro .NET – reference API
description: Mění umístění všech tvarů na snímku. Zarovnává tvary k okrajům nebo k hraně snímku nebo je zarovnává relativně k sobě navzájem.
type: docs
weight: 10
url: /cs/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Mění umístění všech tvarů na snímku. Zarovnává tvary k okrajům nebo k hraně snímku nebo je zarovnává relativně k sobě navzájem.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Určuje, který typ zarovnání bude použit. |
| alignToSlide | Boolean | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| slide | IBaseSlide | Nadřazený snímek. |

### Příklady

Příklad:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Viz také

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* rozhraní [IBaseSlide](../../../aspose.slides/ibaseslide)
* třída [SlideUtil](../../slideutil)
* jmenný prostor [Aspose.Slides.Util](../../slideutil)
* sestavení [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Mění umístění vybraných tvarů na snímku. Zarovnává tvary k okrajům nebo k hraně snímku nebo je zarovnává relativně k sobě navzájem.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Určuje, který typ zarovnání bude použit. |
| alignToSlide | Boolean | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| slide | IBaseSlide | Nadřazený snímek. |
| shapeIndexes | Int32[] | Indexy tvarů, které mají být zarovnány. |

### Příklady

Příklad:

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

### Viz také

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* rozhraní [IBaseSlide](../../../aspose.slides/ibaseslide)
* třída [SlideUtil](../../slideutil)
* jmenný prostor [Aspose.Slides.Util](../../slideutil)
* sestavení [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Mění umístění všech tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo k hraně snímku nebo je zarovnává relativně k sobě navzájem.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Určuje, který typ zarovnání bude použit. |
| alignToSlide | Boolean | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| groupShape | IGroupShape | Nadřazený skupinový tvar. |

### Příklady

Příklad:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Viz také

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* rozhraní [IGroupShape](../../../aspose.slides/igroupshape)
* třída [SlideUtil](../../slideutil)
* jmenný prostor [Aspose.Slides.Util](../../slideutil)
* sestavení [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Mění umístění vybraných tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo k hraně snímku nebo je zarovnává relativně k sobě navzájem.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Určuje, který typ zarovnání bude použit. |
| alignToSlide | Boolean | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| groupShape | IGroupShape | Nadřazený skupinový tvar. |
| shapeIndexes | Int32[] | Indexy tvarů, které mají být zarovnány. |

### Příklady

Příklad:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Viz také

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* rozhraní [IGroupShape](../../../aspose.slides/igroupshape)
* třída [SlideUtil](../../slideutil)
* jmenný prostor [Aspose.Slides.Util](../../slideutil)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->