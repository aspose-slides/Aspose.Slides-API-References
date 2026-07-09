---
title: LayoutSlide
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje snímek rozvržení.
type: docs
weight: 7640
url: /cs/aspose.slides/layoutslide/
---
## LayoutSlide třída

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Vrací pozadí snímku. Pouze ke čtení [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Vrací kolekci ActiveX ovládacích prvků na snímku. Pouze ke čtení [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Vrací vlastní data snímku. Pouze ke čtení [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Vrací kolekci kreslicích vodítek pro snímek rozvržení. Pouze ke čtení [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto snímku rozvržení. Pouze ke čtení Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Vrací správce HeaderFooter snímku rozvržení. Pouze ke čtení [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Poskytuje snadný přístup k obsaženým hyperodkazům. Pouze ke čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Vrací typ rozvržení tohoto snímku rozvržení. Pouze ke čtení [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Vrací nebo nastavuje hlavní snímek pro rozvržení. Čtení i zápis [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Vrací nebo nastavuje název snímku. Čtení i zápis String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Vrací správce zástupných objektů snímku rozvržení. Pouze ke čtení [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Vrací rozhraní IPresentation. Pouze ke čtení [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Vrací tvary snímku. Pouze ke čtení [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Určuje, zda se tvary na hlavním snímku mají zobrazovat na snímcích nebo ne. Čtení i zápis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Vrací ID snímku. Pouze ke čtení UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Vrací objekt Transition, který obsahuje informace o tom, jak se určený snímek postupuje během prezentace. Pouze ke čtní [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Vrací správce přepisujícího motivu. Pouze ke čtení [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Vrací objekt časové osy animace. Pouze ke čtení [`IAnimationTimeLine`](../ianimationtimeline). |

## Metody

| Název | Popis |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Vrací efektivní motiv pro tento snímek. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Určuje, zda jsou dva instance IBaseSlide rovny. Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu. Dva snímky jsou rovny, pokud jsou rovny všechny tvary, styly, texty, animace a další nastavení atd. Porovnání nebere v úvahu jedinečné identifikátory, např. SlideId, a dynamický obsah, např. aktuální hodnotu data v Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Najde první výskyt tvary s určeným alternativním textem. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Vrací pole se všemi snímky, které závisí na tomto snímku rozvržení. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Odstraňuje rozvržení z prezentace. |

### Viz také

* třída [BaseSlide](../baseslide)
* rozhraní [ILayoutSlide](../ilayoutslide)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->