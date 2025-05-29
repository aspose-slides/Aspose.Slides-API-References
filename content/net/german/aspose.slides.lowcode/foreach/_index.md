---
title: ForEach
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Gruppe von Methoden dar, die zum Iterieren über verschiedene Presentation../aspose.slides/presentation-Modellobjekte gedacht sind. Diese Methoden können nützlich sein, wenn Sie das Format oder den Inhalt bestimmter Präsentationselemente ändern müssen, z.B. das Format jeder Portion ändern.
type: docs
weight: 7660
url: /de/aspose.slides.lowcode/foreach/
---

## ForEach-Klasse

Stellt eine Gruppe von Methoden dar, die zum Iterieren über verschiedene [`Presentation`](../../aspose.slides/presentation)-Modellobjekte gedacht sind. Diese Methoden können nützlich sein, wenn Sie das Format oder den Inhalt bestimmter Präsentationselemente ändern müssen, z.B. das Format jeder Portion ändern.

```csharp
public static class ForEach
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iteriert über jede [`LayoutSlide`](./layoutslide) in der [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iteriert über jede [`MasterSlide`](./masterslide) in der [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iteriert über jeden [`Paragraph`](./paragraph) in der [`Presentation`](../../aspose.slides/presentation). Formen werden in allen Arten von Folien iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iteriert über jeden [`Paragraph`](./paragraph) in der [`Presentation`](../../aspose.slides/presentation). Formen werden in allen Arten von Folien iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iteriert über jede [`Portion`](./portion) in der [`Presentation`](../../aspose.slides/presentation). Portionen werden in allen Arten von Folien iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iteriert über jede [`Portion`](./portion) in der [`Presentation`](../../aspose.slides/presentation). Portionen werden in allen Arten von Folien iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iteriert über jede [`Shape`](./shape) in der [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) ist der Basistyp für [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iteriert über jede [`Shape`](./shape) in der [`Presentation`](../../aspose.slides/presentation). Formen werden in allen Arten von Folien iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iteriert über jede [`Shape`](./shape) in der [`Presentation`](../../aspose.slides/presentation). Formen werden in allen Arten von Folien iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) falls erforderlich. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iteriert über jede [`Slide`](./slide) in der [`Presentation`](../../aspose.slides/presentation). |

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

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->