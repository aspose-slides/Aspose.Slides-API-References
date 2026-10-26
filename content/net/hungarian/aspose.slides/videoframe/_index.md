---
title: VideoFrame
second_title: Aspose.Sildes .NET API-referencia
description: Egy dián lévő videoklipet reprezentál.
type: docs
weight: 11720
url: /hu/aspose.slides/videoframe/
---
## VideoFrame osztály

Egy videóklipet képvisel egy dián.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | A forma állítási értékeinek gyűjteményét adja vissza. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | A formához tartozó alternatív szöveget adja vissza vagy állítja be. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | A formához tartozó alternatív szöveg címét adja vissza vagy állítja be. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | A videókerethez tartozó zárt feliratok gyűjteményét adja meg. Ez a tulajdonság csak olvasható, és egy [`ICaptionsCollection`](../icaptionscollection) objektumot ad vissza, amely az összes feliratsávot tartalmazza. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | A forma csatlakozási pontjainak számát adja vissza. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | A forma egyéni adatait adja vissza. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Az EffectFormat objektumot adja vissza, amely a forma alkalmazott képpont effektusait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyek nem rendelkeznek effektus tulajdonságokkal, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Beágyazott videóobjektumot ad vissza vagy állít be. Olvasás/írás [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | A FillFormat objektumot adja vissza, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyek nem rendelkeznek kitöltési tulajdonságokkal, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | A forma keret tulajdonságait adja vissza vagy állítja be. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Meghatározza, hogy a videó teljes képernyő módban jelenik-e meg. Olvasás/írás Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | A forma magasságát adja meg vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Meghatározza, hogy a VideoFrame rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Az egérkattintáshoz definiált hiperhivatkozást adja vissza vagy állítja be. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | A hiperhivatkozás kezelőt adja vissza. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Az egér fölé mozgatásához definiált hiperhivatkozást adja vissza vagy állítja be. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Meghatározza, hogy a PictureFrame Cameo objektum-e vagy sem. Csak olvasható Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | A ‘Mark as decorative’ opciót adja meg vagy állítja be. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a forma csoportosítva van-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | A LineFormat objektumot adja vissza, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyek nem rendelkeznek vonal tulajdonságokkal, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | A VideoFrame-hez kapcsolódó videofájl nevét adja vissza vagy állítja be. Olvasás/írás String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | A forma nevét adja vissza vagy állítja be. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Egy diára korlátozott egyedi azonosítót ad vissza, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | A szülő GroupShape objektumot adja vissza, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | A picture frame-hez tartozó PictureFillFormat objektumot adja vissza. Csak olvasható [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | A forma zárolásait adja vissza. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | A forma helyfoglalóját adja vissza. Null értéket ad vissza, ha a formának nincs helyfoglalója. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Meghatározza, hogy a videó ciklikus-e. Olvasás/írás Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | A videó lejátszási módját adja vissza vagy állítja be. Olvasás/írás [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | A dia szülő prezentációját adja vissza. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | A nyers forma keret tulajdonságait adja vissza vagy állítja be. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | A picture frame magasságának (az eredeti kép méretéhez viszonyítva) méretarányát adja vissza vagy állítja be. Az 1,0 érték 100 %-nak felel meg. Olvasás/írás Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | A picture frame szélességének (az eredeti kép méretéhez viszonyítva) méretarányát adja vissza vagy állítja be. Az 1,0 érték 100 %-nak felel meg. Olvasás/írás Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Meghatározza, hogy a videó automatikusan újrainduljon, amint a lejátszás befejeződött. Olvasás/írás Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | A megadott forma Z-tengely körül történő elfordulásának fokszámát adja vissza vagy állítja be. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányú forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | A forma zárolásait adja vissza. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | A forma stílusobjektumát adja vissza. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | A PictureFrame AutoShape típusát adja vissza vagy állítja be. A(z) [`ShapeType`](../shapetype) halmaz minden eleme engedélyezett, kivéve a különféle vonalakat: |
| [Slide](../../aspose.slides/shape/slide) { get; } | A forma szülő diaját adja vissza. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | A ThreeDFormat objektumot adja vissza, amely a forma 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyek nem rendelkeznek 3D tulajdonságokkal, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Vágás vége [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Vágás kezdete [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Egy belső, prezentáció-szintű azonosítót ad vissza, amelyet kiegészítők vagy egyéb kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan is át lehet állítani, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | A hangerejét adja vissza vagy állítja be. Olvasás/írás [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | A forma szélességét adja meg vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | A forma bal-felső sarkának x-koordinátáját adja meg vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | A forma bal-felső sarkának y-koordinátáját adja meg vagy állítja be, pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | A forma z-rendben betöltött pozícióját adja vissza. A Shapes[0] a z-rend leghátsó elemét, a Shapes[Shapes.Count - 1] pedig a legelülső elemét adja vissza. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyfoglalót ad hozzá, ha nincs, és a helyfoglaló tulajdonságait beállítja egy megadottra. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Alap helyfoglaló formát ad vissza (az elrendezésről és/vagy mesterdiról származó forma, amelyből a jelenlegi forma örökölt). Null értéket ad vissza, ha a jelenlegi forma nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | A geometriai forma útvonalának másolatát adja vissza. A koordináták a forma bal felső sarkához viszonyítva vannak. |
| [GetImage](../../aspose.slides/shape/getimage)() | A forma miniatűrjét adja vissza. Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma miniatűr korlát típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | A forma miniatűrjét adja vissza. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | A forma megjelenített tartalmából számított vizuális határokat adja vissza. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem helyfoglaló. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | A forma geometriáját frissíti a [`IGeometryPath`](../igeometrypath) objektumtól. A koordinátáknak a forma bal felső sarkához kell viszonyulniuk. A forma típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra változtatja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | A forma geometriáját frissíti a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak a forma bal felső sarkához kell viszonyulniuk. A forma típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra változtatja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [PictureFrame](../pictureframe)
* interfész [IVideoFrame](../ivideoframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->