---
title: PresentationAnimationsGenerator
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un generador de las animaciones en la Presentación../aspose.slides/presentation.
type: docs
weight: 4190
url: /es/aspose.slides.export/presentationanimationsgenerator/
---

## Clase PresentationAnimationsGenerator

Representa un generador de las animaciones en la [`Presentation`](../../aspose.slides/presentation).

```csharp
public class PresentationAnimationsGenerator : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PresentationAnimationsGenerator](presentationanimationsgenerator#constructor)(Presentation) | Crea una nueva instancia de [`PresentationAnimationsGenerator`](../presentationanimationsgenerator). |
| [PresentationAnimationsGenerator](presentationanimationsgenerator#constructor_1)(Size) | Crea una nueva instancia de [`PresentationAnimationsGenerator`](../presentationanimationsgenerator). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultDelay](../../aspose.slides.export/presentationanimationsgenerator/defaultdelay) { get; set; } | Obtiene o establece el tiempo de retraso por defecto [ms]. |
| [ExportedSlides](../../aspose.slides.export/presentationanimationsgenerator/exportedslides) { get; } | Obtiene el número de las diapositivas exportadas. |
| [IncludeHiddenSlides](../../aspose.slides.export/presentationanimationsgenerator/includehiddenslides) { get; set; } | Obtiene o establece si se deben incluir las diapositivas ocultas. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.slides.export/presentationanimationsgenerator/dispose)() | Libera la instancia de [`PresentationAnimationsGenerator`](../presentationanimationsgenerator). |
| [Run](../../aspose.slides.export/presentationanimationsgenerator/run#run)(IEnumerable&lt;ISlide&gt;) | Ejecuta la generación de eventos de animación para cada diapositiva. |
| [Run](../../aspose.slides.export/presentationanimationsgenerator/run#run_1)(IEnumerable&lt;ISlide&gt;, int, FrameTickHandler) | Ejecuta la generación de eventos de animación para cada diapositiva. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [FrameSize](../../aspose.slides.export/presentationanimationsgenerator/framesize) | Obtiene el tamaño del marco. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [NewAnimation](../../aspose.slides.export/presentationanimationsgenerator/newanimation) | Un evento que representa que se generó una nueva animación. |

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("animated.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(presentation))
    using (var player = new PresentationPlayer(animationsGenerator, 33))
    {
        player.FrameTick += (sender, args) =>
        {
            args.GetFrame().Save($"frame_{sender.FrameIndex}.png");
        };

        animationsGenerator.Run(presentation.Slides);
    }
}
```

### Véase También

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->