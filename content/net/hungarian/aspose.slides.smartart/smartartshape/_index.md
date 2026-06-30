---
title: SmartArtShape
second_title: Aspose.Sildes .NET API referencia
description: SmartArt alakzatot képviseli
type: docs
weight: 10640
url: /hu/aspose.slides.smartart/smartartshape/
---
## SmartArtShape osztály

A SmartArt alakzatot képviseli

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaad egy gyűjteményt az alakzat beállítási értékeiről. Csak olvasás [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság megadja, hogyan jelenik meg egy alakzat fekete-fehér módon. Olvasás/írás [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzat csatlakozási pontjainak számát. Csak olvasás Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasás [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a alakzatra alkalmazott pixeles effektusokat tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasás [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a kitöltési formázási tulajdonságokat tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasás [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja az alakzat magasságát pontokban. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasás [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a „Megjelölés dekoratívként” lehetőséget. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasás Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasás Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a vonal formázási tulajdonságokat tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasás [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja az alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy dián belül egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy a dokumentum bármely helyéről megbízhatóan hivatkozzon rá. Csak olvasás UInt32. Lásd még [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasás [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a helyfoglalót az alakzathoz. Ha az alakzatnak nincs helyfoglalója, null értéket ad vissza. Csak olvasás [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a diát tartalmazó prezentáció szülőjét. Csak olvasás [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat Z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelent; a negatív érték az ellentétes irányt. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasás [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja az alakzat stílusobjektumát. Csak olvasás [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Visszaadja vagy beállítja a geometria előre beállított típusát. Megjegyzés: az érték megváltoztatásakor minden beállítási érték visszaáll az alapértelmezett értékre. Olvasás/írás [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja az alakzat szülő diát. Csak olvasás [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Visszaadja a SmartArt alakzat szövegét. Csak olvasás [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasás [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentáción belüli azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozott módon is átállíthatja, nem tekinthető állandó egyedi kulcsnak. Csak olvasás UInt32. Lásd még [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja az alakzat szélességét pontokban. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának x-koordinátáját pontokban. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának y-koordinátáját pontokban. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja az alakzat pozícióját a z-rendezésben. A Shapes[0] a z-rendezés hátulján lévő alakzatot adja, a Shapes[Shapes.Count - 1] pedig az előtérben lévőt. Csak olvasás Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyfoglalót ad hozzá, ha nincs, és beállítja a helyfoglaló tulajdonságait a megadottra. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja az alakzat elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyfoglaló alakzatot (a elrendezésről és/vagy a mesterdiáról származó alakzat, amelyből a jelenlegi örökölt). Null érték visszatér, ha a jelenlegi alakzat nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai alakzat útvonalának másolatát. A koordináták az alakzat bal felső sarkához viszonyítva vannak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegképhatároló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri az alakzat vizuális határait, amelyeket a renderelt tartalom alapján számít. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helyfoglaló. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti az alakzat geometriáját a(z) [`IGeometryPath`](../../aspose.slides/igeometrypath) objektumból. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. A forma típusát ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) Custom-ra változtatja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti az alakzat geometriáját a(z) [`IGeometryPath`](../../aspose.slides/igeometrypath) tömbből. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. A forma típusát ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) Custom-ra változtatja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti az alakzat tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Elmenti az alakzat tartalmát SVG fájlként. |

### Lásd még

* osztály [GeometryShape](../../aspose.slides/geometryshape)
* interfész [ISmartArtShape](../ismartartshape)
* névtér [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->