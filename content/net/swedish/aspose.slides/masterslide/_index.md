---
title: MasterSlide
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en master-slide i en presentation.
type: docs
weight: 8030
url: /sv/aspose.slides/masterslide/
---
## MasterSlide klass

Representerar en master-slide i en presentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returns slide's background. Read-only [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Returnerar stilen för en brödtext. Read-only [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returnerar samlingen av ActiveX-kontroller på en slide. Read-only [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returnerar slidens anpassade data. Read-only [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Returnerar en samling ritningsguider för master-sliden. Read-only [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Returnerar true om det finns minst en slide som är beroende av denna master-slide. Read-only Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Returnerar HeaderFooter-hanteraren för master-sliden. Read-only [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Tillhandahåller enkel åtkomst till innehållna hyperlänkar. Read-only [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Returnerar samlingen av underordnade layout-slides för denna master-slide. Read-only [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Returns or sets the name of a master slide. Read/write String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Returnerar stilen för en annan text. Read-only [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returnerar IPresentation-gränssnittet. Read-only [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Determines whether the corresponding master is deleted when all the slides that follow that master are deleted. Note: Aspose.Slides will never remove any unused master by itself, to actually remove unused masters call [`RemoveUnused`](../masterslidecollection/removeunused) Read/write Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returnerar formerna på en slide. Read-only [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Anger om former på master-sliden ska visas på slides eller inte. För själva master-sliden returnerar denna egenskap alltid `false`. Read/write Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returnerar ID-t för en slide. Read-only UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returnerar Transition-objektet som innehåller information om hur den angivna sliden avancerar under en bildspelspresentation. Read-only [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Returnerar temahanteraren. Read-only [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returnerar animations-tidslinjeobjektet. Read-only [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Returnerar stilen för en titeltext. Read-only [`ITextStyle`](../itextstyle). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Skapar en ny master-slide baserad på den aktuella, applicerar ett externt tema på den och applicerar den skapade master-sliden på alla beroende slides. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returnerar ett effektivt tema för denna slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestämmer om de två IBaseSlide-instanserna är lika. Returvärdet beräknas baserat på slidens struktur och statiska innehåll. Två slides är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId, och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date-platshållare. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Hittar första förekomst av en form med den angivna alternativa texten. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Returnerar en array med alla slides som är beroende av denna master-slide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former. |

### Se också

* klass [BaseSlide](../baseslide)
* gränssnitt [IMasterSlide](../imasterslide)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->