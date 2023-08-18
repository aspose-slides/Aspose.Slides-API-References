---
title: AlignShapes
second_title: Référence de l'API Aspose.Slides pour .NET
description: Modifie le placement de toutes les formes sur la diapositive. Aligne les formes sur les marges ou le bord de la diapositive ou les aligne les unes par rapport aux autres.
type: docs
weight: 10
url: /fr/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Modifie le placement de toutes les formes sur la diapositive. Aligne les formes sur les marges ou le bord de la diapositive ou les aligne les unes par rapport aux autres.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Détermine le type d'alignement qui sera appliqué. |
| alignToSlide | Boolean | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| slide | IBaseSlide | Diapositive parent. |

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Voir également

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* espace de noms [Aspose.Slides.Util](../../slideutil)
* Assemblée [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Modifie l'emplacement des formes sélectionnées sur la diapositive. Aligne les formes sur les marges ou le bord de la diapositive ou les aligne les unes par rapport aux autres.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Détermine le type d'alignement qui sera appliqué. |
| alignToSlide | Boolean | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| slide | IBaseSlide | Diapositive parent. |
| shapeIndexes | Int32[] | Index des formes à aligner. |

### Exemples

Exemple :

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

### Voir également

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* espace de noms [Aspose.Slides.Util](../../slideutil)
* Assemblée [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Modifie le placement de toutes les formes dans la forme du groupe. Aligne les formes sur les marges ou le bord de la diapositive ou les aligne les unes par rapport aux autres.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Détermine le type d'alignement qui sera appliqué. |
| alignToSlide | Boolean | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| groupShape | IGroupShape | Forme du groupe parent. |

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Voir également

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* espace de noms [Aspose.Slides.Util](../../slideutil)
* Assemblée [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Modifie le placement des formes sélectionnées dans la forme du groupe. Aligne les formes sur les marges ou le bord de la diapositive ou les aligne les unes par rapport aux autres.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Détermine le type d'alignement qui sera appliqué. |
| alignToSlide | Boolean | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| groupShape | IGroupShape | Forme du groupe parent. |
| shapeIndexes | Int32[] | Index des formes à aligner. |

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Voir également

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* espace de noms [Aspose.Slides.Util](../../slideutil)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
