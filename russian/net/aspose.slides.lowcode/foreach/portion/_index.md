---
title: Portion
second_title: Справочник по API Aspose.Slides для .NET
description: Итерировать каждыйPortionaspose.slides.lowcode/foreach/portion вPresentationaspose.slides/presentation . Части будут повторяться во всех типах слайдов -Slideaspose.slides.lowcode/foreach/slide MasterSlideaspose.slides.lowcode/foreach/masterslide а такжеLayoutSlideaspose.slides.lowcode/foreach/layoutslide
type: docs
weight: 40
url: /ru/net/aspose.slides.lowcode/foreach/portion/
---
## ForEach.Portion method

Итерировать каждый`Portion` в[`Presentation`](../../../aspose.slides/presentation) . Части будут повторяться во всех типах слайдов -[`Slide`](../slide) ,[`MasterSlide`](../masterslide) а также[`LayoutSlide`](../layoutslide)

```csharp
public static void Portion(Presentation pres, ForEachPortionCallback forEachPortion)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | Presentation | Презентация повторяющихся частей |
| forEachPortion | ForEachPortionCallback | Обратный вызов, который будет вызываться для каждой порции |

### Примеры

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.Portion(pres, (portion, para, slide, index) =>
    {
        System.Console.WriteLine($"{portion.Text}, index: {index}");
    });
} 
```

### Смотрите также

* class [Presentation](../../../aspose.slides/presentation)
* delegate [ForEachPortionCallback](../../foreach.foreachportioncallback)
* class [ForEach](../../foreach)
* пространство имен [Aspose.Slides.LowCode](../../foreach)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
