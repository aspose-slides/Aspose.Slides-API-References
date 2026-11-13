---
title: LayoutSlide
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje rozvrhový snímek.
type: docs
weight: 7660
url: /cs/aspose.slides/layoutslide/
---
## LayoutSlide třída

Reprezentuje rozvrhový snímek.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Properties

| Název | Popis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Vrací pozadí snímku. Pouze ke čtení [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Vrací kolekci ovládacích prvků ActiveX na snímku. Pouze ke čtení [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Vrací vlastní data snímku. Pouze ke čtení [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Vrací kolekci kreslicích vodítek pro rozvrhový snímek. Pouze ke čtení [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto rozvrhovém snímku. Pouze ke čtení Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Vrací správce HeaderFooter rozvrhového snímku. Pouze ke čtení [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Poskytuje snadný přístup k obsaženým hyperodkazům. Pouze ke čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Vrací typ rozvržení tohoto rozvrhového snímku. Pouze ke čtení [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Vrací nebo nastavuje hlavní snímek pro rozvržení. Ke čtení a zápisu [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Vrací nebo nastavuje název snímku. Ke čtení a zápisu String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Vrací správce zástupných znaků rozvrhového snímku. Pouze ke čtení [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Vrací rozhraní IPresentation. Pouze ke čtení [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Vrací tvary snímku. Pouze ke čtení [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. Ke čtení a zápisu Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Vrací ID snímku. Pouze ke čtení UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Vrací objekt Transition, který obsahuje informace o tom, jak se určený snímek posouvá během prezentace. Pouze ke čtení [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Vrací správce přepisujícího motivu. Pouze ke čtení [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Vrací objekt časové osy animace. Pouze ke čtení [`IAnimationTimeLine`](../ianimationtimeline). |

## Methods

| Název | Popis |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Vrací efektivní motiv pro tento snímek. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Určuje, zda jsou dvě instance IBaseSlide rovné. Návratová hodnota je vypočtena na základě struktury snímku a statického obsahu. Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nezohledňuje jedinečné hodnoty identifikátorů, např. SlideId a dynamický obsah, např. aktuální hodnotu data v Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Najde první výskyt tvaru se zadaným alternativním textem. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Vrací pole se všemi snímky, které závisí na tomto rozvrhovém snímku. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech přijatelných tvarech. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Spojuje běhy se stejným formátováním ve všech odstavcích ve všech přijatelných tvarech. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Odstraňuje rozvržení z prezentace. |

### See Also

* třída [BaseSlide](../baseslide)
* rozhraní [ILayoutSlide](../ilayoutslide)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->