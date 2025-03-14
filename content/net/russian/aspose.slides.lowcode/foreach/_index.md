---
title: ForEach
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет группу методов предназначенных для перебора различныхPresentation../aspose.slides/presentationобъектов модели. Эти методы могут быть полезны если вам нужно повторить и изменить форматирование или содержимое некоторых элементов презентации например изменить форматирование каждой части.
type: docs
weight: 7200
url: /ru/aspose.slides.lowcode/foreach/
---
## ForEach class

Представляет группу методов, предназначенных для перебора различных[`Presentation`](../../aspose.slides/presentation)объектов модели. Эти методы могут быть полезны, если вам нужно повторить и изменить форматирование или содержимое некоторых элементов презентации, например, изменить форматирование каждой части.

```csharp
public static class ForEach
```

## Методы

| Имя | Описание |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Итерировать каждый[`LayoutSlide`](./layoutslide)в[`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Итерировать каждый[`MasterSlide`](./masterslide)в[`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph)(Presentation, ForEachParagraphCallback) | Итерировать каждый[`Paragraph`](./paragraph)в[`Presentation`](../../aspose.slides/presentation).  Формы будут повторяться во всех типах слайдов -[`Slide`](./slide),[`MasterSlide`](./masterslide)и[`LayoutSlide`](./layoutslide): |
| static [Portion](../../aspose.slides.lowcode/foreach/portion)(Presentation, ForEachPortionCallback) | Итерация каждого[`Portion`](./portion)в[`Presentation`](../../aspose.slides/presentation).  Части будут повторяться во всех типах слайдов -[`Slide`](./slide),[`MasterSlide`](./masterslide)и[`LayoutSlide`](./layoutslide): |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Итерировать каждый[`Shape`](./shape)в[`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide)является базовым типом дляForEachSlideCallback),[`MasterSlide`](./masterslide)и[`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, ForEachShapeCallback) | Итерировать каждый[`Shape`](./shape)в[`Presentation`](../../aspose.slides/presentation).  Формы будут повторяться во всех типах слайдов -[`Slide`](./slide),[`MasterSlide`](./masterslide)и[`LayoutSlide`](./layoutslide): |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Итерировать каждый[`Slide`](./slide)в[`Presentation`](../../aspose.slides/presentation). |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) |  |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) |  |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) |  |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) |  |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) |  |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) |  |

### Примеры

```csharp
using (Presentation presentation = new Presentation("pres.pptx"))
{
   ForEach.Portion(presentation, (portion, para, slide, index) =>
   {
       portion.PortionFormat.LatinFont = new FontData("Times New Roman");
   });
  
   presentation.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Смотрите также

* пространство имен [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
