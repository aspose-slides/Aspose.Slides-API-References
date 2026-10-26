---
title: MasterSlide
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje główny slajd w prezentacji.
type: docs
weight: 8030
url: /pl/aspose.slides/masterslide/
---
## MasterSlide klasa

Reprezentuje główny slajd w prezentacji.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Zwraca tło slajdu. Tylko do odczytu [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Zwraca styl tekstu głównego. Tylko do odczytu [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Zwraca niestandardowe dane slajdu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Zwraca kolekcję przewodników rysowania dla głównego slajdu. Tylko do odczytu [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Zwraca wartość true, jeśli istnieje co najmniej jeden slajd zależny od tego głównego slajdu. Tylko do odczytu Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Zwraca menedżera HeaderFooter głównego slajdu. Tylko do odczytu [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Zapewnia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Zwraca kolekcję podrzędnych układów slajdów dla tego głównego slajdu. Tylko do odczytu [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Zwraca lub ustawia nazwę głównego slajdu. Odczyt/Zapis String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Zwraca styl innego tekstu. Tylko do odczytu [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Zwraca interfejs IPresentation. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Określa, czy odpowiadający master zostanie usunięty, gdy wszystkie slajdy po nim zostaną usunięte. Uwaga: Aspose.Slides nigdy nie usunie nieużywanego mastera samodzielnie; aby faktycznie usunąć nieużywane mastery, wywołaj [`RemoveUnused`](../masterslidecollection/removeunused). Odczyt/Zapis Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Zwraca kształty slajdu. Tylko do odczytu [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Określa, czy kształty na głównym slajdzie mają być wyświetlane na slajdach czy nie. Dla samego głównego slajdu ta właściwość zawsze zwraca `false`. Odczyt/Zapis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Zwraca identyfikator slajdu. Tylko do odczytu UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Zwraca obiekt Transition, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. Tylko do odczytu [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Zwraca menedżera motywu. Tylko do odczytu [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Zwraca obiekt osi czasu animacji. Tylko do odczytu [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Zwraca styl tekstu tytułu. Tylko do odczytu [`ITextStyle`](../itextstyle). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Tworzy nowy główny slajd na podstawie bieżącego, stosując zewnętrzny motyw i zastosowuje utworzony główny slajd do wszystkich zależnych slajdów. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Zwraca efektywny motyw dla tego slajdu. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Określa, czy dwa obiekty IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia unikalnych wartości identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w Symbolu zastępczym daty. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Zwraca tablicę ze wszystkimi slajdami zależnymi od tego głównego slajdu. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Łączy fragmenty o takim samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Łączy fragmenty o takim samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |

### Zobacz także

* klasa [BaseSlide](../baseslide)
* interfejs [IMasterSlide](../imasterslide)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->