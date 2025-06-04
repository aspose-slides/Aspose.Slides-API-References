---
title: StopPreviousSound
second_title: Aspose.Sildes для .NET API Reference
description: Этот атрибут указывает, останавливает ли анимационный эффект предыдущее звучание. Читаемое/записываемое логическое значение.
type: docs
weight: 90
url: /ru/aspose.slides.animation/ieffect/stopprevioussound/
---

## IEffect.StopPreviousSound property

Этот атрибут указывает, останавливает ли анимационный эффект предыдущее звучание. Читаемое/записываемое логическое значение.

```csharp
public bool StopPreviousSound { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Получить первый эффект первого слайда.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Получить первый эффект второго слайда.
    IEffect secondSlideEffect = presentation.Slides[1].Timeline.MainSequence[0];
       
    if (firstSlideEffect.Sound != null)
    {
        // Изменить второй эффект Enhancements/Sound на "Остановить предыдущее звучание"
        secondSlideEffect.StopPreviousSound = true;
    }
}
```

### См. также

* интерфейс [IEffect](../../ieffect)
* пространство имен [Aspose.Slides.Animation](../../ieffect)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->