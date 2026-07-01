---
title: SummaryZoomSection
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett Summary Zoom Section-objekt i en Summary Zoom-ram.
type: docs
weight: 10760
url: /sv/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection klass

Representerar ett Summary Zoom Section-objekt i en Summary Zoom-ram.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln för den alternativa texten som är associerad med en form. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egendom specificerar hur en form renderas i svart-vitt läge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Endast läsning Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Endast läsning [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Returnerar textbeskrivningen av Summary Zoom Section-objektet. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. Observera: kan returnera null för vissa typer av former som saknar effekt-egenskaper. Endast läsning [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformaterings-egenskaper för en form. Observera: kan returnera null för vissa typer av former som saknar fyllnings-egenskaper. Endast läsning [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger ramens egenskaper för formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returnerar formens lås. Endast läsning [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger höjden på formen, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Anger om formen är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänkshanteraren. Endast läsning [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för muspekare. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Hämtar eller anger bildtypen för ett zoom-objekt. Läs/skriv [`ZoomImageType`](../zoomimagetype). Standardvärde: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet “Mark as decorative”. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Anger om formen är grupperad. Endast läsning Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Anger om formen är TextHolder_PPT. Endast läsning Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en form. Observera: kan returnera null för vissa typer av former som saknar linje-egenskaper. Endast läsning [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Får inte vara null. Använd tom sträng vid behov. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar ett bildspels-specifikt unikt ID som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen var som helst i dokumentet. Endast läsning UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras null. Endast läsning [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Endast läsning [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Endast läsning [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa ram-egenskaperna för formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Hämtar eller anger navigationsbeteendet i bildspel. Läs/skriv Boolean. Standardvärde: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returnerar formens lås. Endast läsning [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 egenskaper) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Hämtar eller anger värdet som bestämmer om Zoom-objektet ska använda bakgrunden från mål-bilden. Läs/skriv Boolean. Standardvärde: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en form. Endast läsning [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Hämtar eller anger sektion-objektet som Section Zoom-objektet länkar till. Läs/skriv [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form. Observera: kan returnera null för vissa typer av former som saknar 3D-egenskaper. Endast läsning [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Returnerar texttiteln för Summary Zoom Section-objektet. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Hämtar eller anger varaktigheten för övergången mellan Zoom och bild. Läs/skriv Single. Standardvärde: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar ett internt, presentations-specifikt ID avsett för användning av tillägg eller annan kod. Eftersom detta värde kan tilldelas om av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel. Endast läsning UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger bredden på formen, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Hämtar eller anger bilden för zoom-objektet. Läs/skriv [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Endast läsning Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållarens egenskaper till den angivna. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller mastern som den nuvarande formen ärvs från). Null returneras om den nuvarande formen inte ärvs. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar formens miniatyrbild. ShapeThumbnailBounds.Shape-typ används som standard. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyrbild. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar formens visuella gränser beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna form inte är en platshållare. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar innehållet i Shape som SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | Sparar innehållet i Shape som SVG-fil. |

### Se även

* klass [SectionZoomFrame](../sectionzoomframe)
* gränssnitt [ISummaryZoomSection](../isummaryzoomsection)
* namnrum [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->