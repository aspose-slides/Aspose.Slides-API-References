---
title: SummaryZoomSection
second_title: Aspose.Sildes .NET API Referenciája
description: Összegző Zoom szakasz objektumot képvisel egy Summary Zoom keretben.
type: docs
weight: 10760
url: /hu/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection osztály

A Summary Zoom keretben lévő Summary Zoom Section objektumot képviseli.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a alakzathoz kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a alakzathoz kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság megadja, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Visszaadja a Summary Zoom Section objektum szöveges leírását. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely pixelhatásokat tartalmaz az alakzatra vonatkozóan. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs effektustulajdonsága, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely kitöltési formázási tulajdonságokat tartalmaz az alakzatra vonatkozóan. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs kitöltéstulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekérdezi vagy beállítja a forma magasságát pontokban. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozáskezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé húzva definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Lekérdezi vagy beállítja a zoom objektum kép típusát. Olvasás/írás [`ZoomImageType`](../zoomimagetype). Alapértelmezett érték: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lekérdezi vagy beállítja a „Mark as decorative” beállítást. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a forma csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely vonalformázási tulajdonságokat tartalmaz az alakzatra vonatkozóan. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs vonaltulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a forma nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozódó egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helyőrzőjét. Null értéket ad vissza, ha a formának nincs helyőrzője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a diát tartalmazó bemutató szülőjét. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Lekérdezi vagy beállítja a navigáció viselkedését a diavetítésben. Olvasás/írás Boolean. Alapértelmezett érték: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott forma Z tengely körüli forgatási fokszámát. A pozitív érték óramutató járásával megegyező forgatást jelez; a negatív érték ellentétes irányú forgatást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 property) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Lekérdezi vagy beállítja, hogy a Zoom használja-e a cél-diára vonatkozó háttérképet. Olvasás/írás Boolean. Alapértelmezett érték: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülődiáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Lekérdezi vagy beállítja azt a szakaszobjektumot, amelyre a Section Zoom hivatkozik. Olvasás/írás [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely 3D effektustulajdonságokat tartalmaz a forma számára. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Visszaadja a Summary Zoom Section objektum szöveges címét. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Lekérdezi vagy beállítja a Zoom és a dia közti átmenet időtartamát. Olvasás/írás Single. Alapértelmezett érték: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, bemutatóra korlátozódó azonosítót, amelyet kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy a program módosíthatja, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekérdezi vagy beállítja a forma szélességét pontokban. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekérdezi vagy beállítja a forma bal felső sarkának x koordinátáját pontokban. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekérdezi vagy beállítja a forma bal felső sarkának y koordinátáját pontokban. Olvasás/írás Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Lekérdezi vagy beállítja a zoom objektum képét. Olvasás/írás [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja a forma z-rendben való pozícióját. A Shapes[0] a z-rend leghátrul lévő alakzatát adja vissza, a Shapes[Shapes.Count - 1] pedig az első helyen lévő alakzatot. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait a megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző formát (a layout vagy a mester dia formáját, amelyből a jelenlegi forma örököl). Null értéket ad vissza, ha a jelenlegi forma nem örökölt. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekérdezi a forma vizuális határait, amelyeket a megjelenített tartalma alapján számít. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem helyőrző. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti a forma tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Elmenti a forma tartalmát SVG fájlként. |

### Lásd még

* osztály [SectionZoomFrame](../sectionzoomframe)
* interfész [ISummaryZoomSection](../isummaryzoomsection)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->