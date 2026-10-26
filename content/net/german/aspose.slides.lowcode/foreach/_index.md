---
title: ForEach
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, über verschiedene Presentation../aspose.slides/presentation Modellobjekte zu iterieren. Diese Methoden können nützlich sein, wenn Sie über Presentation-Elemente iterieren und deren Formatierung oder Inhalt ändern müssen, z. B. die Formatierung jedes Abschnitts ändern.
type: docs
weight: 7900
url: /de/aspose.slides.lowcode/foreach/
---
## ForEach Klasse

Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, über verschiedene [`Presentation`](../../aspose.slides/presentation) Modellobjekte zu iterieren. Diese Methoden können nützlich sein, wenn Sie die Formatierung oder den Inhalt von Elementen einer Presentation ändern müssen, z. B. die Formatierung jedes Abschnitts ändern.

```csharp
public static class ForEach
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterieren Sie jedes [`LayoutSlide`](./layoutslide) im [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterieren Sie jedes [`MasterSlide`](./masterslide) im [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterieren Sie jedes [`Paragraph`](./paragraph) im [`Presentation`](../../aspose.slides/presentation). Formen werden in allen Folientypen iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterieren Sie jedes [`Paragraph`](./paragraph) im [`Presentation`](../../aspose.slides/presentation). Formen werden in allen Folientypen iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterieren Sie jedes [`Portion`](./portion) im [`Presentation`](../../aspose.slides/presentation). Abschnitte werden in allen Folientypen iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterieren Sie jedes [`Portion`](./portion) im [`Presentation`](../../aspose.slides/presentation). Abschnitte werden in allen Folientypen iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterieren Sie jedes [`Shape`](./shape) im [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) ist der Basistyp für [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterieren Sie jedes [`Shape`](./shape) im [`Presentation`](../../aspose.slides/presentation). Formen werden in allen Folientypen iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide) und [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterieren Sie jedes [`Shape`](./shape) im [`Presentation`](../../aspose.slides/presentation). Formen werden in allen Folientypen iteriert - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) und [`NotesSlide`](../../aspose.slides/notesslide) falls nötig. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterieren Sie jedes [`Slide`](./slide) im [`Presentation`](../../aspose.slides/presentation). |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback, der für jedes [`LayoutSlide`](./layoutslide) im [`Presentation`](../../aspose.slides/presentation) aufgerufen wird. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback, der für jedes [`MasterSlide`](./masterslide) im [`Presentation`](../../aspose.slides/presentation) aufgerufen wird. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback, der für jedes [`Paragraph`](./paragraph) auf dem [`BaseSlide`](../../aspose.slides/baseslide) aufgerufen wird. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback, der für jedes [`Portion`](./portion) im [`Paragraph`](./paragraph) auf dem [`BaseSlide`](../../aspose.slides/baseslide) aufgerufen wird. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback, der für jedes [`Shape`](./shape) im [`Presentation`](../../aspose.slides/presentation) aufgerufen wird. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback, der für jedes [`Slide`](./slide) im [`Presentation`](../../aspose.slides/presentation) aufgerufen wird. |

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

* Namensraum [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->