---
title: RemoveUnusedLayoutSlides
second_title: Referencia de la API de Aspose.Slides para .NET
description: Realiza la compresión delPresentationaspose.slides/presentation eliminando las diapositivas de diseño no utilizadas.
type: docs
weight: 10
url: /es/net/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress.RemoveUnusedLayoutSlides method

Realiza la compresión del[`Presentation`](../../../aspose.slides/presentation) eliminando las diapositivas de diseño no utilizadas.

```csharp
public static void RemoveUnusedLayoutSlides(Presentation pres)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pres | Presentation | La instancia de presentación |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Ver también

* class [Presentation](../../../aspose.slides/presentation)
* class [Compress](../../compress)
* espacio de nombres [Aspose.Slides.LowCode](../../compress)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->