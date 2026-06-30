---
title: GroupShape
second_title: Aspose.Sildes .NET API referenciája
description: Egy dián lévő alakzatcsoportot reprezentál.
type: docs
weight: 5070
url: /hu/aspose.slides/groupshape/
---
## GroupShape osztály

Egy dián lévő alakzatcsoportot reprezentál.

```csharp
public class GroupShape : Shape, IGroupShape
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | Lehetővé teszi a base IShape interfész lekérését. Csak olvasható [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzat csatlakozási pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a alakzatra alkalmazott pixelhatásokat tartalmazza. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekéri vagy beállítja az alakzat magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lekéri vagy beállítja a 'Megjelölés dekoratívként' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: GroupShape objektumok esetén null értéket ad vissza, mivel nincs vonal tulajdonságuk. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozott egyedi azonosítót, amely az alakzat élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon az alakzatra a dokumentum bármely részéből. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja az alakzat helykitöltőjét. Null értéket ad vissza, ha az alakzatnak nincs helykitöltője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a fokok számát, amelyben a megadott alakzat a z-tengely körül el van forgatva. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást jelzi. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGroupShapeLock`](../igroupshapelock). (2 tulajdonság) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | Visszaadja a csoporton belüli alakzatok gyűjteményét. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja az alakzat szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely az alakzat 3D hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ez az érték felhasználó vagy program által újra kiosztható, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekéri vagy beállítja az alakzat szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekéri vagy beállítja az alakzat bal felső sarkának x koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekéri vagy beállítja az alakzat bal felső sarkának y koordinátáját pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja az alakzat pozícióját a z-sorrendben. A Shapes[0] a z-sorrend hátulján lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] pedig a frontján lévő alakzatot. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helykitöltőt ad hozzá, ha nincs, és a helykitöltő tulajdonságait egy megadottra állítja. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helykitöltő alakzatot (az elrendezésből és/vagy a mester diáról származó alakzat, amelyből a jelenlegi alakzat örököl). Null értéket ad vissza, ha a jelenlegi alakzat nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape alakzat bélyegkép határolók típusa használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri az alakzat vizuális határait, amely a renderelt tartalom alapján számítódik ki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helykitöltő. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti az alakzat tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | Elmenti az alakzat tartalmát SVG fájlként. |

### Lásd még

* osztály [Shape](../shape)
* interfész [IGroupShape](../igroupshape)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->