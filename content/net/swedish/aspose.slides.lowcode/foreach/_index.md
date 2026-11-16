---
title: ForEach
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en grupp av metoder som är avsedda att iterera över olika Presentation../aspose.slides/presentation modellobjekt. Dessa metoder kan vara användbara om du behöver iterera och ändra vissa Presentation-elementens formatering eller innehåll, t.ex. ändra varje portions formatering.
type: docs
weight: 7920
url: /sv/aspose.slides.lowcode/foreach/
---
## ForEach-klass

Representerar en grupp av metoder avsedda att iterera över olika [`Presentation`](../../aspose.slides/presentation) modellobjekt. Dessa metoder kan vara användbara om du behöver iterera och ändra formatering eller innehåll för vissa Presentation-element, t.ex. ändra formatering för varje del.

```csharp
public static class ForEach
```

## Metoder

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterera varje [`LayoutSlide`](./layoutslide) i [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterera varje [`MasterSlide`](./masterslide) i [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterera varje [`Paragraph`](./paragraph) i [`Presentation`](../../aspose.slides/presentation). Shapes kommer att itereras i alla typer av bilder – [`Slide`](./slide), [`MasterSlide`](./masterslide) och [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterera varje [`Paragraph`](./paragraph) i [`Presentation`](../../aspose.slides/presentation). Shapes kommer att itereras i alla typer av bilder – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) och [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterera varje [`Portion`](./portion) i [`Presentation`](../../aspose.slides/presentation). Portions kommer att itereras i alla typer av bilder – [`Slide`](./slide), [`MasterSlide`](./masterslide) och [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterera varje [`Portion`](./portion) i [`Presentation`](../../aspose.slides/presentation). Portions kommer att itereras i alla typer av bilder – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) och [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterera varje [`Shape`](./shape) i [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) är basklassen för [`Slide`](./slide), [`MasterSlide`](./masterslide) och [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterera varje [`Shape`](./shape) i [`Presentation`](../../aspose.slides/presentation). Shapes kommer att itereras i alla typer av bilder – [`Slide`](./slide), [`MasterSlide`](./masterslide) och [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterera varje [`Shape`](./shape) i [`Presentation`](../../aspose.slides/presentation). Shapes kommer att itereras i alla typer av bilder – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) och [`NotesSlide`](../../aspose.slides/notesslide) vid behov. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterera varje [`Slide`](./slide) i [`Presentation`](../../aspose.slides/presentation). |

## Andra medlemmar

| Name | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback som kommer att anropas för varje [`LayoutSlide`](./layoutslide) i [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback som kommer att anropas för varje [`MasterSlide`](./masterslide) i [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback som kommer att anropas för varje [`Paragraph`](./paragraph) på [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback som kommer att anropas för varje [`Portion`](./portion) i [`Paragraph`](./paragraph) på [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback som kommer att anropas för varje [`Shape`](./shape) i [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback som kommer att anropas för varje [`Slide`](./slide) i [`Presentation`](../../aspose.slides/presentation). |

### Exempel

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

### Se även

* namnrymd [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->