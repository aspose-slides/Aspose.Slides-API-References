---
title: Ink
second_title: Aspose.Sildes .NET API Referencia
description: Egy dián lévő tinta objektumot reprezentál.
type: docs
weight: 7530
url: /hu/aspose.slides.ink/ink/
---
## Ink osztály

Egy tintát jelképező objektumot reprezentál egy dián.

```csharp
public class Ink : GraphicalObject, IInk
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a shape-hez kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a shape-hez kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg a shape fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a shape kapcsolódási pontjainak számát. Csak-olvasás Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a shape egyéni adatait. Csak-olvasás [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixeles effektusokat tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak-olvasás [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a shape kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak-olvasás [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a shape keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja a shape zárolásait. Csak-olvasás [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja a shape magasságát, pontokban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a shape rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak-olvasás [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér áthaladására definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a shape csoportosított-e. Csak-olvasás Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a shape TextHolder_PPT-e. Csak-olvasás Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs vonaltulajdonsága, null értéket adhat vissza. Csak-olvasás [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a shape nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozott egyedi azonosítót, amely a shape élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy interop kód megbízhatóan hivatkozzon a shape-re a dokumentum bármely részéről. Csak-olvasás UInt32. Lásd még [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Ellenkező esetben null értéket ad vissza. Csak-olvasás [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a shape helykitöltőjét. Ha a shape-nek nincs helykitöltője, null értéket ad vissza. Csak-olvasás [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a slide szülő prezentációját. Csak-olvasás [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers shape keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott shape z-tengely körüli elforgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja a shape zárolásait. Csak-olvasás [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 tulajdonság) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a shape szülő slide-ját. Csak-olvasás [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a shape 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak-olvasás [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | Lekéri az összes nyomot, amely az IInk elemben [`IInkTrace`](../iinktrace) található. Csak-olvasás. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programkóddal felül lehet írni, nem tekinthető állandó egyedi kulcsnak. Csak-olvasás UInt32. Lásd még [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja a shape szélességét, pontokban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja a shape bal-felső sarkának x koordinátáját, pontokban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja a shape bal-felső sarkának y koordinátáját, pontokban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy shape z-rendben elfoglalt pozícióját. A Shapes[0] a z-rend hátsó részén lévő shape-t adja vissza, a Shapes[Shapes.Count - 1] pedig az elöl lévő shape-t. Csak-olvasás Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | Lekéri az egyéni képek gyűjteményét, amelyeket a tinta ecsetek vizuális effektusainak szimulálására használnak. Ezeket a képeket a tinta adott [`InkEffectType`](../inkeffecttype) értékeivel (például Galaxy, Rainbow stb.) történő megjelenítésekor használják. Saját képek megadásával szabályozhatja, hogy minden tinta effektus hogyan jelenik meg. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helykitöltőt ad hozzá, ha nincs, és beállítja a helykitöltő tulajdonságait a megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helykitöltő alakzatot (az elrendezésből és/vagy a mester diáról származó shape, amelyből a jelenlegi shape örököl). Null értéket ad vissza, ha a jelenlegi shape nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a shape bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape shape bélyegkép határ típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a shape bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri a shape vizuális határait, amelyet a megjelenített tartalma alapján számol. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a shape nem helykitöltő. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GraphicalObject](../../aspose.slides/graphicalobject)
* interfész [IInk](../iink)
* névtér [Aspose.Slides.Ink](../../aspose.slides.ink)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->