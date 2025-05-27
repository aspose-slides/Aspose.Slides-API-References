---
title: MasterSlide
second_title: Referencia de API de Aspose.Slides para .NET
description: Iterar cada MasterSlideaspose.slides.lowcode/foreach/masterslide en la Presentaciónaspose.slides/presentation.
type: docs
weight: 20
url: /es/aspose.slides.lowcode/foreach/masterslide/
---

## Método ForEach.MasterSlide

Iterar cada `MasterSlide` en la [`Presentation`](../../../aspose.slides/presentation).

```csharp
public static void MasterSlide(Presentation pres, ForEachMasterSlideCallback forEachMasterSlide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | Presentation | Presentación para iterar sobre las diapositivas maestras |
| forEachMasterSlide | ForEachMasterSlideCallback | Callback que se invocará para cada diapositiva maestra |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.MasterSlide(pres, (slide, index) =>
    {
        slide.Name = $"MasterSlide #{index}";
    });
} 
```

### Véase también

* clase [Presentation](../../../aspose.slides/presentation)
* delegado [ForEachMasterSlideCallback](../../foreach.foreachmasterslidecallback)
* clase [ForEach](../../foreach)
* espacio de nombres [Aspose.Slides.LowCode](../../foreach)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->