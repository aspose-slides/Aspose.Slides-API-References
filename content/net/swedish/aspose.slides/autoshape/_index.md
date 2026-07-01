---
title: AutoShape
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en AutoShape.
type: docs
weight: 880
url: /sv/aspose.slides/autoshape/
---
## AutoShape klass

Representerar en AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Returnerar en samling av formens justeringsvärden. Skrivskyddad [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln för den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Returnerar autoshapens lås. Skrivskyddad [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egendom som anger hur en form ska renderas i svart-vitt läge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Skrivskyddad Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. Obs: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Skrivskyddad [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformat-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har fyllnings-egenskaper. Skrivskyddad [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger formens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger formens höjd i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Anger huruvida formen är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänk-hanteraren. Skrivskyddad [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-över. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet ”Mark as decorative”. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Anger huruvida formen är grupperad. Skrivskyddad Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Anger om formen är en textruta. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Anger huruvida formen är TextHolder_PPT. Skrivskyddad Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformat-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har linje-egenskaper. Skrivskyddad [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tomt strängvärde om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar ett bildspels-specifikt unikt id som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen var som helst i dokumentet. Skrivskyddad UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar överordnat GroupShape-objekt om formen är grupperad. Annars returneras null. Skrivskyddad [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Skrivskyddad [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar bildspelets överordnade presentation. Skrivskyddad [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa ram-egenskaperna för en form. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde betyder medurs rotation; ett negativt värde betyder moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Returnerar formens lås. Skrivskyddad [`IAutoShapeLock`](../iautoshapelock). (2 egenskaper) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Returnerar formens stil-objekt. Skrivskyddad [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Returnerar eller anger geometri-preset-typen. Obs: vid värdeförändring återställs alla justeringsvärden till sina standardvärden. Läs/skriv [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den bildspels-specifika föräldrasliden för en form. Skrivskyddad [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Returnerar TextFrame-objektet för AutoShape. Skrivskyddad [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effekt-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Skrivskyddad [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar ett internt, presentation-specifikt id avsett för användning av tillägg eller annan kod. Eftersom detta värde kan återtilldelas av användaren eller programatiskt får det inte behandlas som en bestående unik nyckel. Skrivskyddad UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Anger huruvida denna autoshape ska fyllas med bildspels-bakgrundens fyllning istället för den som anges av stil eller fyllningsformat. Läs/skriv Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger formens bredd i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre-vänstra hörn i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre-vänstra hörn i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Lägger till ett nytt TextFrame till en form. Om formen redan har ett TextFrame ändras bara dess text. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Skapar och returnerar en array av formens element. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller mastern som den aktuella formen ärvs från). Null returneras om den aktuella formen inte ärvs. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Returnerar en kopia av geometrins sökväg för formen. Koordinaterna är relativt till formens övre-vänstra hörn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar formens miniatyrbild. FormThumbnailBounds.Shape-typ används som standard. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyrbild. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar formens visuella gräns beräknad från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna form inte är en platshållare. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Uppdaterar formens geometri från [`IGeometryPath`](../igeometrypath)-objektet. Koordinaterna måste vara relativa till formens övre-vänstra hörn. Ändrar formens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Uppdaterar formens geometri från en array av [`IGeometryPath`](../igeometrypath). Koordinaterna måste vara relativa till formens övre-vänstra hörn. Ändrar formens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar innehållet i Shape som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar innehållet i Shape som en SVG-fil. |

### Se även

* klass [GeometryShape](../geometryshape)
* gränssnitt [IAutoShape](../iautoshape)
* namnrymd [Aspose.Slides](../../aspose.slides)
* sammansättning [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->