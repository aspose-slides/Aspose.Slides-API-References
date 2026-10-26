---
title: ForEach
second_title: Aspose.Sildes для .NET справочник API
description: Представляет группу методов, предназначенных для перебора различных объектов модели Presentation../aspose.slides/presentation. Эти методы могут быть полезны, если нужно перебрать и изменить форматирование или содержимое некоторых элементов Presentation, например изменить форматирование каждой части.
type: docs
weight: 7900
url: /ru/aspose.slides.lowcode/foreach/
---
## ForEach класс

Представляет группу методов, предназначенных для перебора различных [`Presentation`](../../aspose.slides/presentation) объектов модели. Эти методы могут быть полезны, если вам нужно перебрать и изменить форматирование или содержимое некоторых элементов Presentation, например изменить форматирование каждой части.

```csharp
public static class ForEach
```

## Методы

| Имя | Описание |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Перебрать каждый [`LayoutSlide`](./layoutslide) в [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Перебрать каждый [`MasterSlide`](./masterslide) в [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Перебрать каждый [`Paragraph`](./paragraph) в [`Presentation`](../../aspose.slides/presentation). Формы будут перебираться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Перебрать каждый [`Paragraph`](./paragraph) в [`Presentation`](../../aspose.slides/presentation). Формы будут перебираться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Перебрать каждый [`Portion`](./portion) в [`Presentation`](../../aspose.slides/presentation). Части будут перебираться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Перебрать каждый [`Portion`](./portion) в [`Presentation`](../../aspose.slides/presentation). Части будут перебираться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Перебрать каждый [`Shape`](./shape) в [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) является базовым типом для [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Перебрать каждый [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). Формы будут перебираться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Перебрать каждый [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). Формы будут перебираться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) при необходимости. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Перебрать каждый [`Slide`](./slide) в [`Presentation`](../../aspose.slides/presentation). |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Обратный вызов, который будет выполнен для каждого [`LayoutSlide`](./layoutslide) в [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Обратный вызов, который будет выполнен для каждого [`MasterSlide`](./masterslide) в [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Обратный вызов, который будет выполнен для каждого [`Paragraph`](./paragraph) на [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Обратный вызов, который будет выполнен для каждого [`Portion`](./portion) в [`Paragraph`](./paragraph) на [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Обратный вызов, который будет выполнен для каждого [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Обратный вызов, который будет выполнен для каждого [`Slide`](./slide) в [`Presentation`](../../aspose.slides/presentation). |

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

### См. также

* пространство имён [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->