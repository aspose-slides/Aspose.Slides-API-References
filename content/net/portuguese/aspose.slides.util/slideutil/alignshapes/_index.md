---
title: AlignShapes
second_title: Referência da API Aspose.Sildes para .NET
description: Altera a posição de todas as formas no slide. Alinha as formas às margens ou à borda do slide ou as alinha em relação umas às outras.
type: docs
weight: 10
url: /pt/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Altera a posição de todas as formas no slide. Alinha as formas às margens ou à borda do slide ou as alinha em relação umas às outras.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qual tipo de alinhamento será aplicado. |
| alignToSlide | Boolean | Se verdadeiro, as formas serão alinhadas em relação às bordas do slide. |
| slide | IBaseSlide | Slide pai. |

### Exemplos

Exemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Veja Também

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* classe [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Altera a posição das formas selecionadas no slide. Alinha as formas às margens ou à borda do slide ou as alinha em relação umas às outras.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qual tipo de alinhamento será aplicado. |
| alignToSlide | Boolean | Se verdadeiro, as formas serão alinhadas em relação às bordas do slide. |
| slide | IBaseSlide | Slide pai. |
| shapeIndexes | Int32[] | Índices das formas a serem alinhadas. |

### Exemplos

Exemplo:

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

### Veja Também

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IBaseSlide](../../../aspose.slides/ibaseslide)
* classe [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Altera a posição de todas as formas dentro do grupo de formas. Alinha as formas às margens ou à borda do slide ou as alinha em relação umas às outras.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qual tipo de alinhamento será aplicado. |
| alignToSlide | Boolean | Se verdadeiro, as formas serão alinhadas em relação às bordas do slide. |
| groupShape | IGroupShape | Grupo de formas pai. |

### Exemplos

Exemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Veja Também

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* classe [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Altera a posição das formas selecionadas dentro do grupo de formas. Alinha as formas às margens ou à borda do slide ou as alinha em relação umas às outras.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina qual tipo de alinhamento será aplicado. |
| alignToSlide | Boolean | Se verdadeiro, as formas serão alinhadas em relação às bordas do slide. |
| groupShape | IGroupShape | Grupo de formas pai. |
| shapeIndexes | Int32[] | Índices das formas a serem alinhadas. |

### Exemplos

Exemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Veja Também

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interface [IGroupShape](../../../aspose.slides/igroupshape)
* classe [SlideUtil](../../slideutil)
* namespace [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->