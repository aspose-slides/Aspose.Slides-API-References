---
title: SectionZoomFrame
second_title: Aspose.Sildes .NET API Referencia
description: Egy diában lévő Section Zoom objektumot képviseli.
type: docs
weight: 9780
url: /hu/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame osztály

A Section Zoom objektumot képviseli egy diában.

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a alakzathoz kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a alakzathoz kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzaton lévő csatlakozási pontok számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely pixel-effekteket tartalmaz az alakzatra alkalmazva. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs effektustulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely kitöltési formázási tulajdonságokat tartalmaz egy alakzat számára. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs kitöltéstulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekéri vagy beállítja az alakzat magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozáskezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Lekéri vagy beállítja egy zoom objektum képtípusát. Olvasás/írás [`ZoomImageType`](../zoomimagetype). Alapértelmezett érték: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lekéri vagy beállítja a „Mark as decorative” opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely vonalformázási tulajdonságokat tartalmaz egy alakzat számára. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs vonaltulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára vonatkozó egyedi azonosítót, amely állandó a forma életciklusa alatt, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely pontjáról. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja egy alakzat helykitöltőjét. Null értéket ad vissza, ha az alakzatnak nincs helykitöltője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a forma nyers keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Lekéri vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás Boolean. Alapértelmezett érték: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli elforgatásának fokszámát. A pozitív érték az óramutató járásának irányú forgást jelzi; a negatív érték az óramutatóval ellentétes forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 tulajdonság) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Lekéri vagy beállítja azt az értéket, amely meghatározza, hogy a Zoom a cél dia háttérét használja-e. Olvasás/írás Boolean. Alapértelmezett érték: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja az alakzat szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Lekéri vagy beállítja azt a szekcióobjektumot, amelyre a Section Zoom objektum hivatkozik. Olvasás/írás [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely egy alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Lekéri vagy beállítja a Zoom és a dia közötti átmenet időtartamát. Olvasás/írás Single. Alapértelmezett érték: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra vonatkozó azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozott módon újra lehet rendelni, nem szabad tartós egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekéri vagy beállítja az alakzat szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekéri vagy beállítja az alakzat bal felső sarkának x koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekéri vagy beállítja az alakzat bal felső sarkának y koordinátáját pontban mérve. Olvasás/írás Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Lekéri vagy beállítja a zoom objektum képét. Olvasás/írás [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy alakzat helyzetét a z-sorrendben. A Shapes[0] a z-sorrend hátuljában lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] pedig a lánc előtti alakzatot. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helykitöltőt ad hozzá, ha nincs, és beállítja a helykitöltő tulajdonságait egy megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helykitöltő alakzatot (az elrendezésből és/vagy mesterdiából származó alakzat, amelyből a jelenlegi alakzat örökölt). Null értéket ad vissza, ha a jelenlegi alakzat nem örökölt. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri az alakzat vizuális határait, amelyet a renderelt tartalma alapján számít ki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helykitöltő. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Mentse az alakzat tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Mentse az alakzat tartalmát SVG fájlként. |

### Lásd még

* osztály [ZoomObject](../zoomobject)
* interfész [ISectionZoomFrame](../isectionzoomframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->