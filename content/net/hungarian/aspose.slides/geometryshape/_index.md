---
title: GeometryShape
second_title: Aspose.Sildes .NET API referencia
description: Az összes geometriai alakzat szülő osztályát képviseli.
type: docs
weight: 4950
url: /hu/aspose.slides/geometryshape/
---
## GeometryShape osztály

Az összes geometriai alakzat szülő osztályát reprezentálja.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | A forma beállítási értékeinek gyűjteményét adja vissza. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | A formához társított alternatív szöveget adja vissza vagy állítja be. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | A formához társított alternatív szöveg címét adja vissza vagy állítja be. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Megadja, hogy a forma hogyan jelenik meg fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | A formán lévő csatlakozási helyek számát adja vissza. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | A forma egyéni adatait adja vissza. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Az EffectFormat objektumot adja vissza, amely a forma alkalmazott pixelhatásait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | A FillFormat objektumot adja vissza, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | A forma keretének tulajdonságait adja vissza vagy állítja be. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | A forma magasságát adja vissza vagy állítja be, pontokban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Az egérkattintásra definiált hiperhivatkozást adja vissza vagy állítja be. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | A hiperhivatkozáskezelőt adja vissza. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Az egér fölé mozgatásra definiált hiperhivatkozást adja vissza vagy állítja be. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | A 'Mark as decorative' opciót adja vissza vagy állítja be. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a forma csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | A LineFormat objektumot adja vissza, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | A forma nevét adja vissza vagy állítja be. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | A diára korlátozott egyedi azonosítót adja vissza, amely a forma életciklusa alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helyőrzőjét. Null értéket ad vissza, ha a formának nincs helyőrzője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a formanyerszám nyers keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott forma z-tengely körüli forgatási fokszámát. A pozitív érték óramutató járásával megegyező forgatást jelez; a negatív érték az ellenkező irányt. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja a forma stílusobjektumát. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Visszaadja vagy beállítja a geometriai előre beállított típust. Megjegyzés: az érték módosításakor minden beállítási érték visszaáll az alapértelmezett értékekre. Olvasás/írás [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülő diáit. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet a kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozottan újra be lehet állítani, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja a forma szélességét, pontokban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja a forma bal-felső sarkának x-koordinátáját, pontokban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja a forma bal-felső sarkának y-koordinátáját, pontokban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a forma z-rendezési pozícióját. A Shapes[0] a z-rendezés hátuljában lévő formát adja vissza, a Shapes[Shapes.Count - 1] pedig a frontján lévő formát. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait egy megadottra állítja. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző formát (a elrendezésből vagy/vagy a mesterdiaból származó formát, amelyből az aktuális forma örököl). Null értéket ad vissza, ha az aktuális forma nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal-felső sarkához viszonyítva vannak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegkép-határoló típus használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekérdezi a forma vizuális határait, amelyet a megjelenített tartalom alapján számítanak ki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem helyőrző. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti a forma geometriáját a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak a forma bal-felső sarkához viszonyítva kell lenniük. A forma típusát ([`ShapeType`](./shapetype)) egyénire változtatja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti a forma geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak a forma bal-felső sarkához viszonyítva kell lenniük. A forma típusát ([`ShapeType`](./shapetype)) egyénire változtatja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A forma tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A forma tartalmát SVG fájlként menti. |

### Lásd még

* osztály [Shape](../shape)
* interfész [IGeometryShape](../igeometryshape)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->