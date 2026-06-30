---
title: SmartArt
second_title: Aspose.Sildes .NET API Referencia
description: SmartArt diagramot reprezentál
type: docs
weight: 10580
url: /hu/aspose.slides.smartart/smartart/
---
## SmartArt osztály

SmartArt diagramot reprezentál

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Visszaadja a SmartArt objektum összes csomópontjának gyűjteményét. Csak olvasható [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja egy alakzathoz társított alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja egy alakzathoz társított alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Visszaadja vagy beállítja a SmartArt objektum színstílusát. Olvasás/írás [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzat csatlakozási helyeinek számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasható [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a alakzatra alkalmazott pixel effektusokat tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén, amelyeknek nincsenek effektus tulajdonságai, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén, amelyeknek nincsenek kitöltési tulajdonságai, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja az alakzat magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hivatkozáskezelőt. Csak olvasható [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egérmutatásra definiált hivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Megjelölés dekoratívként' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Visszaadja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy (jobbról balra) RTL tekintetében, ha a diagram támogatja a fordítást. Olvasás/írás Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Visszaadja vagy beállítja a SmartArt objektum elrendezését. Olvasás/írás [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely egy alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén, amelyeknek nincsenek vonal tulajdonságai, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Ha szükséges, használjon üres karakterláncot. Olvasás/írás String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Visszaadja a SmartArt objektum gyökércsomópontjainak gyűjteményét. Csak olvasható [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára vonatkozó egyedi azonosítót, amely a forma életciklusáig állandó marad, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely helyéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja egy alakzat helyőrzőjét. Null értéket ad vissza, ha az alakzatnak nincs helyőrzője. Csak olvasható [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja egy dia szülő prezentációját. Csak olvasható [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Visszaadja vagy beállítja a SmartArt objektum gyorsstílusát. Olvasás/írás [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 tulajdonság) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja egy alakzat szülő diát. Csak olvasható [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely egy alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén, amelyeknek nincsenek 3D tulajdonságai, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy egyéb kódok használhatnak. Mivel ezt az értéket a felhasználó vagy a programkód felülírhatja, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja az alakzat szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja az alakzat bal-felső sarkának x-koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja az alakzat bal-felső sarkának y-koordinátáját pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy alakzat helyzetét a z-sorrendben. A Shapes[0] a z-sorrend hátulján lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] a frontján lévő alakzatot. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait a megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző alakzatot (a elrendezésből és/vagy a mesterdiából származó alakzat, amelyből az aktuális alakzat örököl). Null értéket ad vissza, ha az aktuális alakzat nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape alakzat bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri az alakzat megjelenített határait, amelyeket a renderelt tartalom alapján számolt ki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helyőrző. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Forma tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Forma tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GraphicalObject](../../aspose.slides/graphicalobject)
* interfész [ISmartArt](../ismartart)
* névtér [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->