---
title: AfterAnimationColor
second_title: Aspose.Slides для .NET API Справочник
description: Определен цвет после анимации для эффекта. Чтение/запись IColorFormataspose.slides/icolorformat.
type: docs
weight: 10
url: /ru/aspose.slides.animation/ieffect/afteranimationcolor/
---

## Свойство IEffect.AfterAnimationColor

Определен цвет после анимации для эффекта. Чтение/запись [`IColorFormat`](../../../aspose.slides/icolorformat).

```csharp
public IColorFormat AfterAnimationColor { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Получить первый эффект первого слайда.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Изменить тип эффекта после анимации на "Цвет"
    firstSlideEffect.AfterAnimationType = AfterAnimationType.Color;
    
    // Установить цвет эффекта после анимации.
    firstSlideEffect.AfterAnimationColor.Color = Color.Green;
}
```

### См. также

* интерфейс [IColorFormat](../../../aspose.slides/icolorformat)
* интерфейс [IEffect](../../ieffect)
* пространство имен [Aspose.Slides.Animation](../../ieffect)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->