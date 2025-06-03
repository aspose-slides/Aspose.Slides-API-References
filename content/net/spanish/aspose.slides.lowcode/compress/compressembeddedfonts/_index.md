---
title: CompressEmbeddedFonts
second_title: Referencia de API de Aspose.Slides para .NET
description: Realiza la compresión de la Presentación aspose.slides/presentation eliminando caracteres no utilizados de las fuentes incrustadas.
type: docs
weight: 10
url: /es/aspose.slides.lowcode/compress/compressembeddedfonts/
---

## Método Compress.CompressEmbeddedFonts

Realiza la compresión de la [`Presentation`](../../../aspose.slides/presentation) eliminando caracteres no utilizados de las fuentes incrustadas.

```csharp
public static void CompressEmbeddedFonts(Presentation pres)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | Presentation | La instancia de la presentación |

### Ejemplos

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Véase también

* clase [Presentation](../../../aspose.slides/presentation)
* clase [Compress](../../compress)
* espacio de nombres [Aspose.Slides.LowCode](../../compress)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->