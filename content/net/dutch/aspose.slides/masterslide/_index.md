---
title: MasterSlide
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een masterdia in een presentatie voor.
type: docs
weight: 8050
url: /nl/aspose.slides/masterslide/
---
## MasterSlide klasse

Stelt een masterdia in een presentatie voor.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retourneert de achtergrond van de dia. Alleen-lezen [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Retourneert de stijl van een hoofdtekst. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retourneert de collectie van ActiveX-besturingselementen op een dia. Alleen-lezen [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retourneert de aangepaste gegevens van de dia. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Retourneert een collectie van tekengidsen voor de masterdia. Alleen-lezen [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze masterdia. Alleen-lezen Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Retourneert de HeaderFooter-beheerder van de masterdia. Alleen-lezen [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot de opgenomen hyperlinks. Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Retourneert de collectie van onderliggende lay-outdia's voor deze masterdia. Alleen-lezen [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Retourneert of stelt de naam van een masterdia in. Lezen/schrijven String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Retourneert de stijl van een andere tekst. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retourneert de IPresentation-interface. Alleen-lezen [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Bepaalt of de bijbehorende master wordt verwijderd wanneer alle dia's die die master volgen, worden verwijderd. Opmerking: Aspose.Slides zal nooit zelf een ongebruikte master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [`RemoveUnused`](../masterslidecollection/removeunused) aan. Lezen/schrijven Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retourneert de vormen van een dia. Alleen-lezen [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Specificeert of vormen op de masterdia al dan niet op dia's moeten worden weergegeven. Voor de masterdia zelf geeft deze eigenschap altijd `false` terug. Lezen/schrijven Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retourneert de ID van een dia. Alleen-lezen UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retourneert het Transition-object dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling wordt voortgezet. Alleen-lezen [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Retourneert de thema-beheerder. Alleen-lezen [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retourneert het animatie-tijdlijnobject. Alleen-lezen [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Retourneert de stijl van een titeltekst. Alleen-lezen [`ITextStyle`](../itextstyle). |

## Methoden

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Maakt een nieuwe masterdia op basis van de huidige, past er een extern thema op toe en past de gemaakte masterdia toe op alle afhankelijke dia's. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retourneert een effectief thema voor deze dia. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. Bij de vergelijking worden unieke identifier-waarden, bijv. SlideId, en dynamische inhoud, bijv. de huidige datumwaarde in een Datum-plaatsaanduiding, niet meegenomen. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Zoekt de eerste verschijning van een vorm met de opgegeven alternatieve tekst. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Retourneert een array met alle dia's die afhankelijk zijn van deze masterdia. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's van alle aanvaardbare vormen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Voegt runs met dezelfde opmaak samen in alle alinea's van alle aanvaardbare vormen. |

### Zie ook

* klasse [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->