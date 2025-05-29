---
title: RemoveUnusedLayoutSlides
second_title: Referencia de la API Aspose.Slides para .NET
description: Realiza la compresión de la Presentationaspose.slides/../aspose.slides/presentation eliminando las diapositivas de diseño no utilizadas.
type: docs
weight: 20
url: /es/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---

## Método Compress.RemoveUnusedLayoutSlides

Realiza la compresión de la [`Presentation`](../../../aspose.slides/presentation) eliminando las diapositivas de diseño no utilizadas.

```csharp
public static void RemoveUnusedLayoutSlides(Presentation pres)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | Presentation | La instancia de la presentación |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Véase también

* clase [Presentation](../../../aspose.slides/presentation)
* clase [Compress](../../compress)
* espacio de nombres [Aspose.Slides.LowCode](../../compress)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->