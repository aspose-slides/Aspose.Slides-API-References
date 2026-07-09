---
title: IShape
second_title: Aspose.Sildes for .NET API referencia
description: Egy dián lévő alakzatot képvisel.
type: docs
weight: 6950
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
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Visszaadja vagy beállítja a shape-hez tartozó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a shape-hez tartozó alternatív szöveg címét. Olvasás/írás String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Lehetővé teszi a bázis IHyperlinkContainer interfész lekérdezését. Csak olvasás [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Lehetővé teszi a bázis ISlideComponent interfész lekérdezését. Csak olvasás [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogy egy shape hogyan jelenik meg fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Visszaadja a shape csatlakozási helyeinek számát. Csak olvasás Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Visszaadja a shape egyéni adatait. Csak olvasás [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixel hatásokat tartalmazza. Csak olvasás [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a shape kitöltési formázási tulajdonságait tartalmazza. Csak olvasás [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Visszaadja vagy beállítja a shape keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Visszaadja vagy beállítja a shape magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Megállapítja, hogy a shape rejtett-e. Olvasás/írás Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Megállapítja, hogy a shape csoportosított-e. Csak olvasás Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Megállapítja, hogy a shape TextHolder-e. Csak olvasás Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Csak olvasás [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Visszaadja vagy beállítja a shape nevét. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Visszaad egy dia által határolt egyedi azonosítót, amely a shape élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a shape-re a dokumentum bármely részéről. Csak olvasás UInt32. Lásd még [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Egyébként null értéket ad vissza. Csak olvasás [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Visszaadja a shape helyőrzőjét. Csak olvasás [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers shape keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott shape z-tengely körüli elforgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellentétes irányú forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Visszaadja a shape zárolásait. Csak olvasás [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Csak olvasás [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Visszaad egy belső, prezentáció által határolt azonosítót, amelyet a kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozott módon át lehet rendelni, nem szabad állandó egyedi kulcsként kezelni. Csak olvasás UInt32. Lásd még [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Visszaadja vagy beállítja a shape szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Visszaadja vagy beállítja a shape bal felső sarkának x-koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Visszaadja vagy beállítja a shape bal felső sarkának y-koordinátáját pontban mérve. Olvasás/írás Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Visszaadja a shape z-rendben betöltött pozícióját. A Shapes[0] a z-rend hátsó részén lévő shape-t adja vissza, a Shapes[Shapes.Count - 1] pedig az előre lévő shape-t. Csak olvasás Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait egy meghatározottra. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Visszaad egy alap helyőrző alakot (az elrendezésből és/vagy a mesterdiából származó shape, amelyről a jelenlegi shape örököl). Null értéket ad vissza, ha a jelenlegi shape nem örököl. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Visszaadja a shape bélyegképét. Alapértelmezésként a ShapeThumbnailBounds.Shape shape bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Visszaadja a shape bélyegképét. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Meghatározza, hogy ez a shape nem helyőrző. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* interfész [IHyperlinkContainer](../ihyperlinkcontainer)
* interfész [ISlideComponent](../islidecomponent)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->