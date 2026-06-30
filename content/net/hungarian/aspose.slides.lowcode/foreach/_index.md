---
title: ForEach
second_title: Aspose.Sildes a .NET API referenciához
description: Representál egy csoport metódust, amelyet különböző Presentation../aspose.slides/presentation modellobjektumokon való iterálásra terveztek. Ezek a metódusok hasznosak lehetnek, ha iterálnod kell és módosítanod néhány Presentation elemet formázás vagy tartalom szempontjából, például minden rész formázásának megváltoztatása.
type: docs
weight: 7880
url: /hu/aspose.slides.lowcode/foreach/
---
## ForEach osztály

Képvisel egy módszercsoportot, amely különböző [`Presentation`](../../aspose.slides/presentation) modellobjektumokon való iterálásra szolgál. Ezek a módszerek hasznosak lehetnek, ha iterálnia és módosítania kell néhány Presentation elemek formázását vagy tartalmát, például minden rész formázását megváltoztatni.

```csharp
public static class ForEach
```

## Módszerek

| Név | Leírás |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterálja az egyes [`LayoutSlide`](./layoutslide) a [`Presentation`](../../aspose.slides/presentation)-ban. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterálja az egyes [`MasterSlide`](./masterslide) a [`Presentation`](../../aspose.slides/presentation)-ban. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterálja az egyes [`Paragraph`](./paragraph) a [`Presentation`](../../aspose.slides/presentation)-ban. Az alakzatok minden típusú dián iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide) és [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterálja az egyes [`Paragraph`](./paragraph) a [`Presentation`](../../aspose.slides/presentation)-ban. Az alakzatok minden típusú dián iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) és [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterálja az egyes [`Portion`](./portion) a [`Presentation`](../../aspose.slides/presentation)-ban. A részek minden típusú dián iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide) és [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterálja az egyes [`Portion`](./portion) a [`Presentation`](../../aspose.slides/presentation)-ban. A részek minden típusú dián iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) és [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterálja az egyes [`Shape`](./shape) a [`BaseSlide`](../../aspose.slides/baseslide)-ban. [`BaseSlide`](../../aspose.slides/baseslide) az alaptípus a [`Slide`](./slide), [`MasterSlide`](./masterslide) és [`LayoutSlide`](./layoutslide) számára |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterálja az egyes [`Shape`](./shape) a [`Presentation`](../../aspose.slides/presentation)-ban. Az alakzatok minden típusú dián iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide) és [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterálja az egyes [`Shape`](./shape) a [`Presentation`](../../aspose.slides/presentation)-ban. Az alakzatok minden típusú dián iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) és [`NotesSlide`](../../aspose.slides/notesslide) ha szükséges. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterálja az egyes [`Slide`](./slide) a [`Presentation`](../../aspose.slides/presentation)-ban. |

## Egyéb tagok

| Név | Leírás |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Visszahívás, amely minden [`LayoutSlide`](./layoutslide) esetén meghívásra kerül a [`Presentation`](../../aspose.slides/presentation)-ban. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Visszahívás, amely minden [`MasterSlide`](./masterslide) esetén meghívásra kerül a [`Presentation`](../../aspose.slides/presentation)-ban. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Visszahívás, amely minden [`Paragraph`](./paragraph) esetén meghívásra kerül a [`BaseSlide`](../../aspose.slides/baseslide)-on. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Visszahívás, amely minden [`Portion`](./portion) esetén meghívásra kerül a [`Paragraph`](./paragraph)-ban a [`BaseSlide`](../../aspose.slides/baseslide)-on. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Visszahívás, amely minden [`Shape`](./shape) esetén meghívásra kerül a [`Presentation`](../../aspose.slides/presentation)-ban. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Visszahívás, amely minden [`Slide`](./slide) esetén meghívásra kerül a [`Presentation`](../../aspose.slides/presentation)-ban. |

### Példák

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

### Lásd még

* névtér [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->