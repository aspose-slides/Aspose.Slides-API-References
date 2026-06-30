---
title: MasterSlide
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en masterbild i en presentation.
type: docs
weight: 8010
url: /sv/aspose.slides/masterslide/
---
## MasterSlide klass

Representerar en masterbild i en presentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Egenskaper

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returnerar bildens bakgrund. Skrivskyddad [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Returnerar stilen för brödtext. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returnerar samlingen av ActiveX-kontroller på en bild. Skrivskyddad [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returnerar bildens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Returnerar en samling ritlinjer för masterbilden. Skrivskyddad [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Returnerar true om det finns minst en bild som är beroende av denna masterbild. Skrivskyddad Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Returnerar HeaderFooter-hanteraren för masterbilden. Skrivskyddad [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Tillhandahåller enkel åtkomst till innehållna hyperlänkar. Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Returnerar samlingen av underordnade layoutbilder för denna masterbild. Skrivskyddad [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Returnerar eller anger namnet på en masterbild. Läs/skriv String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Returnerar stilen för annan text. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returnerar IPresentation-gränssnittet. Skrivskyddad [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Avgör om motsvarande master tas bort när alla bilder som följer den mastern har tagits bort. Obs! Aspose.Slides tar aldrig bort någon oanvänd master självt; för att faktiskt ta bort oanvända master, anropa [`RemoveUnused`](../masterslidecollection/removeunused). Läs/skriv Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returnerar formerna på en bild. Skrivskyddad [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Anger om former på masterbilden ska visas på bilder eller inte. För själva masterbilden returnerar denna egenskap alltid `false`. Läs/skriv Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returnerar ID-t för en bild. Skrivskyddad UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returnerar Transition-objektet som innehåller information om hur den angivna bilden avancerar under en bildspelsvisning. Skrivskyddad [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Returnerar temahanteraren. Skrivskyddad [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returnerar animations-tidslinjeobjektet. Skrivskyddad [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Returnerar stilen för en titeltext. Skrivskyddad [`ITextStyle`](../itextstyle). |

## Metoder

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Skapar en ny masterbild baserad på den aktuella, applicerar ett externt tema på den och tillämpar den skapade masterbilden på alla beroende bilder. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returnerar ett effektivt tema för den här bilden. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Avgör om de två IBaseSlide-instanserna är lika. Returvärdet beräknas baserat på bildens struktur och statiska innehåll. Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Söker den första förekomsten av en form med den angivna alternativa texten. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Returnerar en array med alla bilder som är beroende av denna masterbild. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Slår ihop körrader med samma formatering i alla stycken i alla acceptabla former. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Slår ihop körrader med samma formatering i alla stycken i alla acceptabla former. |

### Se också

* klass [BaseSlide](../baseslide)
* gränssnitt [IMasterSlide](../imasterslide)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->