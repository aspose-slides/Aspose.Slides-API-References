---
title: LayoutSlide
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en layoutbild.
type: docs
weight: 7640
url: /sv/aspose.slides/layoutslide/
---
## LayoutSlide klass

Representerar en layoutbild.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returnerar bildens bakgrund. Skrivskyddad [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returnerar samlingen av ActiveX-kontroller på en bild. Skrivskyddad [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returnerar bildens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Returnerar en samling av ritningsguider för layoutbilden. Skrivskyddad [`IDrawingGuidesCollection`](../idrawingguidescollection). |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Returnerar true om det finns minst en bild som beror på denna layoutbild. Skrivskyddad Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Returnerar HeaderFooter-hanteraren för layoutbilden. Skrivskyddad [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Tillhandahåller enkel åtkomst till innehållna hyperlänkar. Skrivskyddad [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Returnerar layouttyp för denna layoutbild. Skrivskyddad [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Returnerar eller anger masterbilden för en layout. Läs/skriv [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Returnerar eller anger namnet på en bild. Läs/skriv String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Returnerar platshållarhanteraren för layoutbilden. Skrivskyddad [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returnerar IPresentation-gränssnittet. Skrivskyddad [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returnerar formerna på en bild. Skrivskyddad [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Anger om former på masterbilden ska visas på bilder eller inte. Läs/skriv Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returnerar ID för en bild. Skrivskyddad UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returnerar Transition-objektet som innehåller information om hur den angivna bilden avancerar under ett bildspel. Skrivskyddad [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Returnerar den överskrivande temahanteraren. Skrivskyddad [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returnerar animations-tidslinjeobjektet. Skrivskyddad [`IAnimationTimeLine`](../ianimationtimeline). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returnerar ett effektivt tema för den här bilden. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bestämmer om de två IBaseSlide-instanserna är lika. Returvärdet beräknas baserat på bildens struktur och statiskt innehåll. Två bilder är lika om alla former, stilar, texter, animation och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Hittar den första förekomsten av en form med den angivna alternativa texten. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Returnerar en array med alla bilder som beror på denna layoutbild. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Tar bort layout från presentationen. |

### Se även

* klass [BaseSlide](../baseslide)
* gränssnitt [ILayoutSlide](../ilayoutslide)
* namnrymd [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->