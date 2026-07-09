---
title: ForEach
second_title: Aspose.Sildes pro .NET referenční příručka API
description: Zastupuje skupinu metod určených k iteraci přes různé modelové objekty Presentation../aspose.slides/presentation. Tyto metody mohou být užitečné, pokud potřebujete iterovat a měnit formátování nebo obsah některých prvků Presentation, např. změnit formátování každé části.
type: docs
weight: 7900
url: /cs/aspose.slides.lowcode/foreach/
---
## Třída ForEach

Representuje skupinu metod určených k iteraci přes různé [`Presentation`](../../aspose.slides/presentation) modelové objekty. Tyto metody mohou být užitečné, pokud potřebujete iterovat a měnit formátování nebo obsah některých prvků Presentation, např. změnit formátování každé části.

```csharp
public static class ForEach
```

## Metody

| Název | Popis |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterovat každý [`LayoutSlide`](./layoutslide) v [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterovat každý [`MasterSlide`](./masterslide) v [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterovat každý [`Paragraph`](./paragraph) v [`Presentation`](../../aspose.slides/presentation). Tvary budou iterovány ve všech typech snímků - [`Slide`](./slide), [`MasterSlide`](./masterslide) a [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterovat každý [`Paragraph`](./paragraph) v [`Presentation`](../../aspose.slides/presentation). Tvary budou iterovány ve všech typech snímků - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) a [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterovat každý [`Portion`](./portion) v [`Presentation`](../../aspose.slides/presentation). Části budou iterovány ve všech typech snímků - [`Slide`](./slide), [`MasterSlide`](./masterslide) a [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterovat každý [`Portion`](./portion) v [`Presentation`](../../aspose.slides/presentation). Části budou iterovány ve všech typech snímků - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) a [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterovat každý [`Shape`](./shape) v [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) je základní typ pro [`Slide`](./slide), [`MasterSlide`](./masterslide) a [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterovat každý [`Shape`](./shape) v [`Presentation`](../../aspose.slides/presentation). Tvary budou iterovány ve všech typech snímků - [`Slide`](./slide), [`MasterSlide`](./masterslide) a [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterovat každý [`Shape`](./shape) v [`Presentation`](../../aspose.slides/presentation). Tvary budou iterovány ve všech typech snímků - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) a [`NotesSlide`](../../aspose.slides/notesslide) podle potřeby. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterovat každý [`Slide`](./slide) v [`Presentation`](../../aspose.slides/presentation). |

## Ostatní členové

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
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->