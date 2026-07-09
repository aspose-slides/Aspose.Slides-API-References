---
title: Slide
second_title: Aspose.Sildes pro .NET referenci API
description: Reprezentuje snímek v prezentaci.
type: docs
weight: 9960
url: /cs/aspose.slides/slide/
---
## Třída Slide

Reprezentuje snímek v prezentaci.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Vrací pozadí snímku. Pouze ke čtení [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Vrací kolekci ovládacích prvků ActiveX na snímku. Pouze ke čtení [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Vrací vlastní data snímku. Pouze ke čtení [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Vrací správce HeaderFooter snímku. Pouze ke čtení [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Určuje, zda je zadaný snímek skryt během prezentace. Čtení/zápis Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Umožňuje snadný přístup k obsaženým hyperodkazům. Pouze ke čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Vrací nebo nastavuje snímek rozvržení pro aktuální snímek. Čtení/zápis [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Vrací nebo nastavuje název snímku. Čtení/zápis String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Umožňuje přístup k snímku poznámek, jeho přidání a odebrání. Pouze ke čtení [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Vrací rozhraní IPresentation. Pouze ke čtení [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Vrací tvary snímku. Pouze ke čtení [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. Čtení/zápis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Vrací ID snímku. Pouze ke čtení UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Vrací číslo snímku. Index snímku v kolekci [`Slides`](../presentation/slides) je vždy roven SlideNumber - Presentation.FirstSlideNumber. Čtení/zápis Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Vrací objekt Transition, který obsahuje informace o tom, jak se zadaný snímek posouvá během prezentace. Pouze ke čtení [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Vrací správce přepisujícího motivu. Pouze ke čtení [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Vrací objekt časové osy animace. Pouze ke čtení [`IAnimationTimeLine`](../ianimationtimeline). |

## Metody

| Název | Popis |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Vrací efektivní motiv pro tento snímek. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Určuje, zda jsou dvě instance IBaseSlide stejné. Návratová hodnota je vypočtena na základě struktury snímku a statického obsahu. Dva snímky jsou stejné, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. stejné. Porovnání nebere v úvahu jedinečné hodnoty identifikátorů, např. SlideId a dynamický obsah, např. aktuální datum v zástupci Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Najde první výskyt tvaru se zadaným alternativním textem. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Vrací objekt Thumbnail Image (20 % skutečné velikosti). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Vrací objekt Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Vrací objekt miniatury TIFF obrázku s určenými parametry. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Vrací objekt Thumbnail Image s určenou velikostí. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Vrací objekt Thumbnail Image s vlastním měřítkem. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Vrací objekt Thumbnail Image s určenou velikostí. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Vrací objekt Thumbnail Image s vlastním měřítkem. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Vrací všechny komentáře ke snímku přidané konkrétním autorem. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech. |
| [Remove](../../aspose.slides/slide/remove)() | Odstraňuje snímek z prezentace. |
| [Reset](../../aspose.slides/slide/reset)() | Resetuje pozici, velikost a formátování každého tvaru, který má prototyp na LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Ukládá obsah snímku jako soubor EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Ukládá obsah snímku jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Ukládá obsah snímku jako soubor SVG. |

### Viz také

* třída [BaseSlide](../baseslide)
* rozhraní [ISlide](../islide)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->