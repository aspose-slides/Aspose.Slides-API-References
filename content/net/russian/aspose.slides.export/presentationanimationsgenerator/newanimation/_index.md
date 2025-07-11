---
title: NewAnimation
second_title: Aspose.Sildes for .NET API Reference
description: Событие представляет собой новую анимацию, которая была сгенерирована.
type: docs
weight: 60
url: /ru/aspose.slides.export/presentationanimationsgenerator/newanimation/
---

## PresentationAnimationsGenerator.NewAnimation событие

Событие представляет собой новую анимацию, которая была сгенерирована.

```csharp
public event Action<IPresentationAnimationPlayer> NewAnimation;
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("SimpleAnimations.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(presentation.SlideSize.Size.ToSize()))
    {
        animationsGenerator.NewAnimation += animationPlayer =>
        {
            Console.WriteLine($"Общая продолжительность анимации: {animationPlayer.Duration}");
      };
        
        animationsGenerator.Run(presentation.Slides);
    }
}
```

### Смотрите Также

* interface [IPresentationAnimationPlayer](../../ipresentationanimationplayer)
* class [PresentationAnimationsGenerator](../../presentationanimationsgenerator)
* namespace [Aspose.Slides.Export](../../presentationanimationsgenerator)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->