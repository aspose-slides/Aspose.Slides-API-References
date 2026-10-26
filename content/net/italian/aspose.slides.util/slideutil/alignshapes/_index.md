---
title: AlignShapes
second_title: Riferimento API Aspose.Sildes per .NET
description: Modifica la posizione di tutte le forme nella diapositiva. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.
type: docs
weight: 10
url: /it/aspose.slides.util/slideutil/alignshapes/
---
## AlignShapes(ShapesAlignmentType, bool, IBaseSlide) {#alignshapes}

Modifica la posizione di tutte le forme nella diapositiva. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina quale tipo di allineamento verrà applicato. |
| alignToSlide | Boolean | Se true, le forme saranno allineate rispetto ai bordi della diapositiva. |
| slide | IBaseSlide | Diapositiva genitore. |

### Esempi

Esempio:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignBottom, true, pres.Slides);
}
```

### Vedi anche

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interfaccia [IBaseSlide](../../../aspose.slides/ibaseslide)
* classe [SlideUtil](../../slideutil)
* spazio dei nomi [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IBaseSlide, int[]) {#alignshapes_1}

Modifica la posizione delle forme selezionate nella diapositiva. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IBaseSlide slide, int[] shapeIndexes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina quale tipo di allineamento verrà applicato. |
| alignToSlide | Boolean | Se true, le forme saranno allineate rispetto ai bordi della diapositiva. |
| slide | IBaseSlide | Diapositiva genitore. |
| shapeIndexes | Int32[] | Indici delle forme da allineare. |

### Esempi

Esempio:

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

### Vedi anche

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interfaccia [IBaseSlide](../../../aspose.slides/ibaseslide)
* classe [SlideUtil](../../slideutil)
* spazio dei nomi [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape) {#alignshapes_2}

Modifica la posizione di tutte le forme all'interno della forma di gruppo. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina quale tipo di allineamento verrà applicato. |
| alignToSlide | Boolean | Se true, le forme saranno allineate rispetto ai bordi della diapositiva. |
| groupShape | IGroupShape | Forma di gruppo genitore. |

### Esempi

Esempio:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0]);
}
```

### Vedi anche

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interfaccia [IGroupShape](../../../aspose.slides/igroupshape)
* classe [SlideUtil](../../slideutil)
* spazio dei nomi [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

---

## AlignShapes(ShapesAlignmentType, bool, IGroupShape, int[]) {#alignshapes_3}

Modifica la posizione delle forme selezionate all'interno della forma di gruppo. Allinea le forme ai margini o al bordo della diapositiva o le allinea tra loro.

```csharp
public static void AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, 
    IGroupShape groupShape, int[] shapeIndexes)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alignmentType | ShapesAlignmentType | Determina quale tipo di allineamento verrà applicato. |
| alignToSlide | Boolean | Se true, le forme saranno allineate rispetto ai bordi della diapositiva. |
| groupShape | IGroupShape | Forma di gruppo genitore. |
| shapeIndexes | Int32[] | Indici delle forme da allineare. |

### Esempi

Esempio:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
   SlideUtil.AlignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.Shapes[0], new int[] { 0, 2 });
}
```

### Vedi anche

* enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype)
* interfaccia [IGroupShape](../../../aspose.slides/igroupshape)
* classe [SlideUtil](../../slideutil)
* spazio dei nomi [Aspose.Slides.Util](../../slideutil)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->