---
title: VideoFrame
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett videoklipp på en bild.
type: docs
weight: 11720
url: /sv/aspose.slides/videoframe/
---
## VideoFrame klass

Representerar ett videoklipp på en bild.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Returnerar en samling av figurens justeringsvärden. Skrivskyddad [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa texten som är associerad med en figur. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln på den alternativa texten som är associerad med en figur. Läs/skriv String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egenskapen specificerar hur en figur renderas i svartvit visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Hämtar samlingen av stängda undertexter som är associerade med videoramen. Denna egenskap är skrivskyddad och returnerar ett [`ICaptionsCollection`](../icaptionscollection) som innehåller alla bildspår. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på figuren. Skrivskyddad Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar figurens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixel-effekter tillämpade på en figur. Observera: kan returnera null för vissa typer av figurer som saknar effekt-egenskaper. Skrivskyddad [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Returnerar eller anger inbäddat videoobjekt. Läs/skriv [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllningsformaterings-egenskaper för en figur. Observera: kan returnera null för vissa typer av figurer som saknar fyllningsegenskaper. Skrivskyddad [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger figurens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Avgör om en video visas i helskärmsläge. Läs/skriv Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger figurens höjd, mätt i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Avgör om figuren är dold. Läs/skriv Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Avgör om en VideoFrame är dold. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänkhanteraren. Skrivskyddad [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för muspekare. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Avgör om PictureFrame är ett Cameo-objekt eller inte. Skrivskyddad Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Avgör om figuren är grupperad. Skrivskyddad Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Avgör om figuren är TextHolder_PPT. Skrivskyddad Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linjeformaterings-egenskaper för en figur. Observera: kan returnera null för vissa typer av figurer som saknar linje-egenskaper. Skrivskyddad [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Returnerar eller anger namnet på en videofil som är länkad till en VideoFrame. Läs/skriv String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namnet på en figur. Måste vara icke-null. Använd tom sträng om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar en bild-avgränsad unik identifierare som förblir konstant under figurens livstid och låter PowerPoint eller interop-kod referera till figuren på ett pålitligt sätt från var som helst i dokumentet. Skrivskyddad UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar det överordnade GroupShape-objektet om figuren är grupperad. Annars returneras null. Skrivskyddad [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Returnerar PictureFillFormat-objektet för en bildram. Skrivskyddad [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Returnerar figurens lås. Skrivskyddad [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en figur. Returnerar null om figuren saknar platshållare. Skrivskyddad [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Avgör om en video är loopad. Läs/skriv Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Returnerar eller anger videouppspelningsläget. Läs/skriv [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Skrivskyddad [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa ram-egenskaperna för en figur. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Returnerar eller anger skalan för höjden (relativt originalbildens storlek) för bildramen. Värdet 1.0 motsvarar 100%. Läs/skriv Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Returnerar eller anger skalan för bredden (relativt originalbildens storlek) för bildramen. Värdet 1.0 motsvarar 100%. Läs/skriv Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Avgör om en video automatiskt spolas tillbaka till början så snart filmen har avslutats. Läs/skriv Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna figuren roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Returnerar figurens lås. Skrivskyddad [`IPictureFrameLock`](../ipictureframelock). (2 egenskaper) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Returnerar figurens stilobjekt. Skrivskyddad [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Returnerar eller anger AutoShape-typen för en PictureFrame. Alla objekt i uppsättningen [`ShapeType`](../shapetype) är tillåtna, förutom alla typer av linjer: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en figur. Skrivskyddad [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en figur. Observera: kan returnera null för vissa typer av figurer som saknar 3D-egenskaper. Skrivskyddad [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Trimma slut [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Trimma start [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-avgränsad identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte behandlas som en beständig unik nyckel. Skrivskyddad UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Returnerar eller anger ljudvolymen. Läs/skriv [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger figurens bredd, mätt i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för figurens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för figurens övre vänstra hörn, mätt i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar positionen för en figur i z-ordningen. Shapes[0] returnerar figuren längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar figuren längst fram i z-ordningen. Skrivskyddad Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till ett nytt platshållare om det inte finns och sätter platshållarens egenskaper till en angiven. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Skapar och returnerar en array av figurens element. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarfigur (figur från layouten och/eller mästarbilden som den aktuella figuren är ärvd från). Null returneras om den aktuella figuren inte är ärvd. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Returnerar en kopia av geometriformens bana. Koordinaterna är relativa till figurens övre vänstra hörn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar figurens miniatyrbild. ShapeThumbnailBounds.Shape används som standard för miniatyrbildens gräns. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar figurens miniatyrbild. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar de visuella gränserna för figuren beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna figur inte är ett platshållare. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Uppdaterar figurens geometri från [`IGeometryPath`](../igeometrypath)-objektet. Koordinaterna måste vara relativa till figurens övre vänstra hörn. Ändrar figurens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Uppdaterar figurens geometri från en array av [`IGeometryPath`](../igeometrypath). Koordinaterna måste vara relativa till figurens övre vänstra hörn. Ändrar figurens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar figurens innehåll som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar figurens innehåll som en SVG-fil. |

### Se även

* klass [PictureFrame](../pictureframe)
* gränssnitt [IVideoFrame](../ivideoframe)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->