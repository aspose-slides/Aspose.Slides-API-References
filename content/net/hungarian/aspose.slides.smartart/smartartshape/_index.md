---
title: SmartArtShape
second_title: Aspose.Sildes a .NET API Referenciához
description: SmartArt alakzatot reprezentál
type: docs
weight: 10660
url: /hu/aspose.slides.smartart/smartartshape/
---
## SmartArtShape osztály

Represents SmartArt shape

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaadja a forma beállítási értékeinek gyűjteményét. Csak olvasható [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a formához társított alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a formához társított alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma kapcsolódási pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma egyedi adatait. Csak olvasható [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a forma pixel effektusait tartalmazza. Megjegyzés: bizonyos alakzatoknál, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a forma kitöltési tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekéri vagy beállítja a forma magasságát pontokban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér-felette definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Beállítja vagy lekéri a „Mark as decorative” opciót Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a forma csoportosítva van-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatoknál, amelyeknek nincs vonal-tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a forma nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy a diára vonatkozó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy az interoperációs kód számára, hogy a dokumentum bármely pontjáról megbízhatóan hivatkozzon a formára. Csak olvasható UInt32. Lásd még [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosítva van. Egyébként null értéket ad vissza. Csak olvasható [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helyettesítő objektumát. Ha a formának nincs helyettesítője, null értéket ad vissza. Csak olvasható [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott forma z-tengely körüli forgatási szögét fokban. A pozitív érték óramutató járásával megegyező forgást jelent; a negatív érték ellenirányú forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja a forma stílusobjektumát. Csak olvasható [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Visszaadja vagy beállítja a geometria előre definiált típusát. Megjegyzés: az érték megváltoztatásakor minden beállítási érték visszaáll az alapértelmezett értékekre. Olvasás/írás [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülő diáját. Csak olvasható [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Visszaadja a SmartArt forma szövegét. Csak olvasható [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D-effektus-tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatoknál, amelyeknek nincs 3D-tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amely a kiegészítők vagy más kód számára készült. Mivel ezt az értéket a felhasználó vagy programozottan módosíthatja, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekéri vagy beállítja a forma szélességét pontokban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekéri vagy beállítja a forma bal felső sarkának x koordinátáját pontokban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekéri vagy beállítja a forma bal felső sarkának y koordinátáját pontokban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a forma z-rendben betöltött pozícióját. A Shapes[0] visszaadja a hátul lévő formát, a Shapes[Shapes.Count - 1] pedig az előre lévő formát. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyettesítőt ad hozzá, ha nincs, és beállítja a helyettesítő tulajdonságait egy megadottra. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyettesítő formát (a layout vagy a mester dia formáját, amelyből az aktuális forma származik). Ha az aktuális forma nem örökölt, null értéket ad vissza. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához képest relatívak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma miniképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape típusú forma minikép határait használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma miniképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri a forma vizuális határait, amelyeket a megjelenített tartalma alapján számítanak ki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem helyettesítő. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti a forma geometriáját a [`IGeometryPath`](../../aspose.slides/igeometrypath) objektumból. A koordináták a forma bal felső sarkához képest relatívak kell legyenek. A forma típusát ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) Custom-re változtatja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti a forma geometriáját a [`IGeometryPath`](../../aspose.slides/igeometrypath) tömbből. A koordináták a forma bal felső sarkához képest relatívak kell legyenek. A forma típusát ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) Custom-re változtatja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GeometryShape](../../aspose.slides/geometryshape)
* interfész [ISmartArtShape](../ismartartshape)
* névtér [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->