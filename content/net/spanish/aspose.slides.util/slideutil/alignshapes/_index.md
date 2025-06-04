---
title: AlignShapes
second_title: Aspose.Sildes para .NET Referencia de API
description: Cambia la colocación de todas las formas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o alíneelas entre sí.
type: docs
weight: 10
url: /es/aspose.slides.util/slideutil/alignshapes/
---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Cambia la colocación de todas las formas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o alínealas entre sí.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qué tipo de alineación se aplicará. |
| alignToSlide | Boolean | Si es verdadero, las formas se alinearán respecto a los bordes de la diapositiva. |
| slide | IBaseSlide | Diapositiva padre. |

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

Cambia la colocación de formas seleccionadas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o alínealas entre sí.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qué tipo de alineación se aplicará. |
| alignToSlide | Boolean | Si es verdadero, las formas se alinearán respecto a los bordes de la diapositiva. |
| slide | IBaseSlide | Diapositiva padre. |
| shapeIndexes | Int32[] | Índices de las formas a alinear. |

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

Cambia la colocación de todas las formas dentro de un grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva o alínealas entre sí.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qué tipo de alineación se aplicará. |
| alignToSlide | Boolean | Si es verdadero, las formas se alinearán respecto a los bordes de la diapositiva. |
| groupShape | IGroupShape | Grupo de formas padre. |

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

Cambia la colocación de formas seleccionadas dentro de un grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva o alínealas entre sí.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qué tipo de alineación se aplicará. |
| alignToSlide | Boolean | Si es verdadero, las formas se alinearán respecto a los bordes de la diapositiva. |
| groupShape | IGroupShape | Grupo de formas padre. |
| shapeIndexes | Int32[] | Índices de las formas a alinear. |

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