---
title: ForEach
second_title: Référence API Aspose.Sildes pour .NET
description: Représente un groupe de méthodes destinées à itérer sur différents objets modèle Presentation../aspose.slides/presentation. Ces méthodes peuvent être utiles si vous devez itérer et modifier le formatage ou le contenu de certains éléments Presentation, par exemple modifier le formatage de chaque portion.
type: docs
weight: 7920
url: /fr/aspose.slides.lowcode/foreach/
---
## ForEach classe

Représente un groupe de méthodes destinées à itérer sur différents objets modèle [`Presentation`](../../aspose.slides/presentation). Ces méthodes peuvent être utiles si vous devez itérer et modifier le formatage ou le contenu de certains éléments de Presentation, par ex. modifier le formatage de chaque portion.

```csharp
public static class ForEach
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Itère chaque [`LayoutSlide`](./layoutslide) dans le [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Itère chaque [`MasterSlide`](./masterslide) dans le [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Itère chaque [`Paragraph`](./paragraph) dans le [`Presentation`](../../aspose.slides/presentation). Les formes seront parcourues dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide) et [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Itère chaque [`Paragraph`](./paragraph) dans le [`Presentation`](../../aspose.slides/presentation). Les formes seront parcourues dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) et [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Itère chaque [`Portion`](./portion) dans le [`Presentation`](../../aspose.slides/presentation). Les portions seront parcourues dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide) et [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Itère chaque [`Portion`](./portion) dans le [`Presentation`](../../aspose.slides/presentation). Les portions seront parcourues dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) et [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Itère chaque [`Shape`](./shape) dans le [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) est le type de base pour [`Slide`](./slide), [`MasterSlide`](./masterslide) et [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Itère chaque [`Shape`](./shape) dans le [`Presentation`](../../aspose.slides/presentation). Les formes seront parcourues dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide) et [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Itère chaque [`Shape`](./shape) dans le [`Presentation`](../../aspose.slides/presentation). Les formes seront parcourues dans tous les types de diapositives - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) et [`NotesSlide`](../../aspose.slides/notesslide) si nécessaire. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Itère chaque [`Slide`](./slide) dans le [`Presentation`](../../aspose.slides/presentation). |

## Autres membres

| Nom | Description |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Rappel qui sera invoqué pour chaque [`LayoutSlide`](./layoutslide) dans le [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Rappel qui sera invoqué pour chaque [`MasterSlide`](./masterslide) dans le [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Rappel qui sera invoqué pour chaque [`Paragraph`](./paragraph) sur le [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Rappel qui sera invoqué pour chaque [`Portion`](./portion) dans le [`Paragraph`](./paragraph) sur le [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Rappel qui sera invoqué pour chaque [`Shape`](./shape) dans le [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Rappel qui sera invoqué pour chaque [`Slide`](./slide) dans le [`Presentation`](../../aspose.slides/presentation). |

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

### Voir aussi

* espace de noms [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->