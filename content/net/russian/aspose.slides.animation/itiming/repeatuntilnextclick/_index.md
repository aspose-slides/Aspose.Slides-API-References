---
title: RepeatUntilNextClick
second_title: Aspose.Sildes для .NET API Справочник
description: Этот атрибут указывает, будет ли эффект повторяться до следующего щелчка. Читаемое/записываемое логическое значение.
type: docs
weight: 80
url: /ru/aspose.slides.animation/itiming/repeatuntilnextclick/
---

## ITiming.RepeatUntilNextClick свойство

Этот атрибут указывает, будет ли эффект повторяться до следующего щелчка. Читаемое/записываемое логическое значение.

```csharp
public bool RepeatUntilNextClick { get; set; }
```

### Примеры

```csharp
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Получить последовательность эффектов для первого слайда
    ISequence effectsSequence = presentation.Slides[0].Timeline.MainSequence;

    // Получить первый эффект главной последовательности.
    IEffect effect = effectsSequence[0];

    // Изменить время эффекта / Повтор на "До следующего щелчка"
    effect.Timing.RepeatUntilNextClick = true;
}
```

### См. также

* интерфейс [ITiming](../../itiming)
* пространство имен [Aspose.Slides.Animation](../../itiming)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->