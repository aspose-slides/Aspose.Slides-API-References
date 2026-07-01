---
title: Connector
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en anslutning.
type: docs
weight: 2650
url: /sv/aspose.slides/connector/
---
## Connector klass

Representerar en anslutning.

```csharp
public class Connector : GeometryShape, IConnector
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Returnerar en samling av figurens justeringsvärden. Skrivskyddad [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en figur. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln för den alternativa texten som är associerad med en figur. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egendomen specificerar hur en figur ska renderas i svart-vit visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningsställen på figuren. Skrivskyddad Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Returnerar anslutningens lås. Skrivskyddad [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar figurens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en figur. Obs: kan returnera null för vissa typer av figurer som inte har effekt-egenskaper. Skrivskyddad [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Returnerar eller anger figuren som anslutningens ände ska fästas vid. Läs/skriv [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Returnerar eller anger indexet för anslutningsstället för slutfiguren. Läs/skriv UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformat-egenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har fyllningsegenskaper. Skrivskyddad [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar figurramens egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger figurens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Avgör om figuren är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänks-hanteraren. Skrivskyddad [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-över. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Avgör om figuren är grupperad. Skrivskyddad Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Avgör om figuren är TextHolder_PPT. Skrivskyddad Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformat-egenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har linjeegenskaper. Skrivskyddad [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en figur. Måste vara icke-null. Använd ett tomt strängvärde om nödvändigt. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en bild-specifik unik identifierare som förblir konstant under figurens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till figuren från var som helst i dokumentet. Skrivskyddad UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar förälder-GroupShape-objektet om figuren är grupperad. Annars returneras null. Skrivskyddad [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en figur. Returnerar null om figuren inte har någon platshållare. Skrivskyddad [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Skrivskyddad [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa figurramsegenskaperna. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna figuren är roterad runt z-axeln. Ett positivt värde indikerar medursrotation; ett negativt värde indikerar motursrotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Returnerar figurens lås. Skrivskyddad [`IConnectorLock`](../iconnectorlock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Returnerar figurens stilobjekt. Skrivskyddad [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Returnerar eller anger AutoShape-typen. Läs/skriv [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en figur. Skrivskyddad [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Returnerar eller anger figuren som anslutningens början ska fästas vid. Läs/skriv [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Returnerar eller anger indexet för anslutningsstället för startfiguren. Läs/skriv UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som har 3D-effektegenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har 3D-egenskaper. Skrivskyddad [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas som en beständig unik nyckel. Skrivskyddad UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger figurens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för figurens övre-vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för figurens övre-vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar figurens position i z-ordningen. Shapes[0] returnerar figuren längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar figuren längst fram i z-ordningen. Skrivskyddad Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Skapar och returnerar en array av figurens element. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarfigur (figur från layout- och/eller mastern som den aktuella figuren är ärvd från). Null returneras om den aktuella figuren inte är ärvd. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Returnerar en kopia av geometriformens sökväg. Koordinaterna är relativa till figurens övre-vänstra hörn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar figurens miniatyr. ShapeThumbnailBounds.Shape används som standard för miniatyrens gränser. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar figurens miniatyr. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar de visuella gränserna för figuren beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna figur inte är en platshållare. |
| [Reroute](../../aspose.slides/connector/reroute)() | Ruttar om anslutningen så att den tar den kortaste möjliga vägen mellan de figurer den ansluter. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Uppdaterar figurens geometri från [`IGeometryPath`](../igeometrypath)-objektet. Koordinaterna måste vara relativa till figurens övre-vänstra hörn. Ändrar figurens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Uppdaterar figurens geometri från array av [`IGeometryPath`](../igeometrypath). Koordinaterna måste vara relativa till figurens övre-vänstra hörn. Ändrar figurens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar figurens innehåll som SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar figurens innehåll som SVG-fil. |

### Se även

* klass [GeometryShape](../geometryshape)
* gränssnitt [IConnector](../iconnector)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->