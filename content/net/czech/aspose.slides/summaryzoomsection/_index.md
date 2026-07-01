---
title: SummaryZoomSection
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje objekt Summary Zoom Section v rámci Summary Zoom.
type: docs
weight: 10760
url: /cs/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection třída

Reprezentuje objekt Summary Zoom Section v rámu Summary Zoom.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s shape. Čtení/Zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s shape. Čtení/Zápis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude shape vykreslován v režimu černobílého zobrazení. Čtení/Zápis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na shape. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data shape. Pouze pro čtení [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Vrací textový popis objektu Summary Zoom Section. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na shape. Poznámka: může vrátit null pro některé typy shape, které nemají vlastnosti efektů. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti vyplnění pro shape. Poznámka: může vrátit null pro některé typy shape, které nemají vlastnosti vyplnění. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce shape. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zámky shape. Pouze pro čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Vrací nebo nastavuje výšku shape, měřenou v bodech. Čtení/Zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je shape skrytý. Čtení/Zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hyperodkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro přechod myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Vrací nebo nastavuje typ obrázku zoom objektu. Čtení/Zápis [`ZoomImageType`](../zoomimagetype). Výchozí hodnota: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Vrací nebo nastavuje možnost 'Mark as decorative'. Čtení/Zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je shape seskupený. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je shape TextHolder_PPT. Pouze pro čtení Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti čar pro shape. Poznámka: může vrátit null pro některé typy shape, které nemají vlastnosti čar. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název shape. Nesmí být null. Použijte prázdný řetězec, pokud je potřeba. Čtení/Zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost shape a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na shape z libovolného místa v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací rodičovský objekt GroupShape, pokud je shape seskupený. Jinak vrací null. Pouze pro čtení [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací placeholder pro shape. Vrací null, pokud shape nemá placeholder. Pouze pro čtení [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce shape. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Vrací nebo nastavuje chování navigace v prezentaci. Čtení/Zápis Boolean. Výchozí hodnota: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je daný shape otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Čtení/Zápis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zámky shape. Pouze pro čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 vlastnosti) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Vrací nebo nastavuje hodnotu určující, zda Zoom použije pozadí cílového snímku. Čtení/Zápis Boolean. Výchozí hodnota: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek shape. Pouze pro čtení [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Vrací nebo nastavuje objekt sekce, na který odkazuje objekt Section Zoom. Čtení/Zápis [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D vlastnosti efektu pro shape. Poznámka: může vrátit null pro některé typy shape, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Vrací textový nadpis objektu Summary Zoom Section. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Vrací nebo nastavuje dobu trvání přechodu mezi Zoom a snímkem. Čtení/Zápis Single. Výchozí hodnota: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tuto hodnotu může uživatel nebo program přepsat, nesmí být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Vrací nebo nastavuje šířku shape, měřenou v bodech. Čtení/Zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Vrací nebo nastavuje souřadnici x levého horního rohu shape, měřenou v bodech. Čtení/Zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Vrací nebo nastavuje souřadnici y levého horního rohu shape, měřenou v bodech. Čtení/Zápis Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Vrací nebo nastavuje obrázek pro zoom objekt. Čtení/Zápis [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici shape v z-pořadí. Shapes[0] vrací shape na konci z-pořadí a Shapes[Shapes.Count - 1] vrací shape na začátku z-pořadí. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový placeholder, pokud žádný neexistuje, a nastaví vlastnosti placeholderu na zadaný. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní tvar placeholderu (tvar z rozložení a/nebo hlavního snímku, ze kterého je aktuální shape odvozen). Vrátí null, pokud aktuální shape není odvozen. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu shape. Typ ShapeThumbnailBounds.Shape se používá jako výchozí. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Vrací vizuální hranice shape vypočtené z vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento shape není placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah Shape jako SVG soubor. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah Shape jako SVG soubor. |

### Viz také

* třída [SectionZoomFrame](../sectionzoomframe)
* rozhraní [ISummaryZoomSection](../isummaryzoomsection)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->