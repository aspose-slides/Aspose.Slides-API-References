---
title: IShape
second_title: Aspose.Sildes .NET API referencia
description: Egy dián lévő alakzatot reprezentál.
type: docs
weight: 6970
url: /hu/aspose.slides/ishape/
---
## IShape interfész

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Visszaadja vagy beállítja a alakzathoz tartozó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a alakzathoz tartozó alternatív szöveg címét. Olvasás/írás String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Hozzáférést biztosít az alap IHyperlinkContainer interfészhez. Csak olvasható [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Hozzáférést biztosít az alap ISlideComponent interfészhez. Csak olvasható [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Ez a tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Visszaadja az alakzat kapcsolati pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Visszaadja az alakzat egyedi adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Visszaadja a EffectFormat objektumot, amely az alakzatra alkalmazott pixel effektusokat tartalmazza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Visszaadja vagy beállítja az alakzat magasságát pontokban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Dekorációként megjelölés' lehetőséget. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosítva van-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder-e. Csak olvasható Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Visszaadja vagy beállítja az alakzat nevét. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Visszaad egy diára vonatkozó egyedi azonosítót, amely a forma életciklusa során állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosítva van. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Visszaadja az alakzat helyőrzőjét. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzati keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatásának fokszámát. A pozitív érték óramutató járásával megegyező forgást jelez; a negatív érték az óramutató járásával ellentétes forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Visszaad egy belső, prezentációra vonatkozó azonosítót, amelyet kiegészítők vagy egyéb kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan is újra lehet rendelni, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Visszaadja vagy beállítja az alakzat szélességét pontokban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának x koordinátáját pontokban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának y koordinátáját pontokban mérve. Olvasás/írás Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Visszaadja az alakzat helyzetét a z-sorrendben. A Shapes[0] visszaadja a z-sorrend hátsó elemét, a Shapes[Shapes.Count - 1] pedig a fronti elemét. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait a megadottra állítja. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Visszaad egy alap helyőrző alakzatot (az elrendezésből és/vagy a mesterdiáról származó alakzat, amelyből az aktuális alakzat örököl). Ha az aktuális alakzat nem örököl, null értéket ad vissza. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helyőrző. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* interfész [IHyperlinkContainer](../ihyperlinkcontainer)
* interfész [ISlideComponent](../islidecomponent)
* névtér [Aspose.Slides](../../aspose.slides)
* összeszerelés [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->