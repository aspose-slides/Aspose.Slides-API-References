---
title: LayoutSlide
second_title: Aspose.Sildes dla .NET - dokumentacja API
description: Reprezentuje slajd układu.
type: docs
weight: 7620
url: /pl/aspose.slides/layoutslide/
---
## LayoutSlide klasa

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Zwraca tło slajdu. Tylko do odczytu [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Zwraca niestandardowe dane slajdu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Zwraca kolekcję przewodników rysowania dla slajdu układu. Tylko do odczytu [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Zwraca true, jeśli istnieje co najmniej jeden slajd zależny od tego slajdu układu. Tylko do odczytu Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Zwraca menedżer HeaderFooter slajdu układu. Tylko do odczytu [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Umożliwia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Zwraca typ układu tego slajdu układu. Tylko do odczytu [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Zwraca lub ustawia slajd główny dla układu. Odczyt/zapis [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Zwraca lub ustawia nazwę slajdu. Odczyt/zapis String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Zwraca menedżer placeholderów slajdu układu. Tylko do odczytu [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Zwraca interfejs IPresentation. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Zwraca kształty slajdu. Tylko do odczytu [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Określa, czy kształty na slajdzie głównym powinny być wyświetlane na slajdach. Odczyt/zapis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Zwraca identyfikator slajdu. Tylko do odczytu UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Zwraca obiekt Transition, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. Tylko do odczytu [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Zwraca menedżer nadpisującego motywu. Tylko do odczytu [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Zwraca obiekt osi czasu animacji. Tylko do odczytu [`IAnimationTimeLine`](../ianimationtimeline). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Zwraca efektywny motyw dla tego slajdu. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Określa, czy dwa wystąpienia IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itd. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz treści dynamicznej, np. bieżącej wartości daty w placeholderze Date. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Znajduje pierwsze wystąpienie kształtu o określonym alternatywnym tekście. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu układu. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Usuwa układ z prezentacji. |

### Zobacz także

* klasa [BaseSlide](../baseslide)
* interfejs [ILayoutSlide](../ilayoutslide)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->