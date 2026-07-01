---
title: GraphicalObject
second_title: Aspose.Sildes för .NET API-referens
description: Representerar abstrakt grafiskt objekt.
type: docs
weight: 5050
url: /sv/aspose.slides/graphicalobject/
---
## GraphicalObject klass

Representerar abstrakt grafiskt objekt.

```csharp
public class GraphicalObject : Shape, IGraphicalObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln för alternativ text associerad med en form. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en form kommer att renderas i svart-vitt visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Endast läsning Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Endast läsning [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. Obs: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Endast läsning [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformat-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har fyllningsegenskaper. Endast läsning [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger formens ramegenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returnerar formens lås. Endast läsning [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger formens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Bestämmer om formen är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-klick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänkshanteraren. Endast läsning [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-över. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Bestämmer om formen är grupperad. Endast läsning Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Bestämmer om formen är TextHolder_PPT. Endast läsning Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har linje-egenskaper. Endast läsning [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tom sträng om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en unikt identifierare med räckvidd på bild som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från vilken plats som helst i dokumentet. Endast läsning UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras null. Endast läsning [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Endast läsning [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Endast läsning [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger råa ramegenskaper för formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader den specificerade formen roteras runt z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde indikerar motursrotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returnerar formens lås. Endast läsning [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 egenskaper) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en form. Endast läsning [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Endast läsning [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern identifierare med räckvidd på presentationen avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omtilldelas av användaren eller programmässigt, får det inte betraktas som en beständig unik nyckel. Endast läsning UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger formens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Endast läsning Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållaregenskaper till en specificerad. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från). Null returneras om den aktuella formen inte ärvs. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar formens miniatyr. ShapeThumbnailBounds.Shape miniatyrgränstyp används som standard. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyr. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna form inte är en platshållare. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar innehållet i Form som SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar innehållet i Form som SVG-fil. |

### Se även

* klass [Shape](../shape)
* gränssnitt [IGraphicalObject](../igraphicalobject)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->