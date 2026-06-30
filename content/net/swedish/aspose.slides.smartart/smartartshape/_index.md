---
title: SmartArtShape
second_title: Aspose.Sildes för .NET API-referens
description: Representerar SmartArt-form
type: docs
weight: 10640
url: /sv/aspose.slides.smartart/smartartshape/
---
## SmartArtShape klass

Representerar SmartArt-form

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Returnerar en samling av figurens justeringsvärden. Endast läsning [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en figur. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger rubriken för den alternativa texten som är associerad med en figur. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en figur kommer att renderas i svartvit visningsläge. Läs/skriv [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på figuren. Endast läsning Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar figurens anpassade data. Endast läsning [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en figur. Obs: kan returnera null för vissa typer av figurer som inte har effekt-egenskaper. Endast läsning [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformat-egenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har fyllnings-egenskaper. Endast läsning [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger figurens ramegenskaper. Läs/skriv [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger figurens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Anger om figuren är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänkshanteraren. Endast läsning [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för muspekare. Läs/skriv [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Anger om figuren är grupperad. Endast läsning Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Anger om figuren är TextHolder_PPT. Endast läsning Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformat-egenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har linje-egenskaper. Endast läsning [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en figur. Måste vara icke-null. Använd tom sträng om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar ett bildspelsomfattande unikt identifierare som förblir konstant under figurens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till figuren var som helst i dokumentet. Endast läsning UInt32. Se även [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar föräldra-GroupShape-objektet om figuren är grupperad. Annars returneras null. Endast läsning [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en figur. Returnerar null om figuren saknar platshållare. Endast läsning [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den föräldra-presentation som bilden tillhör. Endast läsning [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa egenskaperna för figurens ram. Läs/skriv [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den specificerade figuren roteras kring z-axeln. Ett positivt värde innebär medursrotation; ett negativt värde innebär motursrotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Returnerar figurens lås. Endast läsning [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Returnerar figurens stilobjekt. Endast läsning [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Returnerar eller anger geometrins förinställda typ. Obs: vid värdeförändring återställs alla justeringsvärden till sina standardvärden. Läs/skriv [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den föräldra-bilden för en figur. Endast läsning [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Returnerar texten för SmartArt-figuren. Endast läsning [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har 3D-egenskaper. Endast läsning [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentationsomfattande identifierare avsedd för tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programatiskt, får det inte behandlas som en bestående unik nyckel. Endast läsning UInt32. Se även [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger figurens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för figurens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för figurens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar figurens position i z-ordningen. Shapes[0] returnerar figuren längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar figuren längst fram i z-ordningen. Endast läsning Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en angiven. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Skapar och returnerar en array av figurens element. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarfigur (figur från layouten och/eller mästarbilden som den aktuella figuren är ärvd från). Null returneras om den aktuella figuren inte är avledd. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Returnerar en kopia av geometrivägen för figuren. Koordinaterna är relativt figurens övre vänstra hörn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar figurens miniatyrbild. ShapeThumbnailBounds.Shape används som standard för miniatyrbildens gränstyper. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar figurens miniatyrbild. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar figuren visuella gränser beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna figur inte är en platshållare. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Uppdaterar figurens geometri från [`IGeometryPath`](../../aspose.slides/igeometrypath)-objektet. Koordinaterna måste vara relativa till figurens övre vänstra hörn. Ändrar figurens typ ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) till Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Uppdaterar figurens geometri från en array av [`IGeometryPath`](../../aspose.slides/igeometrypath). Koordinaterna måste vara relativa till figurens övre vänstra hörn. Ändrar figurens typ ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) till Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar figurens innehåll som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar figurens innehåll som en SVG-fil. |

### Se också

* klass [GeometryShape](../../aspose.slides/geometryshape)
* gränssnitt [ISmartArtShape](../ismartartshape)
* namnrymd [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->