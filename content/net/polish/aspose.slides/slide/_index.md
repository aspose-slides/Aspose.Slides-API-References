---
title: Slide
second_title: Aspose.Sildes dla .NET API Reference
description: Reprezentuje slajd w prezentacji.
type: docs
weight: 9940
url: /pl/aspose.slides/slide/
---
## Klasa Slide

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Zwraca tło slajdu. Tylko do odczytu [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Zwraca niestandardowe dane slajdu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Zwraca menedżera HeaderFooter slajdu. Tylko do odczytu [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Określa, czy określony slajd jest ukryty podczas pokazu slajdów. Odczyt/zapis Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Zapewnia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Zwraca lub ustawia slajd układu dla bieżącego slajdu. Odczyt/zapis [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Zwraca lub ustawia nazwę slajdu. Odczyt/zapis String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Umożliwia dostęp do slajdu z notatkami, dodawanie i usuwanie go. Tylko do odczytu [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Zwraca interfejs IPresentation. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Zwraca kształty slajdu. Tylko do odczytu [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Określa, czy kształty na slajdzie master mają być wyświetlane na slajdach. Odczyt/zapis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Zwraca identyfikator slajdu. Tylko do odczytu UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Zwraca numer slajdu. Indeks slajdu w kolekcji [`Slides`](../presentation/slides) jest zawsze równy SlideNumber - Presentation.FirstSlideNumber. Odczyt/zapis Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Zwraca obiekt Transition, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. Tylko do odczytu [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Zwraca menedżera nadrzędnego motywu. Tylko do odczytu [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Zwraca obiekt osi czasu animacji. Tylko do odczytu [`IAnimationTimeLine`](../ianimationtimeline). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Zwraca efektywny motyw dla tego slajdu. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Określa, czy dwie instancje IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, takich jak SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w Symbolu daty. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Znajduje pierwsze wystąpienie kształtu o podanym alternatywnym tekście. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Zwraca obiekt Thumbnail Image (20% rzeczywistego rozmiaru). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Zwraca obiekt Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Zwraca obiekt obrazu tiff miniatury z określonymi parametrami. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Zwraca obiekt Thumbnail Image o podanym rozmiarze. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Zwraca obiekt Thumbnail Image o podanym rozmiarze. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Zwraca wszystkie komentarze slajdu dodane przez określonego autora. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Łączy fragmenty tekstu o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Łączy fragmenty tekstu o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [Remove](../../aspose.slides/slide/remove)() | Usuwa slajd z prezentacji. |
| [Reset](../../aspose.slides/slide/reset)() | Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp w LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Zapisuje zawartość slajdu jako plik EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Zapisuje zawartość slajdu jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Zapisuje zawartość slajdu jako plik SVG. |

### Zobacz także

* klasa [BaseSlide](../baseslide)
* interfejs [ISlide](../islide)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->