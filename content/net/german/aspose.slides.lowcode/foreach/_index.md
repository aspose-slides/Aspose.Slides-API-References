---
title: ForEach
second_title: Aspose.Sildes für .NET API Referenz
description: Repräsentiert eine Gruppe von Methoden, die dazu dienen, über verschiedene Präsentation../aspose.slides/presentation Modellobjekte zu iterieren. Diese Methoden können nützlich sein, wenn Sie einige Formatierungen oder Inhalte von Präsentationselementen iterieren und ändern müssen, z.B. die Formatierung jeder Portion ändern.
type: docs
weight: 7660
url: /de/aspose.slides.lowcode/foreach/
---

## ForEach-Klasse

Repräsentiert eine Gruppe von Methoden, die dazu dienen, über verschiedene [`Presentation`](../../aspose.slides/presentation) Modellobjekte zu iterieren. Diese Methoden können nützlich sein, wenn Sie einige Formatierungen oder Inhalte von Präsentationselementen ändern müssen, z.B. die Formatierung jeder Portion ändern.

```csharp
public static class ForEach
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Über jeder [`LayoutSlide`](./layoutslide) in der [`Presentation`](../../aspose.slides/presentation) iterieren. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Über jeder [`MasterSlide`](./masterslide) in der [`Presentation`](../../aspose.slides/presentation) iterieren. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Über jeder [`Paragraph`](./paragraph) in der [`Presentation`](../../aspose.slides/presentation) iterieren. Formen werden in allen Arten von Folien - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) iteriert. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Über jeder [`Paragraph`](./paragraph) in der [`Presentation`](../../aspose.slides/presentation) iterieren. Formen werden in allen Arten von Folien - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) iteriert. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Über jeder [`Portion`](./portion) in der [`Presentation`](../../aspose.slides/presentation) iterieren. Portionen werden in allen Arten von Folien - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) iteriert. |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Über jeder [`Portion`](./portion) in der [`Presentation`](../../aspose.slides/presentation) iterieren. Portionen werden in allen Arten von Folien - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) iteriert. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Über jeder [`Shape`](./shape) in der [`BaseSlide`](../../aspose.slides/baseslide) iterieren. [`BaseSlide`](../../aspose.slides/baseslide) ist der Basistyp für [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide). |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Über jeder [`Shape`](./shape) in der [`Presentation`](../../aspose.slides/presentation) iterieren. Formen werden in allen Arten von Folien - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) iteriert. |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Über jeder [`Shape`](./shape) in der [`Presentation`](../../aspose.slides/presentation) iterieren. Formen werden in allen Arten von Folien - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) iteriert, falls benötigt. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Über jeder [`Slide`](./slide) in der [`Presentation`](../../aspose.slides/presentation) iterieren. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) |  |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) |  |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) |  |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) |  |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) |  |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) |  |

### Beispiele

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

### Siehe auch

* Namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->