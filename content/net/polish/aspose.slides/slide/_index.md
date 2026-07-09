---
title: Slide
second_title: Aspose.Sildes dla .NET API Reference
description: Reprezentuje slajd w prezentacji.
type: docs
weight: 9960
url: /pl/aspose.slides/slide/
---
## Klasa Slide

Reprezentuje slajd w prezentacji.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Zwraca tło slajdu. Tylko do odczytu [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Zwraca niestandardowe dane slajdu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Zwraca menedżera nagłówka i stopki slajdu. Tylko do odczytu [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Określa, czy podany slajd jest ukryty podczas pokazu slajdów. Odczyt/zapis Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Zapewnia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Zwraca lub ustawia slajd układu dla bieżącego slajdu. Odczyt/zapis [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Zwraca lub ustawia nazwę slajdu. Odczyt/zapis String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Umożliwia dostęp do slajdu notatek, jego dodawanie i usuwanie. Tylko do odczytu [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Zwraca interfejs IPresentation. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Zwraca kształty slajdu. Tylko do odczytu [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach. Odczyt/zapis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Zwraca identyfikator slajdu. Tylko do odczytu UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Zwraca numer slajdu. Indeks slajdu w kolekcji [`Slides`](../presentation/slides) jest zawsze równy SlideNumber - Presentation.FirstSlideNumber. Odczyt/zapis Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Zwraca obiekt Transition zawierający informacje o tym, jak podany slajd przechodzi podczas pokazu slajdów. Tylko do odczytu [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Zwraca menedżera nadpisującego motywu. Tylko do odczytu [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Zwraca obiekt osi czasu animacji. Tylko do odczytu [`IAnimationTimeLine`](../ianimationtimeline). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Zwraca efektywny motyw dla tego slajdu. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Określa, czy dwie instancje IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej treści. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są identyczne. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz treści dynamicznych, np. bieżącej wartości daty w symbolu zastępczym Daty. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Zwraca obiekt Thumbnail Image (20% rzeczywistego rozmiaru). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Zwraca obiekt Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Zwraca obiekt obrazu tiff Thumbnail z podanymi parametrami. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Zwraca obiekt Thumbnail Image o określonym rozmiarze. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Zwraca obiekt Thumbnail Image o określonym rozmiarze. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Zwraca wszystkie komentarze slajdu dodane przez określonego autora. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Łączy segmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Łączy segmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [Remove](../../aspose.slides/slide/remove)() | Usuwa slajd z prezentacji. |
| [Reset](../../aspose.slides/slide/reset)() | Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Zapisuje zawartość slajdu jako plik EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Zapisuje zawartość slajdu jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Zapisuje zawartość slajdu jako plik SVG. |

### Zobacz także

* klasa [BaseSlide](../baseslide)
* interfejs [ISlide](../islide)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->