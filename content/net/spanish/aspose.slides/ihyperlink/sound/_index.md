---
title: Sound
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa el sonido que se reproduce del hipervínculo. Lectura/escritura IAudioaspose.slides/iaudio.
type: docs
weight: 70
url: /es/aspose.slides/ihyperlink/sound/
---

## Propiedad IHyperlink.Sound

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
        // Extraer el sonido del hipervínculo en un arreglo de bytes
        byte[] audioData = link.Sound.BinaryData;
    }
}
```

### Ver También

* interfaz [IAudio](../../iaudio)
* interfaz [IHyperlink](../../ihyperlink)
* espacio de nombres [Aspose.Slides](../../ihyperlink)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->