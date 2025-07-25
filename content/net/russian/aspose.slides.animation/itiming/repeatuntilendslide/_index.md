---
title: RepeatUntilEndSlide
second_title: Aspose.Sildes для .NET API Reference
description: Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Читаемый/записываемый логический тип.
type: docs
weight: 70
url: /ru/aspose.slides.animation/itiming/repeatuntilendslide/
---

## ITiming.RepeatUntilEndSlide property

Этот атрибут указывает, будет ли эффект повторяться до конца слайда. Читаемый/записываемый логический тип.

```csharp
public bool RepeatUntilEndSlide { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Получить последовательность эффектов для первого слайда
    ISequence effectsSequence = presentation.Slides[0].Timeline.MainSequence;

    // Получить первый эффект главной последовательности.
    IEffect effect = effectsSequence[0];

    // Изменить время эффекта/повтор на "До конца слайда"
    effect.Timing.RepeatUntilEndSlide = true;
}
```

### Смотрите Также

* интерфейс [ITiming](../../itiming)
* пространство имен [Aspose.Slides.Animation](../../itiming)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->