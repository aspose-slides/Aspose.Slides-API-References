---
title: Sound
second_title: Aspose.Sildes для .NET API Reference
description: Определенный встроенный звук для эффекта. Чтение/запись IAudioaspose.slides/iaudio.
type: docs
weight: 80
url: /ru/aspose.slides.animation/ieffect/sound/
---

## IEffect.Sound свойство

Определенный встроенный звук для эффекта. Чтение/запись [`IAudio`](../../../aspose.slides/iaudio).

```csharp
public IAudio Sound { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];
    
    // Получает последовательность эффектов для слайда
    ISequence effectsSequence = slide.Timeline.MainSequence;
       
    foreach (IEffect effect in effectsSequence)
    {
        if (effect.Sound == null)
            continue;
        
        // Извлекает звук эффекта в массив байтов
        byte[] audio = effect.Sound.BinaryData;
    }
}
```

### См. также

* интерфейс [IAudio](../../../aspose.slides/iaudio)
* интерфейс [IEffect](../../ieffect)
* пространство имен [Aspose.Slides.Animation](../../ieffect)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->