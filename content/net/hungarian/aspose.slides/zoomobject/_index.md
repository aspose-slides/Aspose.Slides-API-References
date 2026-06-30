---
title: ZoomObject
second_title: Aspose.Sildes .NET API-referencia
description: Egy Zoom objektumot ábrázol egy dián.
type: docs
weight: 11850
url: /hu/aspose.slides/zoomobject/
---
## ZoomObject osztály

Represents an Zoom object in a slide.

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a forma alternatív szövegét. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a forma alternatív szövegének címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság megadja, hogyan jelenik meg a forma fekete-fehér módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasás Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma egyéni adatait. Csak olvasás [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja a EffectFormat objektumot, amely a forma pixeles hatásait tartalmazza. Megjegyzés: bizonyos formatípusoknál null értéket adhat vissza, ha nincs effektus tulajdonságuk. Csak olvasás [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos formatípusoknál null értéket adhat vissza, ha nincs kitöltési tulajdonságuk. Csak olvasás [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja a forma zárolásait. Csak olvasás [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja a forma magasságát pontban. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintáshoz definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasás [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Visszaadja vagy beállítja a zoom objektum képtípusát. Olvasás/írás [`ZoomImageType`](../zoomimagetype). Alapértelmezett érték: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a „Mark as decorative” (díszítőnek jelölés) beállítást. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a forma csoportosítva van-e. Csak olvasás Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a forma TextHolder_PPT-e. Csak olvasás Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos formatípusoknál null értéket adhat vissza, ha nincs vonal tulajdonságuk. Csak olvasás [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a forma nevét. Nem lehet null. Ha szükséges, üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy a diára vonatkozó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasás UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként null értéket ad vissza. Csak olvasás [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a placeholder-t a forma számára. Null értéket ad vissza, ha a forma nem rendelkezik placeholder-rel. Csak olvasás [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasás [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Visszaadja vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás Boolean. Alapértelmezett érték: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a forma z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkezőjét. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasás [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 property) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Visszaadja vagy beállítja, hogy a Zoom a cél dia háttérét használja-e. Olvasás/írás Boolean. Alapértelmezett érték: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülő diáját. Csak olvasás [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos formatípusoknál null értéket adhat vissza, ha nincs 3D tulajdonságuk. Csak olvasás [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Visszaadja vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás Single. Alapértelmezett érték: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra vonatkozó azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy a program felülírhatja, nem tekinthető állandó egyedi kulcsnak. Csak olvasás UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja a forma szélességét pontban. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja a forma bal felső sarkának x koordinátáját pontban. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja a forma bal felső sarkának y koordinátáját pontban. Olvasás/írás Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Visszaadja vagy beállítja a zoom objektum képét. Olvasás/írás [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a forma z-rendben betöltött pozícióját. A Shapes[0] a háttérben lévő formát adja, a Shapes[Shapes.Count - 1] pedig az előtérben lévő formát. Csak olvasás Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új placeholder-t ad hozzá, ha nincs, és beállítja a placeholder tulajdonságait a megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap placeholder formát (a layout vagy mester diáról származó formát, amelyből az aktuális forma öröklődik). Null értéket ad vissza, ha az aktuális forma nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma bélyegképét. Alapértelmezésként a ShapeThumbnailBounds.Shape bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Megkapja a forma megjelenített határait, amelyeket a renderelt tartalma alapján számol. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GraphicalObject](../graphicalobject)
* interfész [IZoomObject](../izoomobject)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->