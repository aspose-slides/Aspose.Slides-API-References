---
title: LayoutSlide
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een layoutslide voor.
type: docs
weight: 7660
url: /nl/aspose.slides/layoutslide/
---
## LayoutSlide klasse

Stelt een layoutslide voor.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Geeft de achtergrond van de slide terug. Alleen-lezen [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Geeft de verzameling van ActiveX-besturingselementen op een slide terug. Alleen-lezen [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Geeft de aangepaste gegevens van de slide terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Geeft een verzameling van tekengidsen voor de layoutslide terug. Alleen-lezen [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Geeft true terug als er minstens één slide bestaat die afhankelijk is van deze layoutslide. Alleen-lezen Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Geeft de HeaderFooter-beheerder van de layoutslide terug. Alleen-lezen [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot ingesloten hyperlinks. Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Geeft het layouttype van deze layoutslide terug. Alleen-lezen [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Geeft de master-slide voor een layout terug of stelt deze in. Lezen/Schrijven [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Geeft de naam van een slide terug of stelt deze in. Lezen/Schrijven String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Geeft de placeholder-beheerder van de layoutslide terug. Alleen-lezen [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Geeft de IPresentation-interface terug. Alleen-lezen [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Geeft de shapes van een slide terug. Alleen-lezen [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Geeft aan of shapes op de master-slide al dan niet getoond moeten worden op slides. Lezen/Schrijven Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Geeft de ID van een slide terug. Alleen-lezen UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Geeft het Transition-object terug dat informatie bevat over hoe de opgegeven slide vordert tijdens een diavoorstelling. Alleen-lezen [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Geeft de overschrijf-thema-beheerder terug. Alleen-lezen [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Geeft het animatie-tijdlijnobject terug. Alleen-lezen [`IAnimationTimeLine`](../ianimationtimeline). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Geeft een effectief thema voor deze slide terug. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de slide. Twee slides zijn gelijk als alle shapes, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, zoals SlideId, en dynamische inhoud, zoals de huidige datumwaarde in een datum-placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Zoekt de eerste verschijning van een shape met de opgegeven alternatieve tekst. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Geeft een array met alle slides terug die afhankelijk zijn van deze layoutslide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's van alle acceptabele shapes. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Voegt runs met dezelfde opmaak samen in alle alinea's van alle acceptabele shapes. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Verwijdert layout uit de presentatie. |

### Zie Ook

* klasse [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->