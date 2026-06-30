---
title: IShape
second_title: Aspose.Sildes a .NET API referencia
description: Egy dián lévő alakzatot képvisel.
type: docs
weight: 6930
url: /hu/aspose.slides/ishape/
---
## IShape interfész

Az egyik dián lévő alakzatot jelöli.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Lehetővé teszi a base IHyperlinkContainer interfész lekérdezését. Csak olvasható [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Lehetővé teszi a base ISlideComponent interfész lekérdezését. Csak olvasható [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Megadja, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Visszaadja az alakzaton lévő kapcsolódási pontok számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a pixel-hatásokat tartalmazza az alakzaton. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a kitöltési formázási tulajdonságokat tartalmazza az alakzaton. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Visszaadja vagy beállítja az alakzat magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Meghatározza, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Beállítja a „Megjelölés dekorációként” opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Meghatározza, hogy az alakzat csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Meghatározza, hogy az alakzat TextHolder-e. Csak olvasható Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a vonalformázási tulajdonságokat tartalmazza az alakzaton. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Visszaadja vagy beállítja az alakzat nevét. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon rá a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Egyébként null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Visszaadja az alakzat helyőrzőjét. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat Z-tengely körüli elforgatásának fokszámát. A pozitív érték óramutató irányú forgást jelent; a negatív érték ellentétes irányú forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a vonalformázási tulajdonságokat tartalmazza az alakzaton. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozódó azonosítót, amelyet kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozottan újra fel lehet osztani, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Visszaadja vagy beállítja az alakzat szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Visszaadja vagy beállítja az alakzat bal-felső sarkának X-koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Visszaadja vagy beállítja az alakzat bal-felső sarkának Y-koordinátáját pontban mérve. Olvasás/írás Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Visszaadja az alakzat pozícióját a Z-rendben. A Shapes[0] az alja, a Shapes[Shapes.Count - 1] a teteje. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait a megadottra. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Visszaad egy alap helyőrző alakzatot (a current shape-ből származó elrendezési vagy mesterdiát). Null érték visszatér, ha a current shape nem örökölt. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezésben a ShapeThumbnailBounds.Shape alakzat bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helyőrző. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Elmenti az alakzat tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Elmenti az alakzat tartalmát SVG fájlként. |

### Lásd még

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->