---
title: MasterSlide
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje slajd główny w prezentacji.
type: docs
weight: 8050
url: /pl/aspose.slides/masterslide/
---
## Klasa MasterSlide

Reprezentuje slajd główny w prezentacji.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Zwraca tło slajdu. Tylko do odczytu [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Zwraca styl tekstu głównego. Tylko do odczytu [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Zwraca własne dane slajdu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Zwraca kolekcję prowadnic rysunkowych dla slajdu głównego. Tylko do odczytu [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Zwraca true, jeśli istnieje co najmniej jeden slajd zależny od tego slajdu głównego. Tylko do odczytu Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Zwraca menedżer HeaderFooter slajdu głównego. Tylko do odczytu [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Zapewnia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Zwraca kolekcję podrzędnych slajdów układu dla tego slajdu głównego. Tylko do odczytu [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Zwraca lub ustawia nazwę slajdu głównego. Odczyt/zapis String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Zwraca styl innego tekstu. Tylko do odczytu [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Zwraca interfejs IPresentation. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Określa, czy odpowiadający slajd główny jest usuwany, gdy wszystkie slajdy po nim zostaną usunięte. Uwaga: Aspose.Slides nigdy nie usunie nieużywanego slajdu głównego samodzielnie; aby rzeczywiście usunąć nieużywane slajdy główne, wywołaj [`RemoveUnused`](../masterslidecollection/removeunused) Odczyt/zapis Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Zwraca kształty slajdu. Tylko do odczytu [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Określa, czy kształty na slajdzie głównym powinny być wyświetlane na slajdach. Dla samego slajdu głównego ta właściwość zawsze zwraca `false`. Odczyt/zapis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Zwraca identyfikator slajdu. Tylko do odczytu UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Zwraca obiekt Transition, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. Tylko do odczytu [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Zwraca menedżer motywu. Tylko do odczytu [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Zwraca obiekt osi czasu animacji. Tylko do odczytu [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Zwraca styl tekstu tytułu. Tylko do odczytu [`ITextStyle`](../itextstyle). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Tworzy nowy slajd główny oparty na bieżącym, stosując do niego zewnętrzny motyw i zastosowuje utworzony slajd główny do wszystkich zależnych slajdów. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Zwraca skuteczny motyw dla tego slajdu. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Określa, czy dwie instancje IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz zawartości dynamicznej, np. bieżącej wartości daty w zastępczym polu daty. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu głównego. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich akceptowalnych kształtach. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich akceptowalnych kształtach. |

### Zobacz również

* klasa [BaseSlide](../baseslide)
* interfejs [IMasterSlide](../imasterslide)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->