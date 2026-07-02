---
title: MasterSlide
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een MasterSlide voor in een presentatie.
type: docs
weight: 8030
url: /nl/aspose.slides/masterslide/
---
## MasterSlide klasse

Stelt een masterslide voor in een presentatie.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retourneert de achtergrond van de dia. Alleen-lezen [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Retourneert de stijl van een hoofdtekst. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retourneert de verzameling van ActiveX-besturingselementen op een dia. Alleen-lezen [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retourneert de aangepaste gegevens van de dia. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Retourneert een verzameling tekenhulpmiddelen voor de masterslide. Alleen-lezen [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Retourneert true als er minstens één dia bestaat die afhankelijk is van deze masterslide. Alleen-lezen Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Retourneert de HeaderFooter-beheerder van de masterslide. Alleen-lezen [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot ingesloten hyperlinks. Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Retourneert de verzameling van onderliggende layoutdia's voor deze masterslide. Alleen-lezen [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Retourneert of stelt de naam van een masterslide in. Lezen/schrijven String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Retourneert de stijl van een andere tekst. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retourneert IPresentation-interface. Alleen-lezen [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle dia's die die master volgen, worden verwijderd. Opmerking: Aspose.Slides zal nooit zelfstandig een ongebruikte master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [`RemoveUnused`](../masterslidecollection/removeunused) aan. Lezen/schrijven Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retourneert de vormen van een dia. Alleen-lezen [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Specificeert of vormen op de masterslide moeten worden weergegeven op dia's of niet. Voor de masterslide zelf retourneert deze eigenschap altijd `false`. Lezen/schrijven Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retourneert de ID van een dia. Alleen-lezen UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retourneert het Transition-object dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling wordt voortgezet. Alleen-lezen [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Retourneert de themabeheerder. Alleen-lezen [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retourneert het animatietijdlijnobject. Alleen-lezen [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Retourneert de stijl van een titulattekst. Alleen-lezen [`ITextStyle`](../itextstyle). |

## Methoden

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Maakt een nieuwe masterslide op basis van de huidige, past een extern thema toe erop en past de gemaakte masterslide toe op alle afhankelijke dia's. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retourneert een effectief thema voor deze dia. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bv. SlideId, en dynamische inhoud, bv. de huidige datumwaarde in Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Vindt de eerste vondst van een vorm met de opgegeven alternatieve tekst. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Retourneert een array met alle dia's die afhankelijk zijn van deze masterslide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's van alle acceptabele vormen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen. |

### Zie ook

* klasse [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->