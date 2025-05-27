---
title: FrameIndex
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene el índice de fotograma.
type: docs
weight: 20
url: /es/aspose.slides.export/presentationplayer/frameindex/
---

## Propiedad PresentationPlayer.FrameIndex

Obtiene el índice de fotograma.

```csharp
public int FrameIndex { get; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(pres))
    using (var player = new PresentationPlayer(animationsGenerator, 33))
    {
        player.FrameTick += (sender, args) =>
        {
            args.GetFrame().Save($"frame_{sender.FrameIndex}.png");
        };
        
        animationsGenerator.Run(pres.Slides);
    }
}
```

### Ver También

* clase [PresentationPlayer](../../presentationplayer)
* espacio de nombres [Aspose.Slides.Export](../../presentationplayer)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->