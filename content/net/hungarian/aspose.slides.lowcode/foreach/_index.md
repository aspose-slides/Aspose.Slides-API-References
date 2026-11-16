---
title: ForEach
second_title: Aspose.Sildes .NET API referenciája
description: Csoportot képvisel a különböző Presentation../aspose.slides/presentation modell objektumokhoz szánt metódusok. Ezek a metódusok hasznosak lehetnek, ha iterálnod kell és módosítanod a Presentation elemek formázását vagy tartalmát, például minden részlet formázását.
type: docs
weight: 7920
url: /hu/aspose.slides.lowcode/foreach/
---
## ForEach osztály

Egy csoport metódust képvisel, amely a különböző [`Presentation`](../../aspose.slides/presentation) modell objektumokon való iterálásra szolgál. Ezek a metódusok hasznosak lehetnek, ha iterálnod kell és módosítanod kell a Presentation elemek formázását vagy tartalmát, például minden részlet formázását módosítani.

```csharp
public static class ForEach
```

## Metódusok

| Név | Leírás |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iterálja az összes [`LayoutSlide`](./layoutslide)-t a [`Presentation`](../../aspose.slides/presentation)-ben. |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iterálja az összes [`MasterSlide`](./masterslide)-t a [`Presentation`](../../aspose.slides/presentation)-ben. |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iterálja az összes [`Paragraph`](./paragraph)-t a [`Presentation`](../../aspose.slides/presentation)-ben. A formák minden diatípusban iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide) és [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iterálja az összes [`Paragraph`](./paragraph)-t a [`Presentation`](../../aspose.slides/presentation)-ben. A formák minden diatípusban iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) és [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iterálja az összes [`Portion`](./portion)-t a [`Presentation`](../../aspose.slides/presentation)-ben. A részek minden diatípusban iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide) és [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iterálja az összes [`Portion`](./portion)-t a [`Presentation`](../../aspose.slides/presentation)-ben. A részek minden diatípusban iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) és [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iterálja az összes [`Shape`](./shape)-t a [`BaseSlide`](../../aspose.slides/baseslide)-ben. [`BaseSlide`](../../aspose.slides/baseslide) az alap típusa a [`Slide`](./slide), [`MasterSlide`](./masterslide) és [`LayoutSlide`](./layoutslide) számára |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iterálja az összes [`Shape`](./shape)-t a [`Presentation`](../../aspose.slides/presentation)-ben. A formák minden diatípusban iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide) és [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iterálja az összes [`Shape`](./shape)-t a [`Presentation`](../../aspose.slides/presentation)-ben. A formák minden diatípusban iterálva lesznek – [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) és [`NotesSlide`](../../aspose.slides/notesslide) ha szükséges. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iterálja az összes [`Slide`](./slide)-t a [`Presentation`](../../aspose.slides/presentation)-ben. |

## Egyéb tagok

| Név | Leírás |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Visszahívás, amely minden [`LayoutSlide`](./layoutslide)-nél a(z) [`Presentation`](../../aspose.slides/presentation)-ben meghívásra kerül. |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Visszahívás, amely minden [`MasterSlide`](./masterslide)-nél a(z) [`Presentation`](../../aspose.slides/presentation)-ben meghívásra kerül. |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Visszahívás, amely minden [`Paragraph`](./paragraph)-nél a(z) [`BaseSlide`](../../aspose.slides/baseslide)-on meghívásra kerül. |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Visszahívás, amely minden [`Portion`](./portion)-nél a(z) [`Paragraph`](./paragraph)-ban a(z) [`BaseSlide`](../../aspose.slides/baseslide)-on meghívásra kerül. |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Visszahívás, amely minden [`Shape`](./shape)-nél a(z) [`Presentation`](../../aspose.slides/presentation)-ban meghívásra kerül. |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Visszahívás, amely minden [`Slide`](./slide)-nél a(z) [`Presentation`](../../aspose.slides/presentation)-ban meghívásra kerül. |

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