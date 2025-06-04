---
title: ForEach
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет собой группу методов, предназначенных для итерации по различным объектам модели Presentation../aspose.slides/presentation. Эти методы могут быть полезны, если вам необходимо просматривать и изменять форматирование или содержимое некоторых элементов Presentation, например, изменять форматирование каждой порции.
type: docs
weight: 7660
url: /ru/aspose.slides.lowcode/foreach/
---

## ForEach class

Представляет собой группу методов, предназначенных для итерации по различным [`Presentation`](../../aspose.slides/presentation) модельным объектам. Эти методы могут быть полезны, если вам необходимо просматривать и изменять форматирование или содержимое некоторых элементов Presentation, например, изменять форматирование каждой порции.

```csharp
public static class ForEach
```

## Methods

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Итерация по каждому [`LayoutSlide`](./layoutslide) в [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Итерация по каждому [`MasterSlide`](./masterslide) в [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Итерация по каждому [`Paragraph`](./paragraph) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итерации по всем типам слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Итерация по каждому [`Paragraph`](./paragraph) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итерации по всем типам слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Итерация по каждому [`Portion`](./portion) в [`Presentation`](../../aspose.slides/presentation). Порции будут итерации по всем типам слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Итерация по каждому [`Portion`](./portion) в [`Presentation`](../../aspose.slides/presentation). Порции будут итерации по всем типам слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Итерация по каждому [`Shape`](./shape) в [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) является базовым типом для [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Итерация по каждому [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итерации по всем типам слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide) и [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Итерация по каждому [`Shape`](./shape) в [`Presentation`](../../aspose.slides/presentation). Фигуры будут итерации по всем типам слайдов - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) и [`NotesSlide`](../../aspose.slides/notesslide) при необходимости. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Итерация по каждому [`Slide`](./slide) в [`Presentation`](../../aspose.slides/presentation). |

## Other Members

| Name | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) |  |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) |  |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) |  |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) |  |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) |  |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) |  |

### Examples

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

### See Also

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->