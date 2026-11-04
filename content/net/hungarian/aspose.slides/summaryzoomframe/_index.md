---
title: SummaryZoomFrame
second_title: Aspose.Sildes .NET API referencia
description: Egy Summary Zoom objektumot képvisel egy dián.
type: docs
weight: 10790
url: /hu/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame osztály

Egy Summary Zoom objektumot képvisel egy dián.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja egy alakzathoz kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja egy alakzathoz kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzaton lévő csatlakozási pontok számát. Csak olvasás Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasás [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a alakzatra alkalmazott pixel effektusokat tartalmazza. Megjegyzés: bizonyos alakzat típusok esetén, amelyeknek nincsenek effektus tulajdonságai, null értéket adhat vissza. Csak olvasás [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely egy alakzat kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzat típusok esetén, amelyeknek nincsenek kitöltési tulajdonságai, null értéket adhat vissza. Csak olvasás [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasás [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekérdezi vagy beállítja az alakzat magasságát, pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasás [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér felett tartásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lekérdezi vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasás Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasás Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | Lekérdezi a Summary Zoom szakaszok elrendezését a keretben. Az alapértelmezett érték a GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely egy alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzat típusok esetén, amelyeknek nincsenek vonal tulajdonságai, null értéket adhat vissza. Csak olvasás [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára vonatkozó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozhasson az alakzatra a dokumentum bármely pontjáról. Csak olvasás UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasás [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja az alakzat helyfoglalóját. Ha az alakzaton nincs helyfoglaló, null értéket ad vissza. Csak olvasás [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasás [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásának irányú forgatást jelzi; a negatív érték az ellenkező irányú forgatást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasás [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 tulajdonság) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja az alakzat szülő diáját. Csak olvasás [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | Lekérdezi a [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) értékét a Summary Zoom Frame objektumhoz. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely egy alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzat típusok esetén, amelyeknek nincsenek 3D tulajdonságai, null értéket adhat vissza. Csak olvasás [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy a program is átállíthatja, nem tekinthető állandó egyedi kulcsnak. Csak olvasás UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekérdezi vagy beállítja az alakzat szélességét, pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekérdezi vagy beállítja az alakzat bal-felső sarkának x-koordinátáját, pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekérdezi vagy beállítja az alakzat bal-felső sarkának y-koordinátáját, pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy alakzat pozícióját a z-rendben. A Shapes[0] a z-rend hátul lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] pedig a frontvonalban lévő alakzatot. Csak olvasás Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyfoglalót ad hozzá, ha nincs, és beállítja a helyfoglaló tulajdonságait egy megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyfoglaló alakzatot (a layoutból és/vagy a mesterdiából származó alakzat, amelyből a jelenlegi alakzat örököl). Ha a jelenlegi alakzat nem örököl, null értéket ad vissza. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape típusú határoló használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekérdezi az alakzat vizuális határait, amelyeket a megjelenített tartalom alapján számol. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helyfoglaló. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti az alakzat tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Elmenti az alakzat tartalmát SVG fájlként. |

### Lásd még

* osztály [GraphicalObject](../graphicalobject)
* interfész [ISummaryZoomFrame](../isummaryzoomframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->