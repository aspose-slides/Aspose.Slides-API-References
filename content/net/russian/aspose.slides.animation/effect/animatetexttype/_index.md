---
title: AnimateTextType
second_title: Aspose.Sildes для .NET API Справочник
description: Определяет тип анимации текста для эффекта. Текст формы может быть анимирован по буквам, по словам или сразу. Чтение/запись AnimateTextType.
type: docs
weight: 30
url: /ru/aspose.slides.animation/effect/animatetexttype/
---

## Effect.AnimateTextType свойство

Определяет тип анимации текста для эффекта. Текст формы может быть анимирован по буквам, по словам или сразу. Чтение/запись `AnimateTextType`.

```csharp
public AnimateTextType AnimateTextType { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Получить первый эффект первого слайда.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Изменить тип анимации текста на "По буквам"
    firstSlideEffect.AnimateTextType = AnimateTextType.ByLetter;
}
```

### См. Также

* enum [AnimateTextType](../../animatetexttype)
* class [Effect](../../effect)
* namespace [Aspose.Slides.Animation](../../effect)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->