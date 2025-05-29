---
title: WriteAsEmf
second_title: Referencia de API de Aspose.Slidess para .NET
description: Guarda el contenido de la diapositiva como un archivo EMF.
type: docs
weight: 130
url: /es/aspose.slides/slide/writeasemf/
---

## Método Slide.WriteAsEmf

Guarda el contenido de la diapositiva como un archivo EMF.

```csharp
public void WriteAsEmf(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo objetivo |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | El flujo objetivo es `null` |

### Ejemplos

El siguiente ejemplo de código demuestra cómo convertir la primera diapositiva de una presentación de PowerPoint en un metafile.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (Stream fileStream = System.IO.File.Create("slide_1.emf"))
    {
        // Guarda la primera diapositiva como un metafile
        pres.Slides[0].WriteAsEmf(fileStream);
    }
}
```

### Véase también

* clase [Slide](../../slide)
* espacio de nombres [Aspose.Slides](../../slide)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->