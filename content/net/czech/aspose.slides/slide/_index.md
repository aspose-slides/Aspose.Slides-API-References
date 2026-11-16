---
title: Slide
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Reprezentuje snímek v prezentaci.
type: docs
weight: 9980
url: /cs/aspose.slides/slide/
---
## Třída Slide

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Vrací pozadí snímku. Pouze pro čtení [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Vrací kolekci ovládacích prvků ActiveX na snímku. Pouze pro čtení [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Vrací vlastní data snímku. Pouze pro čtení [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Vrací správce záhlaví a zápatí snímku. Pouze pro čtení [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Určuje, zda je zadaný snímek skryt během prezentace. Čtení/zápis Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Poskytuje snadný přístup k obsaženým hyperodkazům. Pouze pro čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Vrací nebo nastavuje rozložení snímku pro aktuální snímek. Čtení/zápis [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Vrací nebo nastavuje název snímku. Čtení/zápis String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Umožňuje přístup k poznámkovému snímku, přidat jej a odebrat. Pouze pro čtení [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Vrací rozhraní IPresentation. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Vrací tvary snímku. Pouze pro čtení [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Určuje, zda mají být tvary v hlavním snímku zobrazeny v ostatních snímcích nebo ne. Čtení/zápis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Vrací ID snímku. Pouze pro čtení UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Vrací číslo snímku. Index snímku ve sbírce [`Slides`](../presentation/slides) je vždy roven SlideNumber - Presentation.FirstSlideNumber. Čtení/zápis Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Vrací objekt Transition, který obsahuje informace o tom, jak se určený snímek během prezentace posouvá. Pouze pro čtení [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Vrací správce přebíjejícího motivu. Pouze pro čtení [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Vrací objekt časové osy animace. Pouze pro čtení [`IAnimationTimeLine`](../ianimationtimeline). |

## Metody

| Název | Popis |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Vrací efektivní motiv pro tento snímek. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Určuje, zda jsou dvě instance IBaseSlide stejné. Návratová hodnota se vypočítá na základě struktury snímku a statického obsahu. Dva snímky jsou stejné, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. stejné. Porovnání nebere v úvahu jedinečné hodnoty identifikátorů, např. SlideId a dynamický obsah, např. aktuální hodnotu data v Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Vyhledá první výskyt tvaru s určeným alternativním textem. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Vrací objekt Thumbnail Image (20 % skutečné velikosti). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Vrací objekt Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Vrací objekt thumbnail TIFF obrázku s určenými parametry. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Vrací objekt Thumbnail Image s určenou velikostí. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Vrací objekt Thumbnail Image s vlastním měřítkem. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Vrací objekt Thumbnail Image s určenou velikostí. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Vrací objekt Thumbnail Image s vlastním měřítkem. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Vrací všechny komentáře snímku přidané konkrétním autorem. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech. |
| [Remove](../../aspose.slides/slide/remove)() | Odstraní snímek z prezentace. |
| [Reset](../../aspose.slides/slide/reset)() | Resetuje pozici, velikost a formátování každého tvaru, který má prototyp na LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Uloží obsah snímku jako soubor EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Uloží obsah snímku jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Uloží obsah snímku jako soubor SVG. |

### Viz také

* třída [BaseSlide](../baseslide)
* rozhraní [ISlide](../islide)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->