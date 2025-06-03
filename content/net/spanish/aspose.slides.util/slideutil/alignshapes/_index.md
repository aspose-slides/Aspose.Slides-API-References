---
title: AlignShapes
second_title: Referencia de API de Aspose.Slides para .NET
description: Cambia la colocación de todas las formas en la diapositiva. Alinea las formas con los márgenes o el borde de la diapositiva o las alinea entre sí.
type: docs
weight: 10
url: /es/aspose.slides.util/slideutil/alignshapes/
---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Cambia la colocación de todas las formas en la diapositiva. Alinea las formas con los márgenes o el borde de la diapositiva o las alinea entre sí.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qué tipo de alineación se aplicará. |
| alignToSlide | Boolean | Si es verdadero, las formas se alinearán en relación con los bordes de la diapositiva. |
| slide | IBaseSlide | Diapositiva principal. |

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Ver También

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Cambia la colocación de las formas seleccionadas en la diapositiva. Alinea las formas con los márgenes o el borde de la diapositiva o las alinea entre sí.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qué tipo de alineación se aplicará. |
| alignToSlide | Boolean | Si es verdadero, las formas se alinearán en relación con los bordes de la diapositiva. |
| slide | IBaseSlide | Diapositiva principal. |
| shapeIndexes | Int32[] | Índices de las formas que se alinearán. |

### Ejemplos

Ejemplo:

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

### Ver También

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Cambia la colocación de todas las formas dentro de la forma de grupo. Alinea las formas con los márgenes o el borde de la diapositiva o las alinea entre sí.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qué tipo de alineación se aplicará. |
| alignToSlide | Boolean | Si es verdadero, las formas se alinearán en relación con los bordes de la diapositiva. |
| groupShape | IGroupShape | Forma de grupo principal. |

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Ver También

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Cambia la colocación de las formas seleccionadas dentro de la forma de grupo. Alinea las formas con los márgenes o el borde de la diapositiva o las alinea entre sí.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qué tipo de alineación se aplicará. |
| alignToSlide | Boolean | Si es verdadero, las formas se alinearán en relación con los bordes de la diapositiva. |
| groupShape | IGroupShape | Forma de grupo principal. |
| shapeIndexes | Int32[] | Índices de las formas que se alinearán. |

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Ver También

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* class [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->