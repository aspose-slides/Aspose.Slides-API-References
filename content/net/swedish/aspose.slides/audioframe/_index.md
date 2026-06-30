---
title: AudioFrame
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett ljudklipp på en bild.
type: docs
weight: 850
url: /sv/aspose.slides/audioframe/
---
## AudioFrame-klass

Representerar ett ljudklipp på en bild.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Returnerar en samling av figurens justeringsvärden. Skrivskyddad [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returnerar eller anger den alternativa text som är associerad med en figur. Läs/skriv String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returnerar eller anger titeln för den alternativa texten som är associerad med en figur. Läs/skriv String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Returnerar eller anger ett sista spårindex. Läs/skriv Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Returnerar eller anger en sista spårtid. Läs/skriv Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Returnerar eller anger ett startspårindex. Läs/skriv Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Returnerar eller anger en startspårtid. Läs/skriv Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Egendom specificerar hur en figur renderas i svart-vit visningsläge. Läs/skriv [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Hämtar samlingen av slutna bildtexter som är associerade med ljudramen. Denna egenskap är skrivskyddad och returnerar ett [`ICaptionsCollection`](../icaptionscollection) som innehåller alla bildtextspår. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returnerar antalet anslutningspunkter på figuren. Skrivskyddad Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returnerar figurens anpassade data. Skrivskyddad [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returnerar EffectFormat-objektet som innehåller pixel-effekter som tillämpas på en figur. Obs: kan returnera null för vissa figurer som inte har effekt-egenskaper. Skrivskyddad [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Anger om ett ljud är inbäddat i en presentation. Skrivskyddad Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Returnerar eller anger inbäddat ljudobjekt. Läs/skriv [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Anger tidslängden för den initiala tonings-in-effekten i millisekunder. Läs/skriv Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Anger tidslängden för den avslutande tonings-ut-effekten i millisekunder. Läs/skriv Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returnerar FillFormat-objektet som innehåller fyllnings-egenskaper för en figur. Obs: kan returnera null för vissa figurer som inte har fyllnings-egenskaper. Skrivskyddad [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returnerar eller anger figurens ram-egenskaper. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Hämtar eller anger figurens höjd i punkter. Läs/skriv Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Anger om figuren är dold. Läs/skriv Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Anger om ett AudioFrame är dolt. Läs/skriv Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returnerar hyperlänk-hanteraren. Skrivskyddad [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returnerar eller anger hyperlänken som definierats för mus-över. Läs/skriv [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Anger om PictureFrame är ett Cameo-objekt eller inte. Skrivskyddad Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Hämtar eller anger alternativet 'Mark as decorative'. Läs/skriv Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Anger om figuren är grupperad. Skrivskyddad Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Anger om figuren är TextHolder_PPT. Skrivskyddad Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returnerar LineFormat-objektet som innehåller linje-formaterings-egenskaper för en figur. Obs: kan returnera null för vissa figurer som inte har linje-egenskaper. Skrivskyddad [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Returnerar eller anger namn på en ljudfil som är länkad till ett AudioFrame. Läs/skriv String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returnerar eller anger namn på en figur. Måste vara icke-null. Använd tom sträng om så behövs. Läs/skriv String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Returnerar ett bild-specifikt unikt identifierare som förblir konstant under figurens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till figuren var som helst i dokumentet. Skrivskyddad UInt32. Se även [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returnerar överordnad GroupShape-objekt om figuren är grupperad. Annars null. Skrivskyddad [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Returnerar PictureFillFormat-objektet för en bildram. Skrivskyddad [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Returnerar figurens lås. Skrivskyddad [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returnerar platshållaren för en figur. Returnerar null om figuren saknar platshållare. Skrivskyddad [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Anger om ljud spelas över bildspel. Läs/skriv Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Anger om ett ljud ska loopas. Läs/skriv Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Returnerar eller anger ljudets uppspelningsläge. Läs/skriv [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returnerar den överordnade presentationen för en bild. Skrivskyddad [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returnerar eller anger de råa figurram-egenskaperna. Läs/skriv [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Returnerar eller anger skalan för höjd (i förhållande till originalbildens storlek) för bildramen. Värde 1,0 motsvarar 100 %. Läs/skriv Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Returnerar eller anger skalan för bredd (i förhållande till originalbildens storlek) för bildramen. Värde 1,0 motsvarar 100 %. Läs/skriv Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Anger om ljud automatiskt spolas tillbaka till början efter uppspelning. Läs/skriv Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returnerar eller anger antalet grader som den angivna figuren roteras runt z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Returnerar figurens lås. Skrivskyddad [`IPictureFrameLock`](../ipictureframelock). (2 egenskaper) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Returnerar figurens stil-objekt. Skrivskyddad [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Returnerar eller anger AutoShape-typen för en PictureFrame. Alla objekt i mängden [`ShapeType`](../shapetype) är tillåtna, förutom alla typer av linjer: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returnerar den överordnade bilden för en figur. Skrivskyddad [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returnerar ThreeDFormat-objektet som innehåller 3D-effekt-egenskaper för en figur. Obs: kan returnera null för vissa figurer som saknar 3D-egenskaper. Skrivskyddad [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Anger tidslängden som ska tas bort från media-slutet under uppspelning, i millisekunder. Läs/skriv Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Anger tidslängden som ska tas bort från media-början under uppspelning, i millisekunder. Läs/skriv Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Returnerar en intern, presentation-specifik identifierare avsedd för add-ins eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel. Skrivskyddad UInt32. Se även [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Returnerar eller anger ljudvolymen. Läs/skriv [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Returnerar eller anger ljudvolymen i procent. Läs/skriv Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Hämtar eller anger figurens bredd i punkter. Läs/skriv Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Hämtar eller anger x-koordinaten för figurens övre vänstra hörn i punkter. Läs/skriv Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Hämtar eller anger y-koordinaten för figurens övre vänstra hörn i punkter. Läs/skriv Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returnerar figurens position i z-ordningen. Shapes[0] returnerar figuren längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar figuren längst fram. Skrivskyddad Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en angiven. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Skapar och returnerar en array av figurens element. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returnerar en grundläggande platshållarfigur (figur från layouten och/eller huvudbilden som den nuvarande figuren ärvs från). Null returneras om den nuvarande figuren inte ärvs. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Returnerar en kopia av geometrins bana för geometrifiguren. Koordinaterna är relativa till figurens övre vänstra hörn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Returnerar figurens miniatyrbild. ShapeThumbnailBounds.Shape-typ används som standard. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Returnerar figurens miniatyrbild. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Hämtar figurens visuella gränser beräknade från dess renderade innehåll. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definierar att denna figur inte är en platshållare. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Uppdaterar figurens geometri från [`IGeometryPath`](../igeometrypath)-objektet. Koordinaterna måste vara relativa till figurens övre vänstra hörn. Ändrar figurens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Uppdaterar figurens geometri från en array av [`IGeometryPath`](../igeometrypath). Koordinaterna måste vara relativa till figurens övre vänstra hörn. Ändrar figurens typ ([`ShapeType`](../geometryshape/shapetype)) till Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Sparar figurens innehåll som en SVG-fil. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Sparar figurens innehåll som en SVG-fil. |

### Exempel

Följande exempel visar hur du ändrar alternativ för ljuduppspelning.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Hämtar AudioFrame-figuren
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Ställer in uppspelningsläget till att spela vid klick
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Ställer in volymen till låg
    audioFrame.Volume = AudioVolumeMode.Low;
    // Ställer in att ljudet spelas över bilder
    audioFrame.PlayAcrossSlides = true;
    // Inaktiverar upprepning för ljudet
    audioFrame.PlayLoopMode = false;
    // Döljer AudioFrame under bildspelet
    audioFrame.HideAtShowing = true;
    // Spolar tillbaka ljudet till start efter uppspelning
    audioFrame.RewindAudio = true;
    // Sparar PowerPoint-filen till disk
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Se även

* class [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->