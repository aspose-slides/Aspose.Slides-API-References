---
title: Slide
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en bild i en presentation.
type: docs
weight: 9960
url: /sv/aspose.slides/slide/
---
## Slide klass

Representerar en bild i en presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returnerar bildens bakgrund. Skrivskyddad [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returnerar samlingen av ActiveX-kontroller på en bild. Skrivskyddad [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returnerar bildens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Returnerar HeaderFooter manager för bilden. Skrivskyddad [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Avgör om den angivna bilden är dold under en bildspel. Läs/skriv Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Tillhandahåller enkel åtkomst till innehållna hyperlänkar. Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Returnerar eller anger layout-bilden för den aktuella bilden. Läs/skriv [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Returnerar eller anger namnet på en bild. Läs/skriv String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Tillåter åtkomst till notbilden, lägga till och ta bort den. Skrivskyddad [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returnerar IPresentation gränssnitt. Skrivskyddad [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returnerar formerna på en bild. Skrivskyddad [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Anger om former på master-bilden ska visas på bilder eller inte. Läs/skriv Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returnerar ID för en bild. Skrivskyddad UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Returnerar ett bildnummer. Index för bilden i [`Slides`](../presentation/slides)-samlingen är alltid lika med SlideNumber - Presentation.FirstSlideNumber. Läs/skriv Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returnerar Transition object som innehåller information om hur den angivna bilden avancerar under en bildspel. Skrivskyddad [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Returnerar den överskuggande temahanteraren. Skrivskyddad [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returnerar animation timeline object. Skrivskyddad [`IAnimationTimeLine`](../ianimationtimeline). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returnerar ett effektivt tema för den här bilden. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Avgör om de två IBaseSlide-instanserna är lika. Returvärdet beräknas baserat på bildens struktur och statiskt innehåll. Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Hittar första förekomsten av en form med den angivna alternativtexten. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Returnerar ett Thumbnail Image-objekt (20 % av verklig storlek). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Returnerar ett Thumbnail Image-objekt. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Returnerar ett Thumbnail tiff-bildobjekt med angivna parametrar. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Returnerar ett Thumbnail Image-objekt med angiven storlek. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Returnerar ett Thumbnail Image-objekt med anpassad skalning. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Returnerar ett Thumbnail Image-objekt med angiven storlek. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Returnerar ett Thumbnail Image-objekt med anpassad skalning. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Returnerar alla bildkommentarer som lagts till av en specifik författare. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former. |
| [Remove](../../aspose.slides/slide/remove)() | Tar bort bilden från presentationen. |
| [Reset](../../aspose.slides/slide/reset)() | Återställer position, storlek och formatering för varje form som har en prototyp på LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Sparar bildens innehåll som en EMF-fil. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Sparar bildens innehåll som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Sparar bildens innehåll som en SVG-fil. |

### Se även

* klass [BaseSlide](../baseslide)
* gränssnitt [ISlide](../islide)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->