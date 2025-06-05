---
title: AlignShapes
second_title: Référence de l'API Aspose.Slides pour .NET
description: Modifie le placement de toutes les formes sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.
type: docs
weight: 10
url: /fr/aspose.slides.util/slideutil/alignshapes/
---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Modifie le placement de toutes les formes sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Détermine quel type d'alignement sera appliqué. |
| alignToSlide | Boolean | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| slide | IBaseSlide | Diapositive parente. |

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Voir Aussi

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Modifie le placement des formes sélectionnées sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Détermine quel type d'alignement sera appliqué. |
| alignToSlide | Boolean | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| slide | IBaseSlide | Diapositive parente. |
| shapeIndexes | Int32[] | Index des formes à aligner. |

### Exemples

Exemple:

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

### Voir Aussi

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](="../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Modifie le placement de toutes les formes au sein d'un groupe de formes. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Détermine quel type d'alignement sera appliqué. |
| alignToSlide | Boolean | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| groupShape | IGroupShape | Groupe de formes parent. |

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Voir Aussi

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Modifie le placement des formes sélectionnées au sein d'un groupe de formes. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Détermine quel type d'alignement sera appliqué. |
| alignToSlide | Boolean | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| groupShape | IGroupShape | Groupe de formes parent. |
| shapeIndexes | Int32[] | Index des formes à aligner. |

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Voir Aussi

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->