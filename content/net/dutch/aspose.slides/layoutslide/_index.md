---
title: LayoutSlide
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een layoutdia voor.
type: docs
weight: 7640
url: /nl/aspose.slides/layoutslide/
---
## LayoutSlide klasse

Stelt een layoutdia voor.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retourneert de achtergrond van de dia. Alleen-lezen [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retourneert de collectie van ActiveX-besturingselementen op een dia. Alleen-lezen [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retourneert de aangepaste gegevens van de dia. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Retourneert een verzameling tekenrichtlijnen voor de layoutdia. Alleen-lezen [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze layoutdia. Alleen-lezen Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Retourneert de HeaderFooter-beheerder van de layoutdia. Alleen-lezen [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot de ingesloten hyperlinks. Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Retourneert het layouttype van deze layoutdia. Alleen-lezen [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Retourneert of stelt de masterdia in voor een layout. Lezen/schrijven [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Retourneert of stelt de naam van een dia in. Lezen/schrijven String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Retourneert de placeholder-beheerder van de layoutdia. Alleen-lezen [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retourneert IPresentation-interface. Alleen-lezen [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retourneert de vormen van een dia. Alleen-lezen [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Bepaalt of vormen op de masterdia al dan niet getoond moeten worden op dia's. Lezen/schrijven Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retourneert de ID van een dia. Alleen-lezen UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retourneert het Transition-object dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling wordt voortgeschoven. Alleen-lezen [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Retourneert de overschrijf-thema-beheerder. Alleen-lezen [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retourneert animatie-tijdlijnobject. Alleen-lezen [`IAnimationTimeLine`](../ianimationtimeline). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retourneert een effectief thema voor deze dia. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur van de dia en statische inhoud. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, zoals SlideId, en dynamische inhoud, zoals de huidige datumwaarde in een datum-placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Vindt de eerste verschijning van een vorm met de opgegeven alternatieve tekst. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Retourneert een array met alle dia's die afhankelijk zijn van deze layoutdia. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's van alle geschikte vormen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Voegt runs met dezelfde opmaak samen in alle alinea's van alle geschikte vormen. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Verwijdert de layout uit de presentatie. |

### Zie ook

* klasse [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->