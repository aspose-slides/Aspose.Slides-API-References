---
title: LayoutSlide
second_title: Referencia de API de Aspose.Slides para .NET
description: Iterar cada LayoutSlide aspose.slides.lowcode/foreach/layoutslide en la Presentación aspose.slides/presentation.
type: docs
weight: 10
url: /es/aspose.slides.lowcode/foreach/layoutslide/
---

## Método ForEach.LayoutSlide

Iterar cada `LayoutSlide` en la [`Presentation`](../../../aspose.slides/presentation).

```csharp
public static void LayoutSlide(Presentation pres, ForEachLayoutSlideCallback forEachLayoutSlide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | Presentation | Presentación para iterar diapositivas de diseño |
| forEachLayoutSlide | ForEachLayoutSlideCallback | Callback que será invocado para cada diapositiva de diseño |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.LayoutSlide(pres, (layoutSlide, index) =>
    {
        layoutSlide.Name = $"LayoutSlide #{index}";
    });
} 
```

### También Vea

* clase [Presentation](../../../aspose.slides/presentation)
* delegado [ForEachLayoutSlideCallback](../../foreach.foreachlayoutslidecallback)
* clase [ForEach](../../foreach)
* espacio de nombres [Aspose.Slides.LowCode](../../foreach)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->