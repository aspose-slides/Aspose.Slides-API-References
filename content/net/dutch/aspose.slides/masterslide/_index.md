---
title: MasterSlide
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een master-slide voor in een presentatie.
type: docs
weight: 8030
url: /nl/aspose.slides/masterslide/
---
## MasterSlide klasse

Stelt een master-slide voor in een presentatie.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retourneert de achtergrond van de slide. Alleen-lezen [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Retourneert de stijl van tekst in een body. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retourneert de collectie van ActiveX-besturingselementen op een slide. Alleen-lezen [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retourneert de aangepaste gegevens van de slide. Alleen-lezen [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Retourneert een collectie van tekengidsen voor de master-slide. Alleen-lezen [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Retourneert true als er ten minste één slide bestaat die afhankelijk is van deze master-slide. Alleen-lezen Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Retourneert de HeaderFooter-manager van de master-slide. Alleen-lezen [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot ingesloten hyperlinks. Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Retourneert de collectie van onderliggende layout-slides voor deze master-slide. Alleen-lezen [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Retourneert of stelt de naam van een master-slide in. Lezen/Schrijven String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Retourneert de stijl van andere tekst. Alleen-lezen [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retourneert IPresentation-interface. Alleen-lezen [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Bepaalt of de bijbehorende master wordt verwijderd wanneer alle slides die die master volgen, worden verwijderd. Opmerking: Aspose.Slides zal nooit zelf ongebruikte masters verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [`RemoveUnused`](../masterslidecollection/removeunused) aan. Lezen/Schrijven Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retourneert de shapes van een slide. Alleen-lezen [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Bepaalt of shapes op de master-slide moeten worden getoond op slides of niet. Voor de master-slide zelf geeft deze eigenschap altijd `false` terug. Lezen/Schrijven Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retourneert de ID van een slide. Alleen-lezen UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retourneert het Transition-object dat informatie bevat over hoe de opgegeven slide tijdens een diavoorstelling vooruitgaat. Alleen-lezen [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Retourneert de themamanager. Alleen-lezen [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retourneert het animatietijdlijn-object. Alleen-lezen [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Retourneert de stijl van een titeltekst. Alleen-lezen [`ITextStyle`](../itextstyle). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Maakt een nieuwe master-slide op basis van de huidige, past er een extern thema op toe en past de gemaakte master-slide toe op alle afhankelijke slides. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retourneert een effectief thema voor deze slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de slide. Twee slides zijn gelijk als alle shapes, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijvoorbeeld SlideId, en dynamische inhoud, bijvoorbeeld de huidige datumwaarde in een Datum-placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Zoekt de eerste voorkoming van een shape met de opgegeven alternatieve tekst. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Retourneert een array met alle slides die afhankelijk zijn van deze master-slide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's van alle acceptabele shapes. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Voegt runs met dezelfde opmaak samen in alle alinea's van alle acceptabele shapes. |

### Zie ook

* klasse [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->