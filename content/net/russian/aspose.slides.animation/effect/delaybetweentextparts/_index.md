---
title: DelayBetweenTextParts
second_title: Справочник по API Aspose.Slides для .NET
description: Определяет задержку между анимированными текстовыми частями словами или буквами. Положительное значение указывает процент от продолжительности эффекта. Отрицательное значение указывает задержку в секундах. Чтение/запись Single.
type: docs
weight: 50
url: /ru/aspose.slides.animation/effect/delaybetweentextparts/
---

## Effect.DelayBetweenTextParts свойство

Определяет задержку между анимированными текстовыми частями (словами или буквами). Положительное значение указывает процент от продолжительности эффекта. Отрицательное значение указывает задержку в секундах. Чтение/запись Single.

```csharp
public float DelayBetweenTextParts { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Получить первый эффект первого слайда.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Изменить тип анимации текста на "По словам"
    firstSlideEffect.AnimateTextType = AnimateTextType.ByWord;
    
    // Установить задержку между анимированными текстовыми частями на 20% от продолжительности эффекта.
    firstSlideEffect.DelayBetweenTextParts = 20f;
}
```

### См. также

* class [Effect](../../effect)
* namespace [Aspose.Slides.Animation](../../effect)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->