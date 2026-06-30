---
title: InkActions
second_title: Aspose.Sildes a .NET-hez API-referencia
description: A tinta műveletek gyökerét képviseli.
type: docs
weight: 7540
url: /hu/aspose.slides.ink/inkactions/
---
## InkActions osztály

A tintaműveletek gyökerét képviseli.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a forma alternatív szövegét. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a forma alternatív szövegének címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma egyéni adatait. Csak olvasható [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixel-effektusait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | A forma magasságát adja meg vagy állítja be, pontokban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | A 'Megjelölés dekoratívként' opciót adja meg vagy állítja be. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy a forma csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a forma nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy dián belüli egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely pontjáról. Csak olvasható UInt32. Lásd még [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helyfoglalóját. Ha a formának nincs helyfoglalója, null értéket ad vissza. Csak olvasható [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő bemutatóját. Csak olvasható [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott forma z-tengely körüli fordulási fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 tulajdonság) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülő diáját. Csak olvasható [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, bemutató-szintű azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozott módon újra lehet rendelni, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | A forma szélességét adja meg vagy állítja be, pontokban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | A forma bal-felső sarkának x-koordinátáját adja meg vagy állítja be, pontokban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | A forma bal-felső sarkának y-koordinátáját adja meg vagy állítja be, pontokban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a forma z-rendben betöltött pozícióját. A Shapes[0] a z-rend hátsó részén lévő formát adja vissza, a Shapes[Shapes.Count - 1] pedig az előre részen lévő formát. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyfoglalót ad hozzá, ha nincs, és beállítja a helyfoglaló tulajdonságait a megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyfoglaló formát (a layoutból és/vagy a mester diákról örökölt formát). Null érték kerül visszaadásra, ha a jelenlegi forma nem öröklődik. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma miniatűrjét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape miniatűr keret típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma miniatűrjét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | A forma megjelenített tartalmából számított vizuális határokat adja meg. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Megadja, hogy ez a forma nem helyfoglaló. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A forma tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A forma tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GraphicalObject](../../aspose.slides/graphicalobject)
* interfész [IInkActions](../iinkactions)
* névtér [Aspose.Slides.Ink](../../aspose.slides.ink)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->