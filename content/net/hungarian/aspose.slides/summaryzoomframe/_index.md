---
title: SummaryZoomFrame
second_title: Aspose.Sildes .NET API referencia
description: Összefoglaló nagyítás objektumot képvisel egy dián.
type: docs
weight: 10750
url: /hu/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame osztály

Represents a Summary Zoom object in a slide.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a alakzathoz kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogy egy alakzat hogyan jelenik meg fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzaton lévő kapcsolati pontok számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a alakzatra alkalmazott pixel effektusokat tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyek nem rendelkeznek effektus tulajdonságokkal, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyek nem rendelkeznek kitöltési tulajdonságokkal, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja az alakzat magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér rámutatására definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | Visszaadja a Summary Zoom szekciók elrendezését a keretben. Alapértelmezett érték a GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyek nem rendelkeznek vonal tulajdonságokkal, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja az alakzat nevét. Nem lehet null. Szükség esetén üres karakterláncot kell használni. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy dián belüli egyedi azonosítót, amely a forma élettartama során állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja az alakzat helykitöltőt. Null értéket ad vissza, ha az alakzatnak nincs helykitöltője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzat keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a meghatározott alakzat z-tengely körüli forgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járása ellenkezőjét. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 tulajdonság) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja az alakzat szülő diáit. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | Visszaadja a [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) értéket a Summary Zoom Frame objektumhoz. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely az alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyek nem rendelkeznek 3D tulajdonságokkal, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozódó azonosítót, amely kiegészítők vagy más kód számára készült. Mivel ezt az értéket a felhasználó vagy programozottan át lehet rendelni, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja az alakzat szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának x-koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának y-koordinátáját pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy alakzat z-sorrendben elfoglalt pozícióját. A Shapes[0] a z-sorrend hátulján lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] pedig a frontján lévőt. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helykitöltőt ad hozzá, ha nincs, és a helykitöltő tulajdonságait egy megadottra állítja. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helykitöltő alakzatot (az elrendezésből és/vagy a mester diákról származó alakzat, amelyből a jelenlegi alakzat örökölt). Null érték tér vissza, ha a jelenlegi alakzat nincs örökölve. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape alakzati bélyegkép határoló típus kerül használatra. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Visszaadja az alakzat vizuális határait, amelyeket a renderelt tartalmából számítanak ki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helykitöltő. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti az alakzat tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Elmenti az alakzat tartalmát SVG fájlként. |

### Lásd még

* osztály [GraphicalObject](../graphicalobject)
* interfész [ISummaryZoomFrame](../isummaryzoomframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->