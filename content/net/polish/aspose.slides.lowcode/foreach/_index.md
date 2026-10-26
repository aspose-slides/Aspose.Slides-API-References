---
title: ForEach
second_title: Aspose.Sildes dla .NET - referencja API
description: Reprezentuje grupę metod przeznaczonych do iteracji po różnych obiektach modelu Presentation../aspose.slides/presentation. Metody te mogą być przydatne, jeśli potrzebujesz iterować i zmieniać formatowanie lub zawartość niektórych elementów Presentation, np. zmienić formatowanie każdego fragmentu.
type: docs
weight: 7900
url: /pl/aspose.slides.lowcode/foreach/
---
## ForEach klasa

Reprezentuje grupę metod przeznaczonych do iteracji po różnych [`Presentation`](../../aspose.slides/presentation) obiektach modelu. Metody te mogą być przydatne, jeśli musisz iterować i zmieniać formatowanie lub treść niektórych elementów Presentation, np. zmienić formatowanie każdego fragmentu.

```csharp
public static class ForEach
```

## Metody

| Nazwa | Opis |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iteruje każdy [`LayoutSlide`](./layoutslide) w [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iteruje każdy [`MasterSlide`](./masterslide) w [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iteruje każdy [`Paragraph`](./paragraph) w [`Presentation`](../../aspose.slides/presentation). Kształty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide) i [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iteruje każdy [`Paragraph`](./paragraph) w [`Presentation`](../../aspose.slides/presentation). Kształty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) i [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iteruje każdy [`Portion`](./portion) w [`Presentation`](../../aspose.slides/presentation). Fragmenty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide) i [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iteruje każdy [`Portion`](./portion) w [`Presentation`](../../aspose.slides/presentation). Fragmenty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) i [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iteruje każdy [`Shape`](./shape) w [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) jest typem bazowym dla [`Slide`](./slide), [`MasterSlide`](./masterslide) i [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iteruje każdy [`Shape`](./shape) w [`Presentation`](../../aspose.slides/presentation). Kształty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide) i [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iteruje każdy [`Shape`](./shape) w [`Presentation`](../../aspose.slides/presentation). Kształty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) i [`NotesSlide`](../../aspose.slides/notesslide) w razie potrzeby. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iteruje każdy [`Slide`](./slide) w [`Presentation`](../../aspose.slides/presentation). |

## Inne członkowie

| Nazwa | Opis |
| --- | --- |
| delegate [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Funkcja zwrotna, która zostanie wywołana dla każdego [`LayoutSlide`](./layoutslide) w [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Funkcja zwrotna, która zostanie wywołana dla każdego [`MasterSlide`](./masterslide) w [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Funkcja zwrotna, która zostanie wywołana dla każdego [`Paragraph`](./paragraph) na [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachPortionCallback](foreach.foreachportioncallback) | Funkcja zwrotna, która zostanie wywołana dla każdego [`Portion`](./portion) w [`Paragraph`](./paragraph) na [`BaseSlide`](../../aspose.slides/baseslide). |
| delegate [ForEachShapeCallback](foreach.foreachshapecallback) | Funkcja zwrotna, która zostanie wywołana dla każdego [`Shape`](./shape) w [`Presentation`](../../aspose.slides/presentation). |
| delegate [ForEachSlideCallback](foreach.foreachslidecallback) | Funkcja zwrotna, która zostanie wywołana dla każdego [`Slide`](./slide) w [`Presentation`](../../aspose.slides/presentation). |

### Przykłady

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

### Zobacz także

* przestrzeń nazw [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->