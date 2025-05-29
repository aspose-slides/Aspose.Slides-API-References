---
title: Comprimir
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un grupo de métodos destinados a comprimir Presentation../aspose.slides/presentation.
type: docs
weight: 7630
url: /es/aspose.slides.lowcode/compress/
---

## Clase Compress

Representa un grupo de métodos destinados a comprimir [`Presentation`](../../aspose.slides/presentation).

```csharp
public static class Compress
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CompressEmbeddedFonts](../../aspose.slides.lowcode/compress/compressembeddedfonts)(Presentation) | Realiza la compresión de la [`Presentation`](../../aspose.slides/presentation) eliminando caracteres no utilizados de las fuentes embebidas. |
| static [RemoveUnusedLayoutSlides](../../aspose.slides.lowcode/compress/removeunusedlayoutslides)(Presentation) | Realiza la compresión de la [`Presentation`](../../aspose.slides/presentation) eliminando diapositivas de diseño no utilizadas. |
| static [RemoveUnusedMasterSlides](../../aspose.slides.lowcode/compress/removeunusedmasterslides)(Presentation) | Realiza la compresión de la [`Presentation`](../../aspose.slides/presentation) eliminando diapositivas maestra no utilizadas. |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedImages(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Véase También

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->