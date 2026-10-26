---
title: AudioFrame
second_title: Aspose.Sildes .NET API-referencia
description: Egy dián lévő hangkivágat képvisel.
type: docs
weight: 870
url: /hu/aspose.slides/audioframe/
---
## AudioFrame osztály

Egy dia hangkivágat képvisel.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | A forma állítási értékeinek gyűjteményét adja vissza. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | A formahoz kapcsolódó alternatív szöveget adja vissza vagy állítja be. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | A formahoz kapcsolódó alternatív szöveg címét adja vissza vagy állítja be. Olvasás/írás String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Az utolsó sáv indexét adja vissza vagy állítja be. Olvasás/írás Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Az utolsó sáv időt adja vissza vagy állítja be. Olvasás/írás Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | A kezdő sáv indexét adja vissza vagy állítja be. Olvasás/írás Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | A kezdő sáv időt adja vissza vagy állítja be. Olvasás/írás Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Meghatározza, hogy a forma fekete-fehér megjelenítési módban hogyan lesz megjelenítve. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Visszaadja a hangkerethez tartozó zárt feliratok gyűjteményét. Ez a tulajdonság csak olvasható, és egy [`ICaptionsCollection`](../icaptionscollection)-t ad vissza, amely minden felirat sávot tartalmaz. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | A forma csatlakozási pontjainak számát adja vissza. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | A forma egyéni adatait adja vissza. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a forma pixel-effekteit tartalmazza. Megjegyzés: bizonyos formatípusoknál, amelyeknek nincs effektus-tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Megállapítja, hogy a hang be van-e ágyazva a bemutatóba. Csak olvasható Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Beágyazott hangobjektumot ad vissza vagy állít be. Olvasás/írás [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Megadja a média kezdeti fokozatos megjelenésének időtartamát ezredmásodpercben. Olvasás/írás Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Megadja a média befejező fokozatos eltűnésének időtartamát ezredmásodpercben. Olvasás/írás Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a forma kitöltésének formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos formatípusoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | A forma keretének tulajdonságait adja vissza vagy állítja be. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | A forma magasságát adja vissza vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Meghatározza, hogy egy AudioFrame rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy állítja be az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | A hiperhivatkozáskezelőt adja vissza. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy állítja be az egérmutató fölé definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Megállapítja, hogy a PictureFrame Cameo objektum-e vagy sem. Csak olvasható Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | A „Megjelölés díszítőként” opciót adja vissza vagy állítja be. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy a forma csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos formatípusoknál, amelyeknek nincs vonal-tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Visszaadja vagy állítja be a hangfájl nevét, amely az AudioFrame-hez van csatolva. Olvasás/írás String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy állítja be a forma nevét. Nem lehet null. Ha szükséges, üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy dia-szintű egyedi azonosítót, amely a forma életciklusáig állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Különben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Visszaadja a PictureFillFormat objektumot egy képkerethez. Csak olvasható [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helykitöltőjét. Ha a formának nincs helykitöltője, null értéket ad vissza. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Meghatározza, hogy a hang a diákon keresztül lejátszódik-e. Olvasás/írás Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Meghatározza, hogy a hang ismétlődik-e. Olvasás/írás Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Visszaadja vagy állítja be a hang lejátszási módját. Olvasás/írás [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | A dia szülő bemutatóját adja vissza. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy állítja be a nyers forma keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Visszaadja vagy állítja be a képkeret magasságának (az eredeti kép méretéhez viszonyítva) méretezését. Az 1,0 érték 100 %-nak felel meg. Olvasás/írás Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Visszaadja vagy állítja be a képkeret szélességének (az eredeti kép méretéhez viszonyítva) méretezését. Az 1,0 érték 100 %-nak felel meg. Olvasás/írás Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Meghatározza, hogy a hang automatikusan újraindul-e a lejátszás után. Olvasás/írás Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy állítja be a megadott forma z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató szerinti, a negatív az ellenkező irányú forgást jelzi. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | A forma zárolásait adja vissza. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | A forma stílusobjektumát adja vissza. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Visszaadja vagy állítja be a PictureFrame AutoShape típusát. Az [`ShapeType`](../shapetype) halmaz minden eleme megengedett, kivéve a különböző vonalakat: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D-effektus-tulajdonságait tartalmazza. Megjegyzés: bizonyos formatípusoknál, amelyeknek nincs 3D-tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Megadja a lejátszás során a média végéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Megadja a lejátszás során a média elejéről eltávolítandó időtartamot ezredmásodpercben. Olvasás/írás Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Egy belső, bemutató-szintű azonosítót ad vissza, amelyet kiegészítők vagy más kód használhat. Mivel ez az érték felhasználó vagy program által felülírható, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Visszaadja vagy állítja be a hang hangerősségét. Olvasás/írás [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Visszaadja vagy állítja be a hang hangerősségét százalékban. Olvasás/írás Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | A forma szélességét adja vissza vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | A forma bal-felső sarkának x-koordinátáját adja vissza vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | A forma bal-felső sarkának y-koordinátáját adja vissza vagy állítja be, pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a forma pozícióját a z-rendben. A Shapes[0] a z-rend hátulját, a Shapes[Shapes.Count - 1] a frontját adja vissza. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helykitöltőt ad hozzá, ha nincs, és beállítja a helykitöltő tulajdonságait a megadottra. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alaphelykitöltő alakzatot (az elrendezés vagy a mester-dia alakzata, amelyből a jelenlegi alakzat származik). Ha a jelenlegi alakzat nem örökölt, null értéket ad vissza. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták a forma bal-felső sarkához viszonyítva relatívak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegkép-típus használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | A forma megjelenített tartalma alapján kiszámított vizuális határokat adja vissza. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiálja, hogy ez a forma nem helykitöltő. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti a forma geometriáját a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak a forma bal-felső sarkához relatívnak kell lenniük. A forma típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra változtatja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti a forma geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak a forma bal-felső sarkához relatívnak kell lenniük. A forma típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra változtatja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Példák

Az alábbi példák azt mutatják, hogyan változtathatók a hang lejátszási beállításai.

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
    // Visszatekeri a hangot a lejátszás után a kezdőpontra
    audioFrame.RewindAudio = true;
    // Mentse a PowerPoint fájlt a lemezre
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* osztály [PictureFrame](../pictureframe)
* interfész [IAudioFrame](../iaudioframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->