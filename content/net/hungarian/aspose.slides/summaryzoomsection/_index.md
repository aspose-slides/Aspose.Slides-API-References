---
title: SummaryZoomSection
second_title: Aspose.Sildes .NET API-referencia
description: Egy Summary Zoom Section objektumot reprezentál egy Summary Zoom keretben.
type: docs
weight: 10800
url: /hu/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection osztály

Representál egy Summary Zoom Section objektumot egy Summary Zoom keretben.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja az alakzathoz társított alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alakzathoz társított alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Megadja, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzat kapcsolati pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Visszaadja a Summary Zoom Section objektum szöveges leírását. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a alakzatra alkalmazott pixelhatásokat tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén null értéket adhat vissza, amelyeknek nincs effektus tulajdonsága. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a kitöltés formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén null értéket adhat vissza, amelyeknek nincs kitöltési tulajdonsága. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja az alakzat magasságát pontban. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megadja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé húzásra definiált hivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Visszaadja vagy beállítja egy zoom objektum kép típusát. Olvasás/írás [`ZoomImageType`](../zoomimagetype). Alapértelmezett érték: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a „Mark as decorative” beállítást. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megadja, hogy az alakzat csoportosítva van-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megadja, hogy az alakzat TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a vonal formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén null értéket adhat vissza, amelyeknek nincs vonal tulajdonsága. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja az alakzat nevét. Nem lehet null. Szükség esetén üres karakterlánc használható. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozódó egyedi azonosítót, amely az alakzat élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon rá a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Egyébként null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja az alakzat helyőrzőjét. Ha az alakzatnak nincs helyőrzője, null értéket ad vissza. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő bemutatóját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Visszaadja vagy beállítja a navigációs viselkedést a diavetítésben. Olvasás/írás Boolean. Alapértelmezett érték: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatási fokszámát. Pozitív érték az óramutató járásával megegyező forgást, negatív az ellenkezőjét jelzi. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 property) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Visszaadja vagy beállítja, hogy a Zoom a cél dia háttérképét használja-e. Olvasás/írás Boolean. Alapértelmezett érték: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja az alakzat szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Visszaadja vagy beállítja azt a szekcióobjektumot, amelyhez a Section Zoom objektum kapcsolódik. Olvasás/írás [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a 3D-effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusok esetén null értéket adhat vissza, amelyeknek nincs 3D tulajdonsága. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Visszaadja a Summary Zoom Section objektum szöveges címét. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Visszaadja vagy beállítja a Zoom és a dia közti átmenet időtartamát. Olvasás/írás Single. Alapértelmezett érték: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, bemutatóra korlátozódó azonosítót, amelyet kiegészítők vagy egyéb kód használhat. Mivel ezt az értéket a felhasználó vagy programkódból felülírhatják, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja az alakzat szélességét pontban. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja az alakzat bal-felső sarkának x-koordinátáját pontban. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja az alakzat bal-felső sarkának y-koordinátáját pontban. Olvasás/írás Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Visszaadja vagy beállítja a zoom objektum képét. Olvasás/írás [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy alakzat z-rendjében elfoglalt pozíciót. A Shapes[0] a z-rend leghátsó alakzatát, a Shapes[Shapes.Count - 1] a legelső alakzatát adja vissza. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait a megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző alakzatot (az elrendezésből és/vagy a minta diákról származó alakzat, amelyről a jelenlegi alakzat örökölt). Null érték visszatér, ha a jelenlegi alakzat nem örökölt. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat miniatűrjét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape miniatűr keret típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat miniatűrjét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Visszaadja az alakzat megjelenített határait, amelyet a renderelt tartalom alapján számítanak ki. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helyőrző. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [SectionZoomFrame](../sectionzoomframe)
* interfész [ISummaryZoomSection](../isummaryzoomsection)
* névtér [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->