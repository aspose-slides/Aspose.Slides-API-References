---
title: VideoFrame
second_title: Aspose.Sildes .NET API referencia
description: Egy dián megjelenő videoklipet képvisel.
type: docs
weight: 11740
url: /hu/aspose.slides/videoframe/
---
## VideoFrame osztály

Represents a video clip on a slide.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaadja a shape beállítási értékeinek gyűjteményét. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a shape-hez kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a shape-hez kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Az ingatlan meghatározza, hogyan jelenik meg egy shape fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Megkapja a video frame-hez kapcsolódó lezárt feliratok gyűjteményét. Ez az ingatlan csak olvasható, és egy [`ICaptionsCollection`](../icaptionscollection)-t ad vissza, amely minden feliratsávot tartalmaz. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az shape-en lévő csatlakozási pontok számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az shape egyedi adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott képpontos effektusokat tartalmazza. Megjegyzés: bizonyos, hatástulajdonságokkal nem rendelkező shape-ok esetén null visszaadása lehetséges. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Visszaadja vagy beállítja a beágyazott videóobjektumot. Olvasás/írás [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a shape kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos, kitöltési tulajdonságokkal nem rendelkező shape-ok esetén null visszaadható. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a shape frame tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Meghatározza, hogy a videó teljes képernyőn jelenik-e meg. Olvasás/írás Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Megkapja vagy beállítja a shape magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a shape rejtett-e. Olvasás/írás Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Meghatározza, hogy a VideoFrame rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozáskezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Meghatározza, hogy a PictureFrame Cameo objektum-e vagy sem. Csak olvasható Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Megkapja vagy beállítja a „Mark as decorative” opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a shape csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a shape TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely az shape vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos, vonaltulajdonságokkal nem rendelkező shape-ok esetén null visszaadható. Csak olvasható [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Visszaadja vagy beállítja egy videófájl nevét, amely a VideoFrame-hez kapcsolódik. Olvasás/írás String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy shape nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozott egyedi azonosítót, amely a shape életciklusa alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára a shape megbízható hivatkozását a dokumentum bármely pontjáról. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Különben null-t ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Visszaadja a PictureFillFormat objektumot egy képkerethez. Csak olvasható [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Visszaadja az shape zárolásait. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja egy shape helykitöltőjét. Null-t ad vissza, ha az shape-nek nincs helykitöltője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Meghatározza, hogy a videó ismétlődik-e. Olvasás/írás Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Visszaadja vagy beállítja a videó lejátszási módját. Olvasás/írás [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a slide szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers shape frame tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Visszaadja vagy beállítja a magasság méretezését (az eredeti kép méretéhez viszonyítva) a képkeretben. Az 1,0 érték 100%-nak felel meg. Olvasás/írás Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Visszaadja vagy beállítja a szélesség méretezését (az eredeti kép méretéhez viszonyítva) a képkeretben. Az 1,0 érték 100%-nak felel meg. Olvasás/írás Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Meghatározza, hogy a videó automatikusan újraindul-e a lejátszás befejezésekor. Olvasás/írás Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott shape Z tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkezőjét. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Visszaadja az shape zárolásait. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja az shape stílusobjektumát. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Visszaadja vagy beállítja az AutoShape típust egy PictureFrame-hez. Az [`ShapeType`](../shapetype) halmaz minden eleme engedélyezett, kivéve mindenféle vonalat: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja az alakzat szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a 3D effektustulajdonságokat tartalmazza az alakzathoz. Megjegyzés: bizonyos, 3D tulajdonságokkal nem rendelkező shape-ok esetén null visszaadható. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Trim end [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Trim start [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy program szerint újra lehet rendelni, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Visszaadja vagy beállítja a hangszintet. Olvasás/írás [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | Visszaadja vagy beállítja a pontos videó hangerőt százalékban. Az érték 0 és 100 közötti százalék. Ezzel a tulajdonsággal pontosabb hangerőértékeket olvashat vagy állíthat be, mint a [`Volume`](./volume) tulajdonságnál elérhető előre definiált szintek. Olvasás/írás Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Megkapja vagy beállítja az alakzat szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Megkapja vagy beállítja az alakzat bal-felső sarkának X koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Megkapja vagy beállítja az alakzat bal-felső sarkának Y koordinátáját pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy shape z-sorrendben elfoglalt pozícióját. A Shapes[0] a z-sorrend hátsó shape-át adja vissza, a Shapes[Shapes.Count - 1] pedig az elejét. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Hozzáad egy új helykitöltőt, ha nincs, és beállítja a helykitöltő tulajdonságait egy megadottra. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja az shape elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helykitöltő alakzatot (az elrendezésből és/vagy minta diáról, ahonnan a jelenlegi shape örököl). Null-t ad vissza, ha a jelenlegi shape nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai shape útvonalának másolatát. A koordináták az shape bal-felső sarkához relatívak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az shape bélyegképét. Alapértelmezésben a ShapeThumbnailBounds.Shape bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az shape bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Megkapja az shape vizuális határait, melyek a megjelenített tartalomból számítódnak. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az shape nem helykitöltő. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti az shape geometriáját a [`IGeometryPath`](../igeometrypath) objektumtól. A koordinátáknak az shape bal-felső sarkához relatívnak kell lenniük. Megváltoztatja az shape típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti az shape geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak az shape bal-felső sarkához relatívnak kell lenniük. Megváltoztatja az shape típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti az shape tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Elmenti az shape tartalmát SVG fájlként. |

### Lásd még

* osztály [PictureFrame](../pictureframe)
* interfész [IVideoFrame](../ivideoframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->