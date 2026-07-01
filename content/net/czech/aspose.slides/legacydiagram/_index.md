---
title: LegacyDiagram
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Reprezentuje objekt starého diagramu.
type: docs
weight: 7650
url: /cs/aspose.slides/legacydiagram/
---
## LegacyDiagram třída

Representuje objekt starého diagramu.

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrátí nebo nastaví alternativní text spojený s tvarem. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrátí nebo nastaví nadpis alternativního textu spojeného s tvarem. Read/write String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | Umožňuje získat základní rozhraní IGraphicalObject. Read-only [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak se tvarem bude zobrazovat v černobílém režimu. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrátí počet připojovacích míst na tvaru. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrátí vlastní data tvaru. Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrátí objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti efektu. Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrátí objekt FillFormat, který obsahuje vlastnosti výplně tvaru. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti výplně. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrátí nebo nastaví vlastnosti rámce tvaru. Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrátí zámky tvaru. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Získá nebo nastaví výšku tvaru, měřenou v bodech. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrátí nebo nastaví hyperodkaz definovaný pro kliknutí myší. Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrátí správce hyperodkazů. Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrátí nebo nastaví hyperodkaz definovaný pro přejetí myší. Read/write [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Získá nebo nastaví možnost 'Označit jako dekorativní'. Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupen. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrátí objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti čáry. Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrátí nebo nastaví název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je potřeba. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrátí jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar z libovolného místa v dokumentu. Read-only UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrátí nadřazený objekt GroupShape, pokud je tvar seskupen. Jinak vrátí null. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrátí zástupný prvek pro tvar. Vrátí null, pokud tvar nemá zástupný prvek. Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrátí nadřazenou prezentaci snímku. Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrátí nebo nastaví surové vlastnosti rámce tvaru. Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrátí nebo nastaví počet stupňů, o které je konkrétní tvar natočen kolem osy z. Kladná hodnota značí otáčení po směru hodinových ručiček; záporná hodnota značí otáčení proti směru hodinových ručiček. Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrátí zámky tvaru. Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrátí nadřazený snímek tvaru. Read-only [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrátí objekt ThreeDFormat, který obsahuje 3D efektové vlastnosti pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají 3D vlastnosti. Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrátí interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože může být tento hodnotou přidělena uživatelem nebo programově, neměla by být považována za trvalý jedinečný klíč. Read-only UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Získá nebo nastaví šířku tvaru, měřenou v bodech. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Získá nebo nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Získá nebo nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrátí pozici tvaru v z-řazení. Shapes[0] vrací tvar v zadní části z-řazení a Shapes[Shapes.Count - 1] vrací tvar v přední části z-řazení. Read-only Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | Převede starý diagram na editovatelný skupinový tvar. Vytvořený objekt GroupShape je přidán k nadřazenému skupinovému tvaru ve stejné pozici. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | Převede starý diagram na editovatelný objekt SmartArt. Vytvořený objekt SmartArt je přidán k nadřazenému skupinovému tvaru ve stejné pozici. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrátí základní zástupný tvar (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar odvozen). Vrátí null, pokud aktuální tvar není zděděn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrátí miniaturu tvaru. Ve výchozím nastavení se používá typ ShapeThumbnailBounds.Shape pro ohraničení miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrátí miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako SVG soubor. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako SVG soubor. |

### Viz také

* třída [GraphicalObject](../graphicalobject)
* rozhraní [ILegacyDiagram](../ilegacydiagram)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->