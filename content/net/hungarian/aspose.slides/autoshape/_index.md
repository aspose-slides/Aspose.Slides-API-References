---
title: AutoShape
second_title: Aspose.Slides .NET API referenciája
description: AutoShape-et ábrázol.
type: docs
weight: 880
url: /hu/aspose.slides/autoshape/
---
## AutoShape osztály

Represents an AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaadja a forma igazítási értékeinek gyűjteményét. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a forma alternatív szövegét. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a forma alternatív szövegének címét. Olvasás/írás String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Visszaadja az autoshape zárolásait. Csak olvasható [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma csatlakozási helyeinek számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma saját adatát. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixeles effektusait tartalmazza. Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekéri vagy beállítja a forma magasságát pontokban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja a egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lekéri vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy a forma csoportosított-e. Csak olvasható Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Megadja, hogy a forma szövegdoboz-e. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formáknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a forma nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy a dokumentum bármely pontjáról megbízhatóan hivatkozzon a formára. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helyfoglalóját. Null értéket ad vissza, ha a formának nincs helyfoglalója. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott forma z-tengely körüli forgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgatást jelzi; a negatív érték az ellenkező irányt. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IAutoShapeLock`](../iautoshapelock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja a forma stílusobjektumát. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Visszaadja vagy beállítja a geometria előre beállított típusát. Megjegyzés: az érték változásakor minden igazítási érték visszaáll az alapértelmezett értékére. Olvasás/írás [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülődiáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Visszaadja az AutoShape TextFrame objektumát. Csak olvasható [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formáknál, amelyeknek nincsenek 3D tulajdonságai, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy egyéb kód használhat. Mivel ezt az értéket a felhasználó vagy programkóddal újra lehet rendelni, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Megállapítja, hogy ez az autoshape a dia háttérkitöltésével legyen-e kitöltve a stílus vagy kitöltési formátum helyett. Olvasás/írás Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekéri vagy beállítja a forma szélességét pontokban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekéri vagy beállítja a forma bal felső sarkának x-koordinátáját pontokban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekéri vagy beállítja a forma bal felső sarkának y-koordinátáját pontokban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a forma z-sorrendben betöltött pozícióját. A Shapes[0] a z-sorrend hátulját, a Shapes[Shapes.Count - 1] az elölöt adja vissza. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyfoglalót ad hozzá, ha nincs, és a megadott helyfoglaló tulajdonságait beállítja. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Új TextFrame-et ad egy formához. Ha a forma már rendelkezik TextFrame-el, akkor egyszerűen megváltoztatja a szövegét. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyfoglaló formát (a layoutból és/vagy a fődiából származó formát, amelyről a jelenlegi forma örököl). Null értéket ad vissza, ha a jelenlegi forma nem öröklődik. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához relatívak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape forma bélyegkép határok típusa használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri a forma vizuális határait, amelyek a renderelt tartalomból számítottak. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem helyfoglaló. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti a forma geometriáját a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük. A forma típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra változtatja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti a forma geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük. A forma típusát ([`ShapeType`](../geometryshape/shapetype)) Custom-ra változtatja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Forma tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Forma tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GeometryShape](../geometryshape)
* interfész [IAutoShape](../iautoshape)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->