---
title: ForEach
second_title: Aspose.Sildes per il riferimento API .NET
description: Rappresenta un gruppo di metodi destinati a iterare su diversi oggetti modello Presentation../aspose.slides/presentation. Questi metodi possono essere utili se è necessario iterare e modificare la formattazione o il contenuto di alcuni elementi di Presentation, ad esempio modificare la formattazione di ogni porzione.
type: docs
weight: 7900
url: /it/aspose.slides.lowcode/foreach/
---
## ForEach classe

Rappresenta un gruppo di metodi destinati a iterare su diversi oggetti modello [`Presentation`](../../aspose.slides/presentation). Questi metodi possono essere utili se è necessario iterare e modificare la formattazione o il contenuto di alcuni elementi di Presentation, ad esempio modificare la formattazione di ogni porzione.

```csharp
public static class ForEach
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Itera ogni [`LayoutSlide`](./layoutslide) nel [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Itera ogni [`MasterSlide`](./masterslide) nel [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Itera ogni [`Paragraph`](./paragraph) nel [`Presentation`](../../aspose.slides/presentation). Le forme verranno iterate in tutti i tipi di diapositive - [`Slide`](./slide), [`MasterSlide`](./masterslide) e [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Itera ogni [`Paragraph`](./paragraph) nel [`Presentation`](../../aspose.slides/presentation). Le forme verranno iterate in tutti i tipi di diapositive - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) e [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Itera ogni [`Portion`](./portion) nel [`Presentation`](../../aspose.slides/presentation). Le porzioni verranno iterate in tutti i tipi di diapositive - [`Slide`](./slide), [`MasterSlide`](./masterslide) e [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Itera ogni [`Portion`](./portion) nel [`Presentation`](../../aspose.slides/presentation). Le porzioni verranno iterate in tutti i tipi di diapositive - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) e [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Itera ogni [`Shape`](./shape) nel [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) è il tipo base per [`Slide`](./slide), [`MasterSlide`](./masterslide) e [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Itera ogni [`Shape`](./shape) nel [`Presentation`](../../aspose.slides/presentation). Le forme verranno iterate in tutti i tipi di diapositive - [`Slide`](./slide), [`MasterSlide`](./masterslide) e [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Itera ogni [`Shape`](./shape) nel [`Presentation`](../../aspose.slides/presentation). Le forme verranno iterate in tutti i tipi di diapositive - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) e [`NotesSlide`](../../aspose.slides/notesslide) se necessario. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Itera ogni [`Slide`](./slide) nel [`Presentation`](../../aspose.slides/presentation). |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback che verrà invocato per ogni [`LayoutSlide`](./layoutslide) nel [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback che verrà invocato per ogni [`MasterSlide`](./masterslide) nel [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback che verrà invocato per ogni [`Paragraph`](./paragraph) sul [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback che verrà invocato per ogni [`Portion`](./portion) nel [`Paragraph`](./paragraph) sul [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback che verrà invocato per ogni [`Shape`](./shape) nel [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback che verrà invocato per ogni [`Slide`](./slide) nel [`Presentation`](../../aspose.slides/presentation). |

### Esempi

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

### Vedi anche

* spazio dei nomi [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->