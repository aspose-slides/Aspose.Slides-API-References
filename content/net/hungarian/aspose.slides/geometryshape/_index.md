---
title: GeometryShape
second_title: Aspose.Sildes a .NET API referenciája
description: Az összes geometriai alakzat ősosztályát képviseli.
type: docs
weight: 4990
url: /hu/aspose.slides/geometryshape/
---
## GeometryShape osztály

Az összes geometriai alakzat ősosztályát képviseli.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaadja egy alakzat beállítási értékeinek gyűjteményét. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja az alakzathoz társított alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alakzathoz társított alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzaton lévő csatlakozási pontok számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyedi adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja a EffectFormat objektumot, amely a alakzatra alkalmazott képpontos effektusokat tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén null értéket ad vissza, amelyeknek nincs effektus tulajdonságuk. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén null értéket ad vissza, amelyeknek nincs kitöltési tulajdonságuk. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja az alakzat magasságát pontokban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozáskezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatására definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a „Mark as decorative” opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén null értéket ad vissza, amelyeknek nincs vonal tulajdonságuk. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozott egyedi azonosítót, amely állandó az alakzat élettartama alatt, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon az alakzatra a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja egy alakzat helykitöltőjét. Null érték visszatér, ha a jelenlegi alakzat nem örökölt. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a diát tartalmazó prezentáció szülőjét. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzati keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli elforgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányú forgást jelzi. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja az alakzat stílusobjektumát. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Visszaadja vagy beállítja a geometria előre beállított típusát. Megjegyzés: az érték megváltoztatásakor minden beállítási érték visszaáll az alapértelmezett értékére. Olvasás/írás [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja egy alakzat szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely az alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén null értéket ad vissza, amelyeknek nincs 3D tulajdonságuk. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amely kiegészítők vagy más kód számára készült. Mivel ezt az értéket a felhasználó vagy programozottan újra lehet rendelned, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja az alakzat szélességét pontokban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának x-koordinátáját pontokban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának y-koordinátáját pontokban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy alakzat helyét a z-sorrendben. A Shapes[0] a z-sorrend hátsó részén lévő alakzatot adja, a Shapes[Shapes.Count - 1] pedig az előre lévő alakzatot. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helykitöltőt ad hozzá, ha nincs, és beállítja a helykitöltő tulajdonságait egy megadottra. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehoz és visszaad egy tömböt az alakzat elemeiből. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helykitöltő alakzatot (az elrendezésből és/vagy mester diáról származó alakzatot, amelyből a jelenlegi alakzat örököl). Null érték visszatér, ha a jelenlegi alakzat nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához viszonyítva relatívak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape alakzat bélyegkép-korlát típusa használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Visszaadja az alakzat vizuális határait, amelyeket a megjelenített tartalma alapján számoltak ki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helykitöltő. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti az alakzat geometriáját a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. Megváltoztatja az alakzat típusát ([`ShapeType`](./shapetype)) Custom-ra. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti az alakzat geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. Megváltoztatja az alakzat típusát ([`ShapeType`](./shapetype)) Custom-ra. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti az alakzat tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Elmenti az alakzat tartalmát SVG fájlként. |

### Lásd még

* osztály [Shape](../shape)
* interfész [IGeometryShape](../igeometryshape)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->