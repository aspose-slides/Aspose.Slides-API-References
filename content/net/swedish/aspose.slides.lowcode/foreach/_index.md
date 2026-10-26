---
title: ForEach
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en grupp av metoder avsedda att iterera över olika Presentation../aspose.slides/presentation-modellobjekt. Dessa metoder kan vara användbara om du behöver iterera och ändra vissa Presentation-elementens formatering eller innehåll, t.ex. ändra varje portions formatering.
type: docs
weight: 7900
url: /sv/aspose.slides.lowcode/foreach/
---
## ForEach klass

Representerar en grupp av metoder avsedda att iterera över olika [`Presentation`](../../aspose.slides/presentation) modellobjekt. Dessa metoder kan vara användbara om du behöver iterera och ändra några Presentation-elementens format eller innehåll, t.ex. ändra varje portionsformat.

```csharp
public static class ForEach
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterera varje [`LayoutSlide`](./layoutslide) i [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterera varje [`MasterSlide`](./masterslide) i [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterera varje [`Paragraph`](./paragraph) i [`Presentation`](../../aspose.slides/presentation). Former kommer att itereras i alla typer av bilder - [`Slide`](./slide), [`MasterSlide`](./masterslide) och [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterera varje [`Paragraph`](./paragraph) i [`Presentation`](../../aspose.slides/presentation). Former kommer att itereras i alla typer av bilder - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) och [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterera varje [`Portion`](./portion) i [`Presentation`](../../aspose.slides/presentation). Delar kommer att itereras i alla typer av bilder - [`Slide`](./slide), [`MasterSlide`](./masterslide) och [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterera varje [`Portion`](./portion) i [`Presentation`](../../aspose.slides/presentation). Delar kommer att itereras i alla typer av bilder - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) och [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterera varje [`Shape`](./shape) i [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) är bastypen för [`Slide`](./slide), [`MasterSlide`](./masterslide) och [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterera varje [`Shape`](./shape) i [`Presentation`](../../aspose.slides/presentation). Former kommer att itereras i alla typer av bilder - [`Slide`](./slide), [`MasterSlide`](./masterslide) och [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterera varje [`Shape`](./shape) i [`Presentation`](../../aspose.slides/presentation). Former kommer att itereras i alla typer av bilder - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) och [`NotesSlide`](../../aspose.slides/notesslide) om det behövs. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterera varje [`Slide`](./slide) i [`Presentation`](../../aspose.slides/presentation). |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Återanrop som kommer att anropas för varje [`LayoutSlide`](./layoutslide) i [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Återanrop som kommer att anropas för varje [`MasterSlide`](./masterslide) i [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Återanrop som kommer att anropas för varje [`Paragraph`](./paragraph) på [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Återanrop som kommer att anropas för varje [`Portion`](./portion) i [`Paragraph`](./paragraph) på [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Återanrop som kommer att anropas för varje [`Shape`](./shape) i [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Återanrop som kommer att anropas för varje [`Slide`](./slide) i [`Presentation`](../../aspose.slides/presentation). |

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