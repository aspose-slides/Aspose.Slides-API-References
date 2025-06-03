---
title: Sound
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa el sonido que se reproduce del hipervínculo. Lectura/escritura IAudioaspose.slides/iaudio.
type: docs
weight: 160
url: /es/aspose.slides/hyperlink/sound/
---

## Propiedad Hyperlink.Sound

Representa el sonido que se reproduce del hipervínculo. Lectura/escritura [`IAudio`](../../iaudio).

```csharp
public IAudio Sound { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];
    
    // Obtener el hipervínculo de la primera forma
    IHyperlink link = presentation.Slides[0].Shapes[0].HyperlinkClick;
       
    if (link.Sound != null)
    {
        // Extraer el sonido del hipervínculo en un array de bytes
        byte[] audioData = link.Sound.BinaryData;
    }
}
```

### Ve También

* interfaz [IAudio](../../iaudio)
* clase [Hyperlink](../../hyperlink)
* espacio de nombres [Aspose.Slides](../../hyperlink)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->