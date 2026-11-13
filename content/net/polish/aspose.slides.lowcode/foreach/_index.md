---
title: ForEach
second_title: Aspose.Sildes dla .NET Referencja API
description: Reprezentuje grupę metod przeznaczonych do iteracji po różnych obiektach modelu Presentation../aspose.slides/presentation. Metody te mogą być przydatne, jeśli musisz iterować i zmienić formatowanie lub zawartość niektórych elementów Presentation, np. zmienić formatowanie każdego fragmentu.
type: docs
weight: 7920
url: /pl/aspose.slides.lowcode/foreach/
---
## ForEach klasa

Reprezentuje grupę metod przeznaczonych do iteracji po różnych obiektach modelu [`Presentation`](../../aspose.slides/presentation). Metody te mogą być przydatne, jeśli musisz iterować i zmieniać formatowanie lub zawartość niektórych elementów prezentacji, np. zmienić formatowanie każdego fragmentu.

```csharp
public static class ForEach
```

## Metody

| Nazwa | Opis |
| --- | --- |
| static [LayoutSlide](../../aspose.slides.lowcode/foreach/layoutslide)(Presentation, ForEachLayoutSlideCallback) | Iteruj każdy [`LayoutSlide`](./layoutslide) w [`Presentation`](../../aspose.slides/presentation). |
| static [MasterSlide](../../aspose.slides.lowcode/foreach/masterslide)(Presentation, ForEachMasterSlideCallback) | Iteruj każdy [`MasterSlide`](./masterslide) w [`Presentation`](../../aspose.slides/presentation). |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph_1)(Presentation, ForEachParagraphCallback) | Iteruj każdy [`Paragraph`](./paragraph) w [`Presentation`](../../aspose.slides/presentation). Kształty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide) i [`LayoutSlide`](./layoutslide) |
| static [Paragraph](../../aspose.slides.lowcode/foreach/paragraph#paragraph)(Presentation, bool, ForEachParagraphCallback) | Iteruj każdy [`Paragraph`](./paragraph) w [`Presentation`](../../aspose.slides/presentation). Kształty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) i [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion_1)(Presentation, ForEachPortionCallback) | Iteruj każdy [`Portion`](./portion) w [`Presentation`](../../aspose.slides/presentation). Fragmenty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide) i [`LayoutSlide`](./layoutslide) |
| static [Portion](../../aspose.slides.lowcode/foreach/portion#portion)(Presentation, bool, ForEachPortionCallback) | Iteruj każdy [`Portion`](./portion) w [`Presentation`](../../aspose.slides/presentation). Fragmenty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) i [`NotesSlide`](../../aspose.slides/notesslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape)(BaseSlide, ForEachShapeCallback) | Iteruj każdy [`Shape`](./shape) w [`BaseSlide`](../../aspose.slides/baseslide). [`BaseSlide`](../../aspose.slides/baseslide) jest typem bazowym dla [`Slide`](./slide), [`MasterSlide`](./masterslide) i [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_2)(Presentation, ForEachShapeCallback) | Iteruj każdy [`Shape`](./shape) w [`Presentation`](../../aspose.slides/presentation). Kształty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide) i [`LayoutSlide`](./layoutslide) |
| static [Shape](../../aspose.slides.lowcode/foreach/shape#shape_1)(Presentation, bool, ForEachShapeCallback) | Iteruj każdy [`Shape`](./shape) w [`Presentation`](../../aspose.slides/presentation). Kształty będą iterowane we wszystkich typach slajdów - [`Slide`](./slide), [`MasterSlide`](./masterslide), [`LayoutSlide`](./layoutslide) i [`NotesSlide`](../../aspose.slides/notesslide) w razie potrzeby. |
| static [Slide](../../aspose.slides.lowcode/foreach/slide)(Presentation, ForEachSlideCallback) | Iteruj każdy [`Slide`](./slide) w [`Presentation`](../../aspose.slides/presentation). |

## Inne elementy

| Nazwa | Opis |
| --- | --- |
| delegat [ForEachLayoutSlideCallback](foreach.foreachlayoutslidecallback) | Wywoływane dla każdego [`LayoutSlide`](./layoutslide) w [`Presentation`](../../aspose.slides/presentation). |
| delegat [ForEachMasterSlideCallback](foreach.foreachmasterslidecallback) | Wywoływane dla każdego [`MasterSlide`](./masterslide) w [`Presentation`](../../aspose.slides/presentation). |
| delegat [ForEachParagraphCallback](foreach.foreachparagraphcallback) | Wywoływane dla każdego [`Paragraph`](./paragraph) na [`BaseSlide`](../../aspose.slides/baseslide). |
| delegat [ForEachPortionCallback](foreach.foreachportioncallback) | Wywoływane dla każdego [`Portion`](./portion) w [`Paragraph`](./paragraph) na [`BaseSlide`](../../aspose.slides/baseslide). |
| delegat [ForEachShapeCallback](foreach.foreachshapecallback) | Wywoływane dla każdego [`Shape`](./shape) w [`Presentation`](../../aspose.slides/presentation). |
| delegat [ForEachSlideCallback](foreach.foreachslidecallback) | Wywoływane dla każdego [`Slide`](./slide) w [`Presentation`](../../aspose.slides/presentation). |

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
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->