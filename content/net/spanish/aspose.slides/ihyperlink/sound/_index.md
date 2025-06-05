---
title: Sound
second_title: Aspose.Slides para la referencia de API de .NET
description: Representa el sonido en reproducción del hipervínculo. Lectura/escritura IAudioaspose.slides/iaudio.
type: docs
weight: 70
url: /es/aspose.slides/ihyperlink/sound/
---

## IHyperlink.Sound property

Representa el sonido en reproducción del hipervínculo. Lectura/escritura [`IAudio`](../../iaudio).

```csharp
public IAudio Sound { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];
    
    // Obtener el primer hipervínculo de forma
    IHyperlink link = presentation.Slides[0].Shapes[0].HyperlinkClick;
       
    if (link.Sound != null)
    {
        // Extraer el sonido del hipervínculo en un arreglo de bytes
        byte[] audioData = link.Sound.BinaryData;
    }
}
```

### También Vea

* interfaz [IAudio](../../iaudio)
* interfaz [IHyperlink](../../ihyperlink)
* espacio de nombres [Aspose.Slides](../../ihyperlink)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->