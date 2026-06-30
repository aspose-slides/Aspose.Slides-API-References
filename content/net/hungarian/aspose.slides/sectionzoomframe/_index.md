---
title: SectionZoomFrame
second_title: Aspose.Sildes .NET API Referenciája
description: Egy dián lévő Section Zoom objektumot reprezentál.
type: docs
weight: 9760
url: /hu/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame osztály

Egy Section Zoom objektumot reprezentál egy dián.

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a shape-hez társított alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a shape-hez társított alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Megadja, hogy a shape hogyan jelenik meg fekete-fehér módú megjelenítésben. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a shape kapcsolódási pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a shape egyéni adatát. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja a EffectFormat objektumot, amely a shape-re alkalmazott pixel-effekteket tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs effektus-tulajdonsága, null értéket ad vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a shape kitöltésének formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket ad vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a shape keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja a shape zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekéri vagy beállítja a shape magasságát pontokban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a shape rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér-rámutatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Lekéri vagy beállítja a zoom objektum kép-típusát. Olvasás/írás [`ZoomImageType`](../zoomimagetype). Alapértelmezett érték: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lekéri vagy beállítja a „Mark as decorative” beállítást. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a shape egy csoport része-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a shape TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs vonal-tulajdonsága, null értéket ad vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a shape nevét. Nem lehet null. Üres string használható, ha szükséges. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy dia-szintű egyedi azonosítót, amely a shape élettartama alatt állandó, és a PowerPoint vagy az interop kód megbízhatóan hivatkozhat rá a dokumentumban. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Egyébként null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a shape helyőrzőjét. Null érték, ha a shape-nek nincs helyőrzője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a slide szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a shape keretének nyers (raw) tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás Boolean. Alapértelmezett érték: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a shape z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelöli; a negatív ellenkező irányt. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja a shape zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 tulajdonság) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Lekéri vagy beállítja, hogy a Zoom a cél-dia háttérképét használja-e. Olvasás/írás Boolean. Alapértelmezett érték: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a shape szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Lekéri vagy beállítja azt a szekcióobjektumot, amelyre a Section Zoom hivatkozik. Olvasás/írás [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a shape 3-D effektusait tartalmazza. Megjegyzés: bizonyos shape-típusoknál, amelyeknek nincs 3-D tulajdonsága, null értéket ad vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Lekéri vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás Single. Alapértelmezett érték: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentáció-szintű azonosítót, amelyet kiegészítők vagy egyéb kód használhat. Mivel ezt az értéket a felhasználó vagy programozás útján átírhatja, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekéri vagy beállítja a shape szélességét pontokban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekéri vagy beállítja a shape bal-felső sarkának x-koordinátáját pontokban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekéri vagy beállítja a shape bal-felső sarkának y-koordinátáját pontokban mérve. Olvasás/írás Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Lekéri vagy beállítja a zoom objektum képét. Olvasás/írás [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a shape z-rendben elfoglalt pozícióját. A Shapes[0] a z-rend hátsó elemét, a Shapes[Shapes.Count - 1] a front-elemet adja vissza. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új placeholder-t ad hozzá, ha nincs, és beállítja a placeholder tulajdonságait egy megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap placeholder alakzatot (a layoutból és/vagy a mester diáról származó shape, amelyből az aktuális shape örököl). Null érték visszatér, ha az aktuális shape nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a shape bélyegképét. Alapértelmezésként a ShapeThumbnailBounds.Shape shape bélyegkép határ típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a shape bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri a shape vizuális határait, amely a renderelt tartalomból számított. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a shape nem placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlba menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlba menti. |

### Lásd még

* osztály [ZoomObject](../zoomobject)
* interfész [ISectionZoomFrame](../isectionzoomframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->