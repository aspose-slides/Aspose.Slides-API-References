---
title: Connector
second_title: Aspose.Sildes .NET API Referenciája
description: Egy kapcsolót ábrázol.
type: docs
weight: 2650
url: /hu/aspose.slides/connector/
---
## Connector osztály

Kapcsolót ábrázol.

```csharp
public class Connector : GeometryShape, IConnector
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaad egy gyűjteményt a shape igazítási értékeiről. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a shape-hez társított alternatív szöveget. Olvasható/írható String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a shape-hez társított alternatív szöveg címét. Olvasható/írható String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A property meghatározza, hogyan jelenik meg a shape fekete-fehér megjelenítési módban. Olvasható/írható [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a shape csatlakozási helyeinek számát. Csak olvasható Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Visszaadja a connector zárjait. Csak olvasható [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a shape egyéni adatát. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely pixel effektusokat tartalmaz, amelyeket egy shape-re alkalmaztak. Megjegyzés: bizonyos shape típusok esetén, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Visszaadja vagy beállítja a shape-et, amelyhez a connector végét csatlakoztatni kell. Olvasható/írható [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Visszaadja vagy beállítja a vég shape csatlakozási helyének indexét. Olvasható/írható UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a shape kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape típusok esetén, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a shape keret tulajdonságait. Olvasható/írható [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja a shape magasságát pontban mérve. Olvasható/írható Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a shape rejtett-e. Olvasható/írható Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasható/írható [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé húzásra definiált hiperhivatkozást. Olvasható/írható [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Beállítja vagy lekéri a „Mark as decorative” opciót. Olvasható/írható Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a shape csoportosítva van-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a shape TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape típusok esetén, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy shape nevét. Nem lehet null. Ha szükséges, használjon üres karakterláncot. Olvasható/írható String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára vonatkozó egyedi azonosítót, amely a shape teljes élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a shape-re a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Ellenkező esetben null-t ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a shape helyfoglalót. Ha a shape-nek nincs helyfoglalója, null-t ad vissza. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers shape keret tulajdonságait. Olvasható/írható [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott shape z-tengely körüli forgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást jelzi. Olvasható/írható Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Visszaadja a shape zárjait. Csak olvasható [`IConnectorLock`](../iconnectorlock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja a shape stílus objektumát. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Visszaadja vagy beállítja az AutoShape típusát. Olvasható/írható [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a shape szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Visszaadja vagy beállítja a shape-et, amelyhez a connector elejét csatlakoztatni kell. Olvasható/írható [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Visszaadja vagy beállítja a kezdő shape csatlakozási helyének indexét. Olvasható/írható UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a shape 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos shape típusok esetén, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra vonatkozó azonosítót, amelyet kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozottan is újra lehet rendelni, nem szabad tartós egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja a shape szélességét pontban mérve. Olvasható/írható Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja a shape bal-felső sarkának x-koordinátáját pontban mérve. Olvasható/írható Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja a shape bal-felső sarkának y-koordinátáját pontban mérve. Olvasható/írható Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy shape pozícióját a z-rendben. A Shapes[0] a z-rend hátsó végén lévő shape-et adja vissza, a Shapes[Shapes.Count - 1] pedig az előre lévő shape-et. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Hozzáad egy új helyfoglalót, ha nincs, és beállítja a helyfoglaló tulajdonságait egy megadottra. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a shape elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyfoglaló shape-et (a layoutból és/vagy a mesterdiából származó shape, amelyből a jelenlegi shape örököl). Null értéket ad vissza, ha a jelenlegi shape nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometria shape útvonalának másolatát. A koordináták a shape bal-felső sarkához viszonyítva vannak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a shape miniatűrjét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape shape miniatűr korlát típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a shape miniatűrjét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Visszaadja a shape vizuális határait, amelyeket a megjelenített tartalom alapján számoltak. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a shape nem helyfoglaló. |
| [Reroute](../../aspose.slides/connector/reroute)() | Átirányítja a connectort, hogy a legrövidebb lehetséges útvonalat vegye a shape-ek között, amelyeket összeköt. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti a shape geometriáját a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak a shape bal-felső sarkához kell viszonyulniuk. A shape típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra módosítja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti a shape geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak a shape bal-felső sarkához kell viszonyulniuk. A shape típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra módosítja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GeometryShape](../geometryshape)
* interfész [IConnector](../iconnector)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->