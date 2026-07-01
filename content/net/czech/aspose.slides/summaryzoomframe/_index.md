---
title: SummaryZoomFrame
second_title: Aspose.Sildes pro .NET API Reference
description: Představuje objekt Summary Zoom na snímku.
type: docs
weight: 10750
url: /cs/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame třída

Představuje objekt Summary Zoom na snímku.

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje nadpis alternativního textu spojeného s tvarem. Čtení/zápis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Čtení/zápis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti efektu. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně tvaru. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti výplně. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/zápis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zamčení tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Přijímá nebo nastavuje výšku tvaru, měřenou v bodech. Čtení/zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/zápis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro přechod kurzoru myši. Čtení/zápis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Přijímá nebo nastavuje volbu 'Označit jako dekorativní'. Čtení/zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupený. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | Získává rozložení sekcí Summary Zoom v rámci. Výchozí hodnota je GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti čáry. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je potřeba. Čtení/zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rozsahu snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt GroupShape rodiče, pokud je tvar seskupený. V opačném případě vrací null. Pouze pro čtení [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný prvek tvaru. Vrací null, pokud tvar nemá žádný zástupný prvek. Pouze pro čtení [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Čtení/zápis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Čtení/zápis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zamčení tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 vlastnosti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Pouze pro čtení [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | Získává [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) pro objekt Summary Zoom Frame. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D vlastnosti efektu pro tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rozsahu prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být uživatelem nebo programově přepsána, neměla by být považována za trvalý jedinečný klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Získává nebo nastavuje šířku tvaru, měřenou v bodech. Čtení/zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Získává nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Čtení/zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Získává nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Čtení/zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v z-orderu. Shapes[0] vrací tvar na zadní pozici z-orderu a Shapes[Shapes.Count - 1] vrací tvar na přední pozici z-orderu. Pouze pro čtení Int32. |

## Metody

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). Vrátí null, pokud aktuální tvar není zděděn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Typ ShapeThumbnailBounds.Shape pro omezení miniatury tvaru je použit jako výchozí. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získává vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* třída [GraphicalObject](../graphicalobject)
* rozhraní [ISummaryZoomFrame](../isummaryzoomframe)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->