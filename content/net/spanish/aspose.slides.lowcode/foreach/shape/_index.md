---
title: Shape
second_title: Referencia de la API de Aspose.Slides para .NET
description: Iterar cadaShapeaspose.slides.lowcode/foreach/shape en elPresentationaspose.slides/presentation .  Las formas se repetirán en todo tipo de diapositivasSlideaspose.slides.lowcode/foreach/slide MasterSlideaspose.slides.lowcode/foreach/masterslide yLayoutSlideaspose.slides.lowcode/foreach/layoutslide
type: docs
weight: 50
url: /es/aspose.slides.lowcode/foreach/shape/
---
## Shape(Presentation, ForEachShapeCallback) {#shape_1}

Iterar cada`Shape` en el[`Presentation`](../../../aspose.slides/presentation) .  Las formas se repetirán en todo tipo de diapositivas:[`Slide`](../slide) ,[`MasterSlide`](../masterslide) y[`LayoutSlide`](../layoutslide)

```csharp
public static void Shape(Presentation pres, ForEachShapeCallback forEachShape)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pres | Presentation | Presentación para iterar formas de diseño |
| forEachShape | ForEachShapeCallback | Devolución de llamada que se invocará para cada forma |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.Shape(pres, (shape, slide, index) => 
    {
        System.Console.WriteLine($"{shape.Name}, index: {index}");
    });
} 
```

### Ver también

* class [Presentation](../../../aspose.slides/presentation)
* delegate [ForEachShapeCallback](../../foreach.foreachshapecallback)
* class [ForEach](../../foreach)
* espacio de nombres [Aspose.Slides.LowCode](../../foreach)
* asamblea [Aspose.Slides](../../../)

---

## Shape(BaseSlide, ForEachShapeCallback) {#shape}

Iterar cada[`Shape`](../shape) en el[`BaseSlide`](../../../aspose.slides/baseslide) . [`BaseSlide`](../../../aspose.slides/baseslide) es el tipo base para[`Slide`](../slide) ,[`MasterSlide`](../masterslide) y[`LayoutSlide`](../layoutslide)

```csharp
public static void Shape(BaseSlide baseSlide, ForEachShapeCallback forEachShape)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| baseSlide | BaseSlide | Deslizar para iterar formas de diseño |
| forEachShape | ForEachShapeCallback | Devolución de llamada que se invocará para cada forma |

### Ejemplos

```csharp
(Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.Slide(pres, (slide, index) =>
    {
        ForEach.Shape(slide, (shape, baseSlide, shapeIndex) =>
        {
            System.Console.WriteLine($"{shape.Name}, index: {shapeIndex}");
        });
    });
} 
```

### Ver también

* class [BaseSlide](../../../aspose.slides/baseslide)
* delegate [ForEachShapeCallback](../../foreach.foreachshapecallback)
* class [ForEach](../../foreach)
* espacio de nombres [Aspose.Slides.LowCode](../../foreach)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
