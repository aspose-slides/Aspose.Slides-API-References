---
title: MasterSlide
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en master slide i en presentation.
type: docs
weight: 8050
url: /sv/aspose.slides/masterslide/
---
## MasterSlide klass

Representerar en master slide i en presentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returnerar slidens bakgrund. Skrivskyddad [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Returnerar stilen för brödtexten. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returnerar samlingen av ActiveX-kontroller på en slide. Skrivskyddad [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returnerar slidens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Returnerar en samling av ritningsguider för master slide. Skrivskyddad [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Returnerar true om det finns minst en slide som beror på denna master slide. Skrivskyddad Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Returnerar HeaderFooter-hanterare för master slide. Skrivskyddad [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Tillhandahåller enkel åtkomst till innehållna hyperlänkar. Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Returnerar samlingen av underordnade layout-slides för denna master slide. Skrivskyddad [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Returnerar eller anger namnet på en master slide. Läs/skriv String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Returnerar stilen för en annan text. Skrivskyddad [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returnerar IPresentation-gränssnittet. Skrivskyddad [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Bestämmer om motsvarande master tas bort när alla slides som följer den mastern har raderats. Obs: Aspose.Slides kommer aldrig att ta bort någon oanvänd master själv, för att faktiskt ta bort oanvända masters anropa [`RemoveUnused`](../masterslidecollection/removeunused) Läs/skriv Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returnerar formerna på en slide. Skrivskyddad [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Anger om former på master slide ska visas på slides eller inte. För själva master slide returnerar denna egenskap alltid `false`. Läs/skriv Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returnerar ID-t för en slide. Skrivskyddad UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returnerar Transition-objektet som innehåller information om hur den angivna sliden fortskrider under en bildspelsvisning. Skrivskyddad [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Returnerar temahanteraren. Skrivskyddad [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returnerar animations-tidslinje-objektet. Skrivskyddad [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Returnerar stilen för en titeltext. Skrivskyddad [`ITextStyle`](../itextstyle). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Skapar en ny master slide baserad på den aktuella, applicerar ett externt tema på den och tillämpar den skapade master slide på alla beroende slides. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returnerar ett effektivt tema för denna slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestämmer om de två IBaseSlide-instanserna är lika. Returvärdet beräknas baserat på slidens struktur och statiska innehåll. Två slides är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifieringsvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Hittar första förekomsten av en form med den angivna alternativa texten. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Returnerar en array med alla slides som beror på denna master slide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Kombinerar löptexter med samma formatering i alla stycken i alla accepterade former. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Kombinerar löptexter med samma formatering i alla stycken i alla accepterade former. |

### Se också

* klass [BaseSlide](../baseslide)
* gränssnitt [IMasterSlide](../imasterslide)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->