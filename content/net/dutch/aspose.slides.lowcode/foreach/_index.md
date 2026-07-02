---
title: ForEach
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om over verschillende Presentation../aspose.slides/presentation modelobjecten te itereren. Deze methoden kunnen nuttig zijn als u moet itereren en de opmaak of inhoud van enkele Presentation elementen wilt wijzigen, bijvoorbeeld de opmaak van elk gedeelte wilt wijzigen.
type: docs
weight: 7900
url: /nl/aspose.slides.lowcode/foreach/
---
## ForEach klasse

Stelt een groep methoden voor die bedoeld zijn om over verschillende [`Presentation`](../../aspose.slides/presentation) modelobjecten te itereren. Deze methoden kunnen nuttig zijn als u moet itereren en de opmaak of inhoud van enkele Presentation-elementen wilt wijzigen, bijv. de opmaak van elk gedeelte wijzigen.

```csharp
public static class ForEach
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Itereren over elke [`LayoutSlide`](./layoutslide) in de [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Itereren over elke [`MasterSlide`](./masterslide) in de [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Itereren over elke [`Paragraph`](./paragraph) in de [`Presentation`](../../aspose.slides/presentation). Shapes zullen worden geïnterereerd in alle types dia's - [`Slide`](./slide), [`MasterSlide`](./masterslide) en [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Itereren over elke [`Paragraph`](./paragraph) in de [`Presentation`](../../aspose.slides/presentation). Shapes zullen worden geïnterereerd in alle types dia's - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) en [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Itereren over elke [`Portion`](./portion) in de [`Presentation`](../../aspose.slides/presentation). Portions zullen worden geïnterereerd in alle types dia's - [`Slide`](./slide), [`MasterSlide`](./masterslide) en [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Itereren over elke [`Portion`](./portion) in de [`Presentation`](../../aspose.slides/presentation). Portions zullen worden geïnterereerd in alle types dia's - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) en [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Itereren over elke [`Shape`](./shape) in de [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) is het basistype voor [`Slide`](./slide), [`MasterSlide`](./masterslide) en [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Itereren over elke [`Shape`](./shape) in de [`Presentation`](../../aspose.slides/presentation). Shapes zullen worden geïnterereerd in alle types dia's - [`Slide`](./slide), [`MasterSlide`](./masterslide) en [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Itereren over elke [`Shape`](./shape) in de [`Presentation`](../../aspose.slides/presentation). Shapes zullen worden geïnterereerd in alle types dia's - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) en [`NotesSlide`](../../aspose.slides/notesslide) indien nodig. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Itereren over elke [`Slide`](./slide) in de [`Presentation`](../../aspose.slides/presentation). |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback die wordt aangeroepen voor elke [`LayoutSlide`](./layoutslide) in de [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback die wordt aangeroepen voor elke [`MasterSlide`](./masterslide) in de [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback die wordt aangeroepen voor elke [`Paragraph`](./paragraph) op de [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback die wordt aangeroepen voor elke [`Portion`](./portion) in de [`Paragraph`](./paragraph) op de [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback die wordt aangeroepen voor elke [`Shape`](./shape) in de [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback die wordt aangeroepen voor elke [`Slide`](./slide) in de [`Presentation`](../../aspose.slides/presentation). |

### Voorbeelden

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

### Zie ook

* naamruimte [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->