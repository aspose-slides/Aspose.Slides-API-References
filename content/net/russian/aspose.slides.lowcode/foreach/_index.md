---
title: ForEach
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет собой группу методов, предназначенных для итерации по различным объектам модели Presentationaspose.slides/aspose.slides/presentation. Эти методы могут быть полезны, если вам нужно пройтись и изменить форматирование или содержимое некоторых элементов презентации, например, изменить форматирование каждой порции.
type: docs
weight: 7660
url: /ru/aspose.slides.lowcode/foreach/
---

## Класс ForEach

Представляет собой группу методов, предназначенных для итерации по различным [`Presentation`](../../aspose.slides/presentation) объектам модели. Эти методы могут быть полезны, если вам нужно пройтись и изменить форматирование или содержимое некоторых элементов презентации, например, изменить форматирование каждой порции.

```csharp
public static class ForEach
```

## Методы

| Имя | Описание |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Итерация по каждой [`LayoutSlide`](./layoutslide) в [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Итерация по каждому [`MasterSlide`](./masterslide) в [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Итерация по каждому [`Paragraph`](./paragraph) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итераться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Итерация по каждому [`Paragraph`](./paragraph) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итераться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Итерация по каждой [`Portion`](./portion) в [`Presentation`](../../aspose.slides/presentation). Порции будут итераться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Итерация по каждой [`Portion`](./portion) в [`Presentation`](../../aspose.slides/presentation). Порции будут итераться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Итерация по каждой [`Shape`](./shape) в [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) является базовым типом для [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Итерация по каждой [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итераться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Итерация по каждой [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итераться во всех типах слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide), если это необходимо. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Итерация по каждому [`Slide`](./slide) в [`Presentation`](../../aspose.slides/presentation). |

## Другие Члены

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

### См. также

* пространство имен [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->