---
title: AudioFrame
second_title: Aspose.Sildes .NET API Referenciája
description: Egy dián lévő audio klipet ábrázol.
type: docs
weight: 850
url: /hu/aspose.slides/audioframe/
---
## AudioFrame osztály

Egy diára helyezett audio klipet ábrázol.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaadja a shape beállítási értékeinek gyűjteményét. Csak-olvasás [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a shape-hez társított alternatív szöveget. Olvasható-írható String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a shape-hez tartozó alternatív szöveg címét. Olvasható-írható String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Visszaadja vagy beállítja az utolsó sáv indexét. Olvasható-írható Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Visszaadja vagy beállítja az utolsó sáv időpontját. Olvasható-írható Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Visszaadja vagy beállítja a kezdő sáv indexét. Olvasható-írható Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Visszaadja vagy beállítja a kezdő sáv időpontját. Olvasható-írható Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg a shape fekete-fehér megjelenítési módban. Olvasható-írható [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | A hangkerethez tartozó zárt feliratok gyűjteményét adja vissza. Ez a tulajdonság csak-olvasás, és egy [`ICaptionsCollection`](../icaptionscollection) objektumot ad vissza, amely az összes feliratsávot tartalmazza. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a shape csatlakozási pontjainak számát. Csak-olvasás Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a shape egyedi adatait. Csak-olvasás [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixeleffektusokat tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak-olvasás [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Megállapítja, hogy a hang be van-ágyazva a prezentációba. Csak-olvasás Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Visszaadja vagy beállítja a beágyazott audio objektumot. Olvasható-írható [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Megadja a média kezdeti fade-in időtartamát ezredmásodpercben. Olvasható-írható Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Megadja a média befejező fade-out időtartamát ezredmásodpercben. Olvasható-írható Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a shape kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak-olvasás [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a shape keret tulajdonságait. Olvasható-írható [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja a shape magasságát pontban mérve. Olvasható-írható Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy a shape rejtett-e. Olvasható-írható Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Megállapítja, hogy az AudioFrame rejtett-e. Olvasható-írható Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperlinket. Olvasható-írható [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperlink kezelőt. Csak-olvasás [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé húzásra definiált hiperlinket. Olvasható-írható [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Megállapítja, hogy a PictureFrame Cameo objektum-e vagy sem. Csak-olvasás Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a „Megjelölés díszítőként” opciót. Olvasható-írható Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy a shape csoportosított-e. Csak-olvasás Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy a shape TextHolder_PPT-e. Csak-olvasás Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak-olvasás [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Visszaadja vagy beállítja az AudioFrame-hez kapcsolt audiofájl nevét. Olvasható-írható String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a shape nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasható-írható String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára vonatkozó egyedi azonosítót, amely a shape élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a shape-re a dokumentum bármely pontjáról. Csak-olvasás UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Ellenkező esetben null értéket ad vissza. Csak-olvasás [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Visszaadja a képkeret PictureFillFormat objektumát. Csak-olvasás [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Visszaadja a shape zárolásait. Csak-olvasás [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a shape helyfoglalóját. Null értéket ad vissza, ha a shape-nek nincs helyfoglalója. Csak-olvasás [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Megállapítja, hogy az audio a diákon keresztül játszódik-e. Olvasható-írható Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Megállapítja, hogy az audio ismétlődik-e. Olvasható-írható Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Visszaadja vagy beállítja az audio lejátszási módot. Olvasható-írható [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak-olvasás [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a shape nyers keret tulajdonságait. Olvasható-írható [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel szemben) arányát. Az 1.0 érték 100%-nak felel meg. Olvasható-írható Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel szemben) arányát. Az 1.0 érték 100%-nak felel meg. Olvasható-írható Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Megállapítja, hogy az audio automatikusan visszatekerődjön-e a lejátszás után. Olvasható-írható Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott shape Z-tengely körüli forgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányt. Olvasható-írható Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Visszaadja a shape zárolásait. Csak-olvasás [`IPictureFrameLock`](../ipictureframelock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja a shape stílusobjektumát. Csak-olvasás [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Visszaadja vagy beállítja a PictureFrame AutoShape típusát. A [`ShapeType`](../shapetype) halmaz minden eleme engedélyezett, kivéve a különféle vonalakat: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a shape szülő diáját. Csak-olvasás [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a shape 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak-olvasás [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Olvasható-írható Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Olvasható-írható Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, a prezentációra vonatkozó azonosítót, amelyet kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozott módon felülírhatja, nem tekinthető állandó egyedi kulcsnak. Csak-olvasás UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Visszaadja vagy beállítja az audio hangerőt. Olvasható-írható [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Visszaadja vagy beállítja az audio hangerőt százalékban. Olvasható-írható Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja a shape szélességét pontban mérve. Olvasható-írható Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja a shape bal-felső sarkának x-koordinátáját pontban mérve. Olvasható-írható Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja a shape bal-felső sarkának y-koordinátáját pontban mérve. Olvasható-írható Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a shape z-rendiségben betöltött pozícióját. A Shapes[0] a z-rendiség hátulján lévő shape-t adja vissza, a Shapes[Shapes.Count - 1] pedig az előre lévő shape-t. Csak-olvasás Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyfoglalót ad hozzá, ha nincs, és a megadott helyfoglaló tulajdonságait beállítja. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a shape elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyfoglaló shape-t (a layout vagy a mesterdia shape-jét, amelyből a jelenlegi shape örökölt). Null értéket ad vissza, ha a shape nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai shape útvonalának másolatát. A koordináták a shape bal-felső sarkához viszonyítva relatívak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a shape bélyegképét. Alapértelmezésként a ShapeThumbnailBounds.Shape shape bélyegkép-határok típusa használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a shape bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Visszaadja a shape vizuális határait, amelyet a renderelt tartalom alapján számol. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a shape nem helyfoglaló. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti a shape geometriáját a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak a shape bal-felső sarkához kell viszonyulniuk. A shape típusát ([`ShapeType`](../geometryshape/shapetype)) Custom típusra módosítja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti a shape geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak a shape bal-felső sarkához kell viszonyulniuk. A shape típusát ([`ShapeType`](../geometryshape/shapetype)) Custom típusra módosítja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A shape tartalmát SVG fájlként menti. |

### Példák

A következő példák bemutatják, hogyan lehet módosítani az Audio lejátszási beállításokat.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Lekéri az AudioFrame alakzatot
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Beállítja a lejátszási módot kattintásra
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Beállítja a hangerőt alacsonyra
    audioFrame.Volume = AudioVolumeMode.Low;
    // Beállítja, hogy a hang a diákon keresztül játsszon
    audioFrame.PlayAcrossSlides = true;
    // Kikapcsolja a hang ismétlését
    audioFrame.PlayLoopMode = false;
    // Elrejti az AudioFrame-et a diavetítés során
    audioFrame.HideAtShowing = true;
    // Visszatekeri a hangot a kezdőpontra a lejátszás után
    audioFrame.RewindAudio = true;
    // Elmenti a PowerPoint fájlt a lemezre
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* osztály [PictureFrame](../pictureframe)
* interfész [IAudioFrame](../iaudioframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->