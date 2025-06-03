---
title: Slide
second_title: Referencia de la API de Aspose.Slides para .NET
description: Iterar cada Diapositiva aspose.slides.lowcode/foreach/slide en la Presentación aspose.slides/presentation.
type: docs
weight: 60
url: /es/aspose.slides.lowcode/foreach/slide/
---

## Método ForEach.Slide

Iterar cada `Slide` en la [`Presentation`](../../../aspose.slides/presentation).

```csharp
public static void Slide(Presentation pres, ForEachSlideCallback forEachSlide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | Presentation | Presentación para iterar diapositivas |
| forEachSlide | ForEachSlideCallback | Callback que será invocado para cada diapositiva |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.Slide(pres, (slide, index) =>
    {
        slide.Name = $"Slide #{index}";
    });
} 
```

### Vea También

* class [Presentation](../../../aspose.slides/presentation)
* delegate [ForEachSlideCallback](../../foreach.foreachslidecallback)
* class [ForEach](../../foreach)
* namespace [Aspose.Slides.LowCode](../../foreach)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
