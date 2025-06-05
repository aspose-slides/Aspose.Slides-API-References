---
title: ForEach
second_title: Aspose.Sildes for .NET API Reference
description: Representa un grupo de métodos destinados a iterar sobre diferentes objetos del modelo Presentation../aspose.slides/presentation. Estos métodos pueden ser útiles si necesitas iterar y cambiar el formato o contenido de algunos elementos de Presentación, por ejemplo, cambiar el formato de cada porción.
type: docs
weight: 7660
url: /es/aspose.slides.lowcode/foreach/
---

## ForEach class

Representa un grupo de métodos destinados a iterar sobre diferentes [`Presentation`](../../aspose.slides/presentation) modelos de objetos. Estos métodos pueden ser útiles si necesitas iterar y cambiar el formato o contenido de algunos elementos de Presentación, por ejemplo, cambiar el formato de cada porción.

```csharp
public static class ForEach
```

## Methods

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterar cada [`LayoutSlide`](./layoutslide) en la [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterar cada [`MasterSlide`](./masterslide) en la [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterar cada [`Paragraph`](./paragraph) en la [`Presentation`](../../aspose.slides/presentation). Las formas se iterarán en todos los tipos de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide) y [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterar cada [`Paragraph`](./paragraph) en la [`Presentation`](../../aspose.slides/presentation). Las formas se iterarán en todos los tipos de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) y [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterar cada [`Portion`](./portion) en la [`Presentation`](../../aspose.slides/presentation). Las porciones se iterarán en todos los tipos de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide) y [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterar cada [`Portion`](./portion) en la [`Presentation`](../../aspose.slides/presentation). Las porciones se iterarán en todos los tipos de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) y [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterar cada [`Shape`](./shape) en el [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) es el tipo base para [`Slide`](./slide), [`MasterSlide`](./masterslide) y [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterar cada [`Shape`](./shape) en la [`Presentation`](../../aspose.slides/presentation). Las formas se iterarán en todos los tipos de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide) y [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterar cada [`Shape`](./shape) en la [`Presentation`](../../aspose.slides/presentation). Las formas se iterarán en todos los tipos de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) y [`NotesSlide`](../../aspose.slides/notesslide) si es necesario. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterar cada [`Slide`](./slide) en la [`Presentation`](../../aspose.slides/presentation). |

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