---
title: ForEach
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa un grupo de métodos destinados a iterar sobre diferentes objetos modelo Presentation../aspose.slides/presentation. Estos métodos pueden ser útiles si necesita iterar y cambiar el formato o el contenido de algunos elementos de Presentation, p.ej. cambiar el formato de cada porción.
type: docs
weight: 7900
url: /es/aspose.slides.lowcode/foreach/
---
## ForEach clase

Representa un grupo de métodos destinados a iterar sobre diferentes [`Presentation`](../../aspose.slides/presentation) objetos modelo. Estos métodos pueden ser útiles si necesita iterar y cambiar el formato o el contenido de algunos elementos de Presentation, p.ej. cambiar el formato de cada porción.

```csharp
public static class ForEach
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterar cada [`LayoutSlide`](./layoutslide) en el [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterar cada [`MasterSlide`](./masterslide) en el [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterar cada [`Paragraph`](./paragraph) en el [`Presentation`](../../aspose.slides/presentation). Las formas se iterarán en todo tipo de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide) y [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterar cada [`Paragraph`](./paragraph) en el [`Presentation`](../../aspose.slides/presentation). Las formas se iterarán en todo tipo de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) y [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterar cada [`Portion`](./portion) en el [`Presentation`](../../aspose.slides/presentation). Las porciones se iterarán en todo tipo de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide) y [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterar cada [`Portion`](./portion) en el [`Presentation`](../../aspose.slides/presentation). Las porciones se iterarán en todo tipo de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) y [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterar cada [`Shape`](./shape) en el [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) es el tipo base para [`Slide`](./slide), [`MasterSlide`](./masterslide) y [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterar cada [`Shape`](./shape) en el [`Presentation`](../../aspose.slides/presentation). Las formas se iterarán en todo tipo de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide) y [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterar cada [`Shape`](./shape) en el [`Presentation`](../../aspose.slides/presentation). Las formas se iterarán en todo tipo de diapositivas - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) y [`NotesSlide`](../../aspose.slides/notesslide) si es necesario. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterar cada [`Slide`](./slide) en el [`Presentation`](../../aspose.slides/presentation). |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback que será invocado para cada [`LayoutSlide`](./layoutslide) en el [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback que será invocado para cada [`MasterSlide`](./masterslide) en el [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback que será invocado para cada [`Paragraph`](./paragraph) en el [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback que será invocado para cada [`Portion`](./portion) en el [`Paragraph`](./paragraph) en el [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback que será invocado para cada [`Shape`](./shape) en el [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback que será invocado para cada [`Slide`](./slide) en el [`Presentation`](../../aspose.slides/presentation). |

### Ejemplos

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

### Ver también

* espacio de nombres [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->