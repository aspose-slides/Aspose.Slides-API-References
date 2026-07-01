---
title: PictureFrame
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en ram med en bild inuti.
type: docs
weight: 9390
url: /sv/aspose.slides/pictureframe/
---
## PictureFrame-klass

Representerar en ram med en bild inuti.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Returnerar en samling av formens justeringsvärden. Skrivskyddad [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln för den alternativa texten som är associerad med en form. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen anger hur en form ska renderas i svart-vit visningsläge.. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på formen. Skrivskyddad Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar formens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en form. Obs: kan returnera null för vissa typer av former som inte har effektegenskaper. Skrivskyddad [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformat-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har fyllnings-egenskaper. Skrivskyddad [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger ramens egenskaper för formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger formens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Anger om formen är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-klick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänk-hanteraren. Skrivskyddad [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-över. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Anger om PictureFrame är ett Cameo-objekt eller inte. Skrivskyddad Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet ”Mark as decorative”. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Anger om formen är grupperad. Skrivskyddad Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Anger om formen är TextHolder_PPT. Skrivskyddad Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformat-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har linje-egenskaper. Skrivskyddad [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tom sträng om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en bild-scopad unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod referera till formen på ett tillförlitligt sätt var som helst i dokumentet. Skrivskyddad UInt32. Se också [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar överordnad GroupShape-objekt om formen är grupperad. Annars returneras null. Skrivskyddad [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Returnerar PictureFillFormat-objektet för en bildram. Skrivskyddad [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Returnerar formens lås. Skrivskyddad [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en form. Returnerar null om formen saknar platshållare. Skrivskyddad [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Skrivskyddad [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa ram-egenskaperna för formen. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Returnerar eller anger skalningen av höjden (i förhållande till originalbildens storlek) för bildramen. Värde 1,0 motsvarar 100 %. Läs/skriv Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Returnerar eller anger skalningen av bredden (i förhållande till originalbildens storlek) för bildramen. Värde 1,0 motsvarar 100 %. Läs/skriv Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Returnerar formens lås. Skrivskyddad [`IPictureFrameLock`](../ipictureframelock). (2 egenskaper) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Returnerar formens stilobjekt. Skrivskyddad [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Returnerar eller anger AutoShape-typen för en PictureFrame. Alla tillåtna element i mängden [`ShapeType`](../shapetype) är giltiga, förutom alla sorters linjer: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en form. Skrivskyddad [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effekt-egenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har 3D-egenskaper. Skrivskyddad [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-scopad identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan återtilldelas av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel. Skrivskyddad UInt32. Se också [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger formens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för formens övre-vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för formens övre-vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och anger platshållarens egenskaper till en specificerad. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Skapar och returnerar en array av formens element. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarform (form från layouten och/eller mastern som den aktuella formen ärvs från). Null returneras om den aktuella formen inte ärvs. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Returnerar kopian av geometrins bana för formen. Koordinaterna är relativa till formens övre-vänstra hörn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar formens miniatyrbild. ShapeThumbnailBounds.Shape-typ av miniatyrbild används som standard. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar formens miniatyrbild. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar de visuella avgränsningarna för formen beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Anger att denna form inte är en platshållare. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Uppdaterar formens geometri från [`IGeometryPath`](../igeometrypath)-objekt. Koordinaterna måste vara relativa till formens övre-vänstra hörn. Ändrar formens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Uppdaterar formens geometri från en array av [`IGeometryPath`](../igeometrypath). Koordinaterna måste vara relativa till formens övre-vänstra hörn. Ändrar formens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar innehållet i Shape som SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar innehållet i Shape som SVG-fil. |

### Exempel

Följande exempel visar hur man ändrar miniatyrbild för ljudram.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Lägger till ett ljudram på bilden med en angiven position och storlek.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Lägger till en bild i presentationens resurser.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Anger bilden för ljudramen.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	// Sparar den modifierade presentationen till disk
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Se också

* klass [GeometryShape](../geometryshape)
* gränssnitt [IPictureFrame](../ipictureframe)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->