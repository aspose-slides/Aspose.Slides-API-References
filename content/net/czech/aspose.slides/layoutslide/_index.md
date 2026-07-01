---
title: LayoutSlide
second_title: Aspose.Sildes pro .NET API referenci
description: Reprezentuje rozvrhový snímek.
type: docs
weight: 7620
url: /cs/aspose.slides/layoutslide/
---
## LayoutSlide třída

Represents a layout slide.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Vrací pozadí snímku. Pouze pro čtení [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Vrací kolekci ovládacích prvků ActiveX na snímku. Pouze pro čtení [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Vrací vlastní data snímku. Pouze pro čtení [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Vrací kolekci kreslicích vodítek pro rozvrhový snímek. Pouze pro čtení [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Vrací pravdu, pokud existuje alespoň jeden snímek, který závisí na tomto rozvrhovém snímku. Pouze pro čtení Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Vrací správce záhlaví a zápatí rozvrhového snímku. Pouze pro čtení [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Poskytuje snadný přístup k obsaženým hyperodkazům. Pouze pro čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Vrací typ rozvržení tohoto rozvrhového snímku. Pouze pro čtení [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Vrací nebo nastavuje hlavní snímek pro rozvržení. Čtení/zápis [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Vrací nebo nastavuje název snímku. Čtení/zápis String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Vrací správce zástupných objektů rozvrhového snímku. Pouze pro čtení [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Vrací rozhraní IPresentation. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Vrací tvary snímku. Pouze pro čtení [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Určuje, zda se tvary na hlavním snímku mají zobrazovat na snímcích, nebo ne. Čtení/zápis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Vrací ID snímku. Pouze pro čtení UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Vrací objekt Transition, který obsahuje informace o tom, jak se určený snímek posouvá během prezentace. Pouze pro čtení [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Vrací správce přepisující motiv. Pouze pro čtení [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Vrací objekt časové osy animace. Pouze pro čtení [`IAnimationTimeLine`](../ianimationtimeline). |

## Metody

| Název | Popis |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Vrací efektivní motiv pro tento snímek. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Určuje, zda jsou dvě instance IBaseSlide rovny. Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu. Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nebere v úvahu jedinečné hodnoty identifikátorů, např. SlideId, a dynamický obsah, např. aktuální datum v Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Najde první výskyt tvaru se zadaným alternativním textem. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Vrací pole se všemi snímky, které závisí na tomto rozvrhovém snímku. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Spojí běhy se stejným formátováním ve všech odstavcích všech vhodných tvarů. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Spojí běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Odstraní rozvržení z prezentace. |

### Viz také

* třída [BaseSlide](../baseslide)
* rozhraní [ILayoutSlide](../ilayoutslide)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->