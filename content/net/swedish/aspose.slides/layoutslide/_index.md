---
title: LayoutSlide
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en layout-bild.
type: docs
weight: 7620
url: /sv/aspose.slides/layoutslide/
---
## LayoutSlide klass

Representerar en layout-bild.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Returnerar bildens bakgrund. Read-only [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Returnerar samlingen av ActiveX-kontroller på en bild. Read-only [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Returnerar bildens anpassade data. Read-only [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Returnerar en samling av ritningsguider för layout-bilden. Read-only [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Returnerar true om det finns minst en bild som beror på denna layoutbild. Read-only Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Returnerar HeaderFooter-hanterare för layoutbilden. Read-only [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar. Read-only [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Returnerar layouttyp för denna layoutbild. Read-only [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Returnerar eller anger master-bilden för en layout. Read/write [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Returnerar eller anger namnet på en bild. Read/write String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Returnerar platshållarhanteraren för layoutbilden. Read-only [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Returnerar IPresentation-gränssnittet. Read-only [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Returnerar formerna på en bild. Read-only [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Anger om former på master-bilden ska visas på bilder eller inte. Read/write Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Returnerar ID-et för en bild. Read-only UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Returnerar Transition-objektet som innehåller information om hur den angivna bilden avancerar under ett bildspel. Read-only [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Returnerar den överskrivande temahanteraren. Read-only [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Returnerar animations-tidslinjeobjektet. Read-only [`IAnimationTimeLine`](../ianimationtimeline). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Returnerar ett effektivt tema för denna bild. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determinerar om de två IBaseSlide-instanserna är lika. Returnerat värde beräknas baserat på bildens struktur och statiska innehåll. Två bilder är lika om alla former, stilar, texter, animation och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Hittar första förekomsten av en form med angiven alternativ text. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Returnerar en array med alla bilder som beror på denna layoutbild. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Tar bort layout från presentationen. |

### Se också

* klass [BaseSlide](../baseslide)
* gränssnitt [ILayoutSlide](../ilayoutslide)
* namnområde [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->