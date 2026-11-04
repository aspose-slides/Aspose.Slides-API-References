---
title: ForEach
second_title: Справка API Aspose.Sildes для .NET
description: Представляет группу методов, предназначенных для перебора различных объектов модели Presentation../aspose.slides/presentation. Эти методы могут быть полезны, если вам нужно перебрать и изменить форматирование или содержание некоторых элементов Presentation, например изменить форматирование каждой части.
type: docs
weight: 7920
url: /ru/aspose.slides.lowcode/foreach/
---
## ForEach класс

Представляет группу методов, предназначенных для перебора различных [`Presentation`](../../aspose.slides/presentation) объектов модели. Эти методы могут быть полезны, если необходимо перебрать и изменить форматирование или содержание некоторых элементов Presentation, например изменить форматирование каждой части.

```csharp
public static class ForEach
```

## Методы

| Имя | Описание |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Итерировать каждый [`LayoutSlide`](./layoutslide) в [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Итерировать каждый [`MasterSlide`](./masterslide) в [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Итерировать каждый [`Paragraph`](./paragraph) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итерироваться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Итерировать каждый [`Paragraph`](./paragraph) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итерироваться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Итерировать каждый [`Portion`](./portion) в [`Presentation`](../../aspose.slides/presentation). Части будут итерироваться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Итерировать каждый [`Portion`](./portion) в [`Presentation`](../../aspose.slides/presentation). Части будут итерироваться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Итерировать каждый [`Shape`](./shape) в [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) является базовым типом для [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Итерировать каждый [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итерироваться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Итерировать каждый [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итерироваться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide), если это необходимо. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Итерировать каждый [`Slide`](./slide) в [`Presentation`](../../aspose.slides/presentation). |

## Другие члены

| Имя | Описание |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Обратный вызов, который будет вызываться для каждого [`LayoutSlide`](./layoutslide) в [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Обратный вызов, который будет вызываться для каждого [`MasterSlide`](./masterslide) в [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Обратный вызов, который будет вызываться для каждого [`Paragraph`](./paragraph) на [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Обратный вызов, который будет вызываться для каждого [`Portion`](./portion) в [`Paragraph`](./paragraph) на [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Обратный вызов, который будет вызываться для каждого [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Обратный вызов, который будет вызываться для каждого [`Slide`](./slide) в [`Presentation`](../../aspose.slides/presentation). |

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

* пространство имён [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->