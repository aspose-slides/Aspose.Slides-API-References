---
title: Slide
second_title: Aspose.Slides для .NET API Reference
description: Итерация каждого Slide в Presentation.
type: docs
weight: 60
url: /ru/aspose.slides.lowcode/foreach/slide/
---

## ForEach.Slide метод

Итерация каждого `Slide` в [`Presentation`](../../../aspose.slides/presentation).

```csharp
public static void Slide(Presentation pres, ForEachSlideCallback forEachSlide)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | Presentation | Презентация для итерации слайдов |
| forEachSlide | ForEachSlideCallback | Коллбек, который будет вызван для каждого слайда |

### Примеры

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.Slide(pres, (slide, index) =>
    {
        slide.Name = $"Slide #{index}";
    });
} 
```

### Смотрите Также

* класс [Presentation](../../../aspose.slides/presentation)
* делегат [ForEachSlideCallback](../../foreach.foreachslidecallback)
* класс [ForEach](../../foreach)
* пространство имен [Aspose.Slides.LowCode](../../foreach)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->