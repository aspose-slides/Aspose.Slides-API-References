---
title: ForEach
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um grupo de métodos destinados a iterar sobre diferentes objetos de modelo Presentation../aspose.slides/presentation. Esses métodos podem ser úteis se você precisar iterar e alterar a formatação ou o conteúdo de alguns elementos da Presentation, por exemplo, alterar a formatação de cada porção.
type: docs
weight: 7920
url: /pt/aspose.slides.lowcode/foreach/
---
## ForEach classe

Representa um grupo de métodos destinados a iterar sobre diferentes objetos de modelo [`Presentation`](../../aspose.slides/presentation). Esses métodos podem ser úteis se você precisar iterar e alterar a formatação ou o conteúdo de alguns elementos da Presentation, por exemplo, alterar a formatação de cada porção.

```csharp
public static class ForEach
```

## Métodos

| Name | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Itera cada [`LayoutSlide`](./layoutslide) no [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Itera cada [`MasterSlide`](./masterslide) no [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Itera cada [`Paragraph`](./paragraph) no [`Presentation`](../../aspose.slides/presentation). As formas serão iteradas em todos os tipos de slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) e [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Itera cada [`Paragraph`](./paragraph) no [`Presentation`](../../aspose.slides/presentation). As formas serão iteradas em todos os tipos de slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) e [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Itera cada [`Portion`](./portion) no [`Presentation`](../../aspose.slides/presentation). As porções serão iteradas em todos os tipos de slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) e [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Itera cada [`Portion`](./portion) no [`Presentation`](../../aspose.slides/presentation). As porções serão iteradas em todos os tipos de slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) e [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Itera cada [`Shape`](./shape) no [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) é o tipo base para [`Slide`](./slide), [`MasterSlide`](./masterslide) e [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Itera cada [`Shape`](./shape) no [`Presentation`](../../aspose.slides/presentation). As formas serão iteradas em todos os tipos de slides - [`Slide`](./slide), [`MasterSlide`](./masterslide) e [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Itera cada [`Shape`](./shape) no [`Presentation`](../../aspose.slides/presentation). As formas serão iteradas em todos os tipos de slides - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) e [`NotesSlide`](../../aspose.slides/notesslide) se necessário. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Itera cada [`Slide`](./slide) no [`Presentation`](../../aspose.slides/presentation). |

## Outros Membros

| Name | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Callback que será invocado para cada [`LayoutSlide`](./layoutslide) no [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Callback que será invocado para cada [`MasterSlide`](./masterslide) no [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Callback que será invocado para cada [`Paragraph`](./paragraph) no [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Callback que será invocado para cada [`Portion`](./portion) em [`Paragraph`](./paragraph) no [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Callback que será invocado para cada [`Shape`](./shape) no [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Callback que será invocado para cada [`Slide`](./slide) no [`Presentation`](../../aspose.slides/presentation). |

### Exemplos

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

### Veja Também

* espaço de nomes [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->