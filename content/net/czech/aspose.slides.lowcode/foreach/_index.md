---
title: ForEach
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje skupinu metod určených k iteraci přes různé objekty modelu Presentation../aspose.slides/presentation. Tyto metody mohou být užitečné, pokud potřebujete iterovat a měnit formátování nebo obsah některých prvků Presentation, např. změnit formátování každé části.
type: docs
weight: 7880
url: /cs/aspose.slides.lowcode/foreach/
---
## ForEach třída

Represents a group of methods intended to iterate over different [`Presentation`](../../aspose.slides/presentation) model objects. These methods can be useful if you need to iterate and change some Presentation' elements formatting or content, např. change each portion formatting.

```csharp
public static class ForEach
```

## Metody

| Název | Popis |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterujte každou [`LayoutSlide`](./layoutslide) v [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterujte každou [`MasterSlide`](./masterslide) v [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterujte každou [`Paragraph`](./paragraph) v [`Presentation`](../../aspose.slides/presentation). Shapes will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) and [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterujte každou [`Paragraph`](./paragraph) v [`Presentation`](../../aspose.slides/presentation). Shapes will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) and [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterujte každou [`Portion`](./portion) v [`Presentation`](../../aspose.slides/presentation). Portions will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) and [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterujte každou [`Portion`](./portion) v [`Presentation`](../../aspose.slides/presentation). Portions will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) and [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterujte každou [`Shape`](./shape) v [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) is the base type for [`Slide`](./slide), [`MasterSlide`](./masterslide) and [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterujte každou [`Shape`](./shape) v [`Presentation`](../../aspose.slides/presentation). Shapes will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) and [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterujte každou [`Shape`](./shape) v [`Presentation`](../../aspose.slides/presentation). Shapes will be iterated in all type of slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) and [`NotesSlide`](../../aspose.slides/notesslide) if needed. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterujte každou [`Slide`](./slide) v [`Presentation`](../../aspose.slides/presentation). |

## Další členové

| Název | Popis |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Zpětné volání, které bude vyvoláno pro každého [`LayoutSlide`](./layoutslide) v [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Zpětné volání, které bude vyvoláno pro každého [`MasterSlide`](./masterslide) v [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Zpětné volání, které bude vyvoláno pro každého [`Paragraph`](./paragraph) na [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Zpětné volání, které bude vyvoláno pro každého [`Portion`](./portion) v [`Paragraph`](./paragraph) na [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Zpětné volání, které bude vyvoláno pro každého [`Shape`](./shape) v [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Zpětné volání, které bude vyvoláno pro každého [`Slide`](./slide) v [`Presentation`](../../aspose.slides/presentation). |

### Příklady

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

### Viz také

* jmenný prostor [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->