---
title: RemoveUnusedMasterSlides
second_title: Referencia de la API de Aspose.Slides para .NET
description: Realiza la compresión delPresentationaspose.slides/presentation eliminando las diapositivas maestras no utilizadas.
type: docs
weight: 20
url: /es/net/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress.RemoveUnusedMasterSlides method

Realiza la compresión del[`Presentation`](../../../aspose.slides/presentation) eliminando las diapositivas maestras no utilizadas.

```csharp
public static void RemoveUnusedMasterSlides(Presentation pres)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pres | Presentation | La instancia de presentación |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Ver también

* class [Presentation](../../../aspose.slides/presentation)
* class [Compress](../../compress)
* espacio de nombres [Aspose.Slides.LowCode](../../compress)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->