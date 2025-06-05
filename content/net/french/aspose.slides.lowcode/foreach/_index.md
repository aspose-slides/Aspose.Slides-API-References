---
title: ForEach
second_title: Référence API Aspose.Slides pour .NET
description: Représente un groupe de méthodes destinées à itérer sur différents objets du modèle Presentationaspose.slides/aspose.slides/presentation. Ces méthodes peuvent être utiles si vous devez itérer et changer le formatage ou le contenu de certains éléments de la présentation, par exemple changer le formatage de chaque portion.
type: docs
weight: 7660
url: /fr/aspose.slides.lowcode/foreach/
---

## Classe ForEach

Représente un groupe de méthodes destinées à itérer sur différents objets du modèle [`Presentation`](../../aspose.slides/presentation). Ces méthodes peuvent être utiles si vous devez itérer et changer le formatage ou le contenu de certains éléments de la présentation, par exemple changer le formatage de chaque portion.

```csharp
public static class ForEach
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Itérer chaque [`LayoutSlide`](./layoutslide) dans la [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Itérer chaque [`MasterSlide`](./masterslide) dans la [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Itérer chaque [`Paragraph`](./paragraph) dans la [`Presentation`](../../aspose.slides/presentation). Les formes seront itérées dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide) et [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Itérer chaque [`Paragraph`](./paragraph) dans la [`Presentation`](../../aspose.slides/presentation). Les formes seront itérées dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) et [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Itérer chaque [`Portion`](./portion) dans la [`Presentation`](../../aspose.slides/presentation). Les portions seront itérées dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide) et [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Itérer chaque [`Portion`](./portion) dans la [`Presentation`](../../aspose.slides/presentation). Les portions seront itérées dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) et [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Itérer chaque [`Shape`](./shape) dans la [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) est le type de base pour [`Slide`](./slide), [`MasterSlide`](./masterslide) et [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Itérer chaque [`Shape`](./shape) dans la [`Presentation`](../../aspose.slides/presentation). Les formes seront itérées dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide) et [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Itérer chaque [`Shape`](./shape) dans la [`Presentation`](../../aspose.slides/presentation). Les formes seront itérées dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) et [`NotesSlide`](../../aspose.slides/notesslide) si nécessaire. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Itérer chaque [`Slide`](./slide) dans la [`Presentation`](../../aspose.slides/presentation). |

## Autres Membres

| Nom | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) |  |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) |  |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) |  |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) |  |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) |  |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) |  |

### Exemples

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

### Voir Aussi

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->