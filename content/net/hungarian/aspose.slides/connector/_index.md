---
title: Connector
second_title: Aspose.Sildes .NET API Referencia
description: Egy csatlakozót képvisel.
type: docs
weight: 2670
url: /hu/aspose.slides/connector/
---
## Connector osztály

Egy csatlakozót reprezentál.

```csharp
public class Connector : GeometryShape, IConnector
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | A shape beállítási értékeinek gyűjteményét adja vissza. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Az alakhoz kapcsolódó alternatív szöveget adja vissza vagy állítja be. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Az alakhoz kapcsolódó alternatív szöveg címét adja vissza vagy állítja be. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogy a shape hogyan jelenik meg fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | A shape kapcsolódási pontjainak számát adja vissza. Csak olvasható Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | A csatlakozó zárjait adja vissza. Csak olvasható [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | A shape egyéni adatait adja vissza. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixelhatásokat tartalmazza. Megjegyzés: bizonyos shape típusoknál, amelyeknek nincs hatás tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | A csatlakozó végét a megadott shape-hez csatolja vagy állítja be. Olvasás/írás [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | A vég shape kapcsolódási pont indexét adja vissza vagy állítja be. Olvasás/írás UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a shape kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape típusoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | A shape keret tulajdonságait adja vissza vagy állítja be. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | A shape magasságát adja vissza vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy a shape rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | A egérkattintásra definiált hiperhivatkozást adja vissza vagy állítja be. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | A hiperhivatkozás-kezelőt adja vissza. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Az egér fölé húzásra definiált hiperhivatkozást adja vissza vagy állítja be. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Az „Megjelölés dekoratívként” opciót adja vissza vagy állítja be. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy a shape csoportosítva van-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy a shape TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape típusoknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | A shape nevét adja vissza vagy állítja be. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára jellemző egyedi azonosítót, amely a shape életciklusa során állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a shape-re a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a shape helyőrzőjét. Ha a shape-nek nincs helyőrzője, null értéket ad vissza. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | A shape alapkeret tulajdonságait adja vissza vagy állítja be. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | A megadott shape z-tengely körüli forgatásának fokszámát adja vissza vagy állítja be. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Visszaadja a shape zárjait. Csak olvasható [`IConnectorLock`](../iconnectorlock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja a shape stílusobjektumát. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Az AutoShape típusát adja vissza vagy állítja be. Olvasás/írás [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a shape szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | A csatlakozó kezdetét a megadott shape-hez csatolja vagy állítja be. Olvasás/írás [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | A kezdő shape kapcsolódási pont indexét adja vissza vagy állítja be. Olvasás/írás UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a shape 3D hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos shape típusoknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra jellemző azonosítót, amelyet bővítmények vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozott módon is át lehet rendelni, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | A shape szélességét adja vissza vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | A shape bal-felső sarkának x koordinátáját adja vissza vagy állítja be, pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | A shape bal-felső sarkának y koordinátáját adja vissza vagy állítja be, pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a shape pozícióját a z-sorrendben. A Shapes[0] a z-sorrend hátulját, a Shapes[Shapes.Count - 1] pedig a frontját adja vissza. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait a megadottra állítja. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a shape elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző shape-et (a layout vagy a mesterdiáról származó shape, amelyből az aktuális shape örököl). Null értéket ad vissza, ha az aktuális shape nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai shape útvonalának másolatát. A koordináták a shape bal-felső sarkához képest relatívak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a shape miniatűrjét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape shape miniatűr határoló típusa használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a shape miniatűrjét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | A shape megjelenített tartalma alapján kiszámított vizuális határolókat adja vissza. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a shape nem helyőrző. |
| [Reroute](../../aspose.slides/connector/reroute)() | Átirányítja a csatlakozót, hogy a csatlakoztatott shape-ek között a lehető legrövidebb útvonalat vegye. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | A shape geometriáját frissíti a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak a shape bal-felső sarkához képest relatívnak kell lenniük. A shape típusát ([`ShapeType`](../geometryshape/shapetype)) egyéni típusra módosítja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | A shape geometriáját frissíti a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak a shape bal-felső sarkához képest relatívnak kell lenniük. A shape típusát ([`ShapeType`](../geometryshape/shapetype)) egyéni típusra módosítja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GeometryShape](../geometryshape)
* interfész [IConnector](../iconnector)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->