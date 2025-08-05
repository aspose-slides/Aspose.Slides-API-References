---
title: ForEach
second_title: Aspose.Sildes for .NET API Reference
description: Represents a group of methods intended to iterate over different Presentation../aspose.slides/presentation model objects. These methods can be useful if you need to iterate and change some Presentation elements formatting or content e.g. change each portion formatting.
type: docs
weight: 7810
url: /aspose.slides.lowcode/foreach/
---

## ForEach class

Represents a group of methods intended to iterate over different [`Presentation`](../../aspose.slides/presentation) model objects. These methods can be useful if you need to iterate and change some Presentation' elements formatting or content, e.g. change each portion formatting.

```csharp
public static class ForEach
```

## Methods

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterate each [`LayoutSlide`](./layoutslide) in the [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterate each [`MasterSlide`](./masterslide) in the [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterate each [`Paragraph`](./paragraph) in the [`Presentation`](../../aspose.slides/presentation). Shapes will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) and [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterate each [`Paragraph`](./paragraph) in the [`Presentation`](../../aspose.slides/presentation). Shapes will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) and [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterate each [`Portion`](./portion) in the [`Presentation`](../../aspose.slides/presentation). Portions will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) and [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterate each [`Portion`](./portion) in the [`Presentation`](../../aspose.slides/presentation). Portions will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) and [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterate each [`Shape`](./shape) in the [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) is the base type for [`Slide`](./slide), [`MasterSlide`](./masterslide) and [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterate each [`Shape`](./shape) in the [`Presentation`](../../aspose.slides/presentation). Shapes will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) and [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterate each [`Shape`](./shape) in the [`Presentation`](../../aspose.slides/presentation). Shapes will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) and [`NotesSlide`](../../aspose.slides/notesslide) if needed. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterate each [`Slide`](./slide) in the [`Presentation`](../../aspose.slides/presentation). |

## Other Members

| Name | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback that will be invoked for each [`LayoutSlide`](./layoutslide) in the [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback that will be invoked for each [`MasterSlide`](./masterslide) in the [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback that will be invoked for each [`Paragraph`](./paragraph) on the [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback that will be invoked for each [`Portion`](./portion) in the [`Paragraph`](./paragraph) on the [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback that will be invoked for each [`Shape`](./shape) in the [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback that will be invoked for each [`Slide`](./slide) in the [`Presentation`](../../aspose.slides/presentation). |

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
