---
title: SmartArt
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje diagram SmartArt
type: docs
weight: 10580
url: /cs/aspose.slides.smartart/smartart/
---
## SmartArt třída

Represents a SmartArt diagram

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Vrací kolekce všech uzlů v objektu SmartArt. Pouze ke čtení [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje titulek alternativního textu spojeného s tvarem. Čtení/zápis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Čtení/zápis [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Vrací nebo nastavuje styl barvy objektu SmartArt. Čtení/zápis [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze ke čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací uživatelská data tvaru. Pouze ke čtení [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti efektu. Pouze ke čtení [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti výplně. Pouze ke čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámečku tvaru. Čtení/zápis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zamykání tvaru. Pouze ke čtení [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Vrací nebo nastavuje výšku tvaru, měřenou v bodech. Čtení/zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/zápis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze ke čtení [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Čtení/zápis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Vrací nebo nastavuje možnost 'Označit jako dekorativní'. Čtení/zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupený. Pouze ke čtení Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Vrací nebo nastavuje stav diagramu SmartArt vzhledem k (zleva doprava) LTR nebo (zdoprava doleva) RTL, pokud diagram podporuje převrácení. Čtení/zápis Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze ke čtení Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Vrací nebo nastavuje rozvržení objektu SmartArt. Čtení/zápis [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti čáry. Pouze ke čtení [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je to potřeba. Čtení/zápis String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Vrací kolekce kořenových uzlů v objektu SmartArt. Pouze ke čtení [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze ke čtení UInt32. Viz také [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací nadřazený objekt GroupShape, pokud je tvar seskupený. Jinak vrací null. Pouze ke čtení [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný prvek pro tvar. Vrací null, pokud tvar nemá zástupný prvek. Pouze ke čtení [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze ke čtení [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Vrací nebo nastavuje rychlý styl objektu SmartArt. Čtení/zápis [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámečku tvaru. Čtení/zápis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen kolem osy z. Kladná hodnota označuje otočení ve směru hodinových ručiček; záporná hodnota označuje otočení proti směru hodinových ručiček. Čtení/zápis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zamykání tvaru. Pouze ke čtení [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 vlastnosti) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Pouze ke čtení [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají 3D vlastnosti. Pouze ke čtení [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiný kód. Protože tato hodnota může být přeřazena uživatelem nebo programově, nesmí být považována za trvalý jedinečný klíč. Pouze ke čtení UInt32. Viz také [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Vrací nebo nastavuje šířku tvaru, měřenou v bodech. Čtení/zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Vrací nebo nastavuje souřadnici x levého horního rohu tvaru, měřenou v bodech. Čtení/zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Vrací nebo nastavuje souřadnici y levého horního rohu tvaru, měřenou v bodech. Čtení/zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v z-řadě. Shapes[0] vrací tvar na konci z-řady a Shapes[Shapes.Count - 1] vrací tvar na začátku z-řady. Pouze ke čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavní snímku, ze kterého je aktuální tvar odvozen). Vrátí null, pokud aktuální tvar není odvozen. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Výchozí je typ ShapeThumbnailBounds.Shape pro ohraničení miniatury tvaru. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Vrací vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* třída [GraphicalObject](../../aspose.slides/graphicalobject)
* rozhraní [ISmartArt](../ismartart)
* jmenný prostor [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->