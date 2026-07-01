---
title: Table
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Představuje tabulku na snímku.
type: docs
weight: 10840
url: /cs/aspose.slides/table/
---
## Table třída

Představuje tabulku na snímku.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/Zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Čtení/Zápis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Čtení/Zápis [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Vrací kolekci sloupců. Pouze čtení [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze čtení [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty použité na tvaru. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti efektu. Pouze čtení [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Vrací objekt TableFormat.FillFormat obsahující formátování výplně pro tabulku. Pouze čtení [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Určuje, zda má být první sloupec tabulky vykreslen se zvláštním formátováním. Čtení/Zápis Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Určuje, zda má být první řádek tabulky vykreslen se zvláštním formátováním. Čtení/Zápis Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámečku tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zámky tvaru. Pouze čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Získává nebo nastavuje výšku tvaru v bodech. Čtení/Zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/Zápis Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Čtení/Zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Čtení/Zápis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Získává nebo nastavuje možnost „Označit jako dekorativní“. Čtení/Zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupen. Pouze čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze čtení Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Vrací buňku na zadaných indexech sloupce a řádku. Pouze čtení [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Určuje, zda má být poslední sloupec tabulky vykreslen se zvláštním formátováním. Čtení/Zápis Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Určuje, zda má být poslední řádek tabulky vykreslen se zvláštním formátováním. Čtení/Zápis Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti čáry. Pouze čtení [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nemůže být null. Pokud je potřeba, použijte prázdný řetězec. Čtení/Zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou dobu existence tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze čtení UInt32. Viz také [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací rodičovský objekt GroupShape, pokud je tvar seskupen. Jinak vrací null. Pouze čtení [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný prvek pro tvar. Vrací null, pokud tvar nemá zástupný prvek. Pouze čtení [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze čtení [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámečku tvaru. Čtení/Zápis [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Určuje, zda má tabulka pravý-levý směr čtení. Čtení/Zápis Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je tvar otočen kolem osy z. Kladná hodnota znamená otáčení po směru hodinových ručiček; záporná hodnota otáčení proti směru hodinových ručiček. Čtení/Zápis Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Vrací kolekci řádků. Pouze čtení [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zámky tvaru. Pouze čtení [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací rodičovský snímek tvaru. Pouze čtení [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Získává nebo nastavuje vestavěný styl tabulky. Čtení/Zápis [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Vrací objekt TableFormat, který obsahuje vlastnosti formátování pro tuto tabulku. Pouze čtení [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D vlastnosti efektu pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají 3D vlastnosti. Pouze čtení [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací vnitřní identifikátor v rámci prezentace určený pro doplňky nebo jiný kód. Protože tuto hodnotu může uživatel nebo program přepsat, neměla by být považována za trvalý jedinečný klíč. Pouze čtení UInt32. Viz také [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Čtení/Zápis Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Získává nebo nastavuje šířku tvaru v bodech. Čtení/Zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Získává nebo nastavuje x-souřadnici levého horního rohu tvaru v bodech. Čtení/Zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Získává nebo nastavuje y-souřadnici levého horního rohu tvaru v bodech. Čtení/Zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v z-řazení. Shapes[0] vrací tvar na pozadí z-řazení a Shapes[Shapes.Count - 1] vrací tvar v popředí z-řazení. Pouze čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud žádný není, a nastaví vlastnosti zástupného prvku na určený. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). Vrací null, pokud aktuální tvar není zděděn. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Výchozí typ je ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získává vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Spojí sousední buňky. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Nastaví definované vlastnosti formátu odstavce pro všechny odstavce buněk tabulky. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Nastaví definované vlastnosti formátu úseku pro všechny úseky buněk tabulky. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Nastaví definované vlastnosti formátu textového rámečku pro všechny textové rámečky buněk tabulky. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* třída [GraphicalObject](../graphicalobject)
* rozhraní [ITable](../itable)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->