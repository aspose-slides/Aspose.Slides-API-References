---
title: VideoFrame
second_title: Aspose.Sildes .NET API referencia
description: Egy videóklipet képvisel a dián.
type: docs
weight: 11700
url: /hu/aspose.slides/videoframe/
---
## VideoFrame osztály

Egy videóklipet képvisel a dián.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaad egy gyűjteményt a forma beállítási értékeiről. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a formához társított alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a formához társított alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Visszaadja a zárt feliratok gyűjteményét, amelyek a videókerethez tartoznak. Ez a tulajdonság csak olvasható, és egy [`ICaptionsCollection`](../icaptionscollection)-t ad vissza, amely az összes feliratsávot tartalmazza. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a formára alkalmazott pixel hatásokat tartalmazza. Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs effekt tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Visszaadja vagy beállítja a beágyazott videó objektumot. Olvasás/írás [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Megállapítja, hogy a videó teljes képernyős módban jelenik-e meg. Olvasás/írás Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja a forma magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Megállapítja, hogy a VideoFrame rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra meghatározott hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatására definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Megállapítja, hogy a PictureFrame Cameo objektum-e vagy sem. Csak olvasható Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy a forma csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Visszaadja vagy beállítja a VideoFrame-hez linkelt videófájl nevét. Olvasás/írás String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy forma nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaadja a diára korlátozott egyedi azonosítót, amely a forma teljes élettartama alatt állandó marad, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Visszaadja a PictureFillFormat objektumot egy képkerethez. Csak olvasható [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helyőrzőjét. Null értéket ad vissza, ha a formának nincs helyőrzője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Megállapítja, hogy a videó ismétlődik-e. Olvasás/írás Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Visszaadja vagy beállítja a videó lejátszási módját. Olvasás/írás [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a diát tartalmazó prezentáció szülőjét. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Visszaadja vagy beállítja a képkeret magasságának (az eredeti kép méretéhez viszonyítva) méretarányát. Az 1,0 érték 100%-nak felel meg. Olvasás/írás Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Visszaadja vagy beállítja a képkeret szélességének (az eredeti kép méretéhez viszonyítva) méretarányát. Az 1,0 érték 100%-nak felel meg. Olvasás/írás Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Megállapítja, hogy a videó automatikusan visszatekerődik-e a kezdetre, amint a film lejátszása befejeződik. Olvasás/írás Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott forma Z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást, a negatív érték az ellenkező irányú forgást jelzi. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja a forma stílusobjektumát. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Visszaadja vagy beállítja a PictureFrame AutoShape típusát. A [`ShapeType`](../shapetype) halmaz minden eleme megengedett, kivéve mindenféle vonal. |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülődiaját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Vágás vége [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Vágás kezdete [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, a prezentációra korlátozott azonosítót, amelyet kiegészítők vagy egyéb kód használhat. Mivel ezt az értéket a felhasználó vagy programkóddal újra lehet rendelni, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Visszaadja vagy beállítja a hanghangerőt. Olvasás/írás [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja a forma szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja a forma bal felső sarkának x-koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja a forma bal felső sarkának y-koordinátáját pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a forma z-rendben betöltött pozícióját. A Shapes[0] a z-rend hátsó részén lévő formát adja vissza, a Shapes[Shapes.Count - 1] pedig az elején lévőt. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait a megadottra állítja. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alaphelyőrző formát (a layout vagy a mester dia formáját, amiből a jelenlegi forma örököl). Null értéket ad vissza, ha a jelenlegi forma nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához relatívak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határoló típusa használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri a forma megjelenített határait, amelyeket a renderelt tartalom alapján számolt. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem helyőrző. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti a forma geometriáját a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük. A forma típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra változtatja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti a forma geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük. A forma típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra változtatja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [PictureFrame](../pictureframe)
* interfész [IVideoFrame](../ivideoframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->