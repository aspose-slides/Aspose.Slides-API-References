---
title: GetFrame
second_title: Aspose.Slides para .NET Referencia API
description: Obtén el marco actual de PresentationPlayeraspose.slides.export/presentationplayer.
type: docs
weight: 20
url: /es/aspose.slides.export/frametickeventargs/getframe/
---

## Método FrameTickEventArgs.GetFrame

Obtén el marco actual de [`PresentationPlayer`](../../presentationplayer).

```csharp
public IImage GetFrame()
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(pres))
    using (var player = new PresentationPlayer(animationsGenerator, 33))
    {
        int frameNumber = 0;
        player.FrameTick += (sender, args) =>
        {
            args.GetFrame().Save($"frame_{frameNumber++}.png");
        };
        
        animationsGenerator.Run(pres.Slides);
    }
}
```

### También Puedes Ver

* interface [IImage](../../../aspose.slides/iimage)
* class [FrameTickEventArgs](../../frametickeventargs)
* namespace [Aspose.Slides.Export](../../frametickeventargs)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITES: generado por xmldocmd para Aspose.Slides.dll -->