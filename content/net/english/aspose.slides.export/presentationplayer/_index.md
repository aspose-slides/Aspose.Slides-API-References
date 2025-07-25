---
title: PresentationPlayer
second_title: Aspose.Sildes for .NET API Reference
description: Represents the player of animations associated with the Presentation../aspose.slides/presentation.
type: docs
weight: 4260
url: /aspose.slides.export/presentationplayer/
---

## PresentationPlayer class

Represents the player of animations associated with the [`Presentation`](../../aspose.slides/presentation).

```csharp
public class PresentationPlayer : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [PresentationPlayer](presentationplayer)(PresentationAnimationsGenerator, double) | Creates new instance of the [`PresentationPlayer`](../presentationplayer). |

## Properties

| Name | Description |
| --- | --- |
| [FrameIndex](../../aspose.slides.export/presentationplayer/frameindex) { get; } | Gets the frame index. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.slides.export/presentationplayer/dispose)() | Disposes the instance of the [`PresentationPlayer`](../presentationplayer). |

## Other Members

| Name | Description |
| --- | --- |
| delegate [FrameTickHandler](presentationplayer.frametickhandler) | Represents the frame tick handler of [`FrameTick`](./frametick) event. |

### Examples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(pres))
    {
        // Play animation with 33 FPS
        using (var player = new PresentationPlayer(animationsGenerator, 33))
        {
            player.FrameTick += (sender, args) =>
            {
                args.GetFrame().Save(Path.Combine("33fps", $"frame_{sender.FrameIndex}.png"));
            };

            animationsGenerator.Run(pres.Slides);
        }
        
        // Play animation with 45 FPS
        using (var player = new PresentationPlayer(animationsGenerator, 45))
        {
            player.FrameTick += (sender, args) =>
            {
                args.GetFrame().Save(Path.Combine("45fps", $"frame_{sender.FrameIndex}.png"));
            };

            animationsGenerator.Run(pres.Slides);
        }
    }
}
```

### See Also

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
