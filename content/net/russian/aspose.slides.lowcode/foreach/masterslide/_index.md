---
title: MasterSlide
second_title: Aspose.Sildes для справки по .NET API
description: Итерация каждого MasterSlideaspose.slides.lowcode/foreach/masterslide в Presentationaspose.slides/presentation.
type: docs
weight: 20
url: /ru/aspose.slides.lowcode/foreach/masterslide/
---

## Метод ForEach.MasterSlide

Итерация каждого `MasterSlide` в [`Presentation`](../../../aspose.slides/presentation).

```csharp
public static void MasterSlide(Presentation pres, ForEachMasterSlideCallback forEachMasterSlide)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | Presentation | Презентация для итерации мастер-слайдов |
| forEachMasterSlide | ForEachMasterSlideCallback | Обратный вызов, который будет вызван для каждого мастер-слайда |

### Примеры

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.MasterSlide(pres, (slide, index) =>
    {
        slide.Name = $"MasterSlide #{index}";
    });
} 
```

### См. Также

* класс [Presentation](../../../aspose.slides/presentation)
* делегат [ForEachMasterSlideCallback](../../foreach.foreachmasterslidecallback)
* класс [ForEach](../../foreach)
* пространство имен [Aspose.Slides.LowCode](../../foreach)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->