---
title: Table
second_title: Aspose.Sildes a .NET API referencia
description: Egy dián egy táblát reprezentál.
type: docs
weight: 10840
url: /hu/aspose.slides/table/
---
## Table osztály

Egy dián megjelenő táblát reprezentál.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a formához tartozó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a formához tartozó alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogy a forma hogyan jelenik meg fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Visszaadja az oszlopok gyűjteményét. Csak olvasható [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma csatlakozási helyeinek számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixelhatásait tartalmazza. Megjegyzés: bizonyos, hatástulajdonságokkal nem rendelkező formák esetén null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Visszaad egy TableFormat.FillFormat objektumot, amely a tábla kitöltési formázását tartalmazza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Meghatározza, hogy a tábla első oszlopa speciális formázással legyen-e megjelenítve. Olvasás/írás Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Meghatározza, hogy a tábla első sorát speciális formázással legyen-e megjelenítve. Olvasás/írás Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja a forma magasságát, pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Meghatározza, hogy a páros sorok különböző formázással legyenek-e megjelenítve. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé húzásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a forma csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Visszaadja a megadott oszlop- és sorindexeknél lévő cellát. Csak olvasható [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Meghatározza, hogy a tábla utolsó oszlopa speciális formázással legyen-e megjelenítve. Olvasás/írás Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Meghatározza, hogy a tábla utolsó sora speciális formázással legyen-e megjelenítve. Olvasás/írás Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos, vonal tulajdonságokkal nem rendelkező formák esetén null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy forma nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy dián belül egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy a dokumentum bármely részéről megbízhatóan hivatkozzon a formára. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helyőrzőjét. Null értéket ad, ha a formának nincs helyőrzője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Meghatározza, hogy a táblának jobbról balra olvasási sorrendje van-e. Olvasás/írás Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott forma Z-tengely körül forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasás/írás Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Visszaadja a sorok gyűjteményét. Csak olvasható [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 tulajdonság) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Visszaadja vagy beállítja a beépített tábla stílust. Olvasás/írás [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Visszaadja a TableFormat objektumot, amely a tábla formázási tulajdonságait tartalmazza. Csak olvasható [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos, 3D tulajdonságokkal nem rendelkező formák esetén null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amely kiegészítők vagy más kódok számára készült. Mivel ezt az értéket a felhasználó vagy programból is át lehet állítani, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Meghatározza, hogy a páros oszlopok különböző formázással legyenek-e megjelenítve. Olvasás/írás Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja a forma szélességét, pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja a forma bal felső sarkának x-koordinátáját, pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja a forma bal felső sarkának y-koordinátáját, pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy forma z-sorrendben elfoglalt pozícióját. A Shapes[0] a z-sorrend hátulján lévő formát adja vissza, míg a Shapes[Shapes.Count - 1] a fronton lévőt. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait egy megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző formát (a elrendezésből és/vagy mester diából származó formát, amelyből a jelenlegi forma örököl). Null értéket ad, ha a jelenlegi forma nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma miniatűrjét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape miniatűr határoló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma miniatűrjét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Visszaadja a forma megjelenített tartalma alapján számított vizuális határolókat. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Összevonja a szomszédos cellákat. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem helyőrző. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Beállítja a meghatározott bekezdésformátum tulajdonságait az összes tábla cella bekezdéseire. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Beállítja a meghatározott részformátum tulajdonságait az összes tábla cella részeire. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Beállítja a meghatározott szövegkeret formátum tulajdonságait az összes tábla cella szövegkereteire. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Mentse a forma tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Mentse a forma tartalmát SVG fájlként. |

### Lásd még

* osztály [GraphicalObject](../graphicalobject)
* interfész [ITable](../itable)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->