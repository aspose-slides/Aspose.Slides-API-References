---
title: Cell
second_title: Aspose.Sildes .NET API hivatkozás
description: Egy táblázat celláját reprezentálja.
type: docs
weight: 1130
url: /hu/aspose.slides/cell/
---
## Cell osztály

Egy táblázat celláját reprezentálja.

```csharp
public class Cell : ICell
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Megállapítja, hogy a szövegdoboz középre van-e helyezve a cellában. Olvasás/írás Boolean. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Visszaadja a CellFormat objektumot, amely a cella formázási tulajdonságait tartalmazza. Csak olvasható [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Visszaadja a szülő tábla táblarácsában lévő rácsoszlopok számát, amelyet az aktuális cella átnyúlik. Ez a tulajdonság lehetővé teszi, hogy a cellák egyesített megjelenést kapjanak, mivel függőleges határokat nyújtanak át más cellák felett a táblázatban. Csak olvasható Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Lekéri a cella első oszlopát. Csak olvasható [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Visszaadja az első oszlop indexét, amelyet a cella lefed. Csak olvasható Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Lekéri a cella első sorát. Csak olvasható [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Visszaadja az első sor indexét, amelyet a cella lefed. Csak olvasható Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Visszaadja a cella magasságát. Csak olvasható Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Igaz értéket ad vissza, ha a cella egyesített bármely módosított cellával, egyébként hamis. Csak olvasható Boolean. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Visszaadja vagy beállítja az alsó margót egy TextFrame-ben. Olvasás/írás Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Visszaadja vagy beállítja a bal margót egy TextFrame-ben. Olvasás/írás Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Visszaadja vagy beállítja a jobb margót egy TextFrame-ben. Olvasás/írás Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Visszaadja vagy beállítja a felső margót egy TextFrame-ben. Olvasás/írás Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Visszaadja a cella minimális magasságát. Ez a cella által lefedett összes sor minimális magasságának összege. Csak olvasható Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Visszaadja a táblázat bal oldalától a cella bal oldaláig terjedő távolságot. Csak olvasható Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Visszaadja a táblázat felső oldalától a cella felső oldaláig terjedő távolságot. Csak olvasható Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Visszaadja a cella szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Visszaadja a sorok számát, amelyen egy egyesített cella átnyúlik. Ez a vMerge attribútummal más cellákon együtt használható a vízszintes egyesítés kezdőcellájának meghatározásához. Csak olvasható Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Visszaadja a cella szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Visszaadja a cella szülő Table objektumot. Csak olvasható [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Visszaadja vagy beállítja a szövegankor típusát. Olvasás/írás [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Visszaadja a cella szövegdobozát. Csak olvasható [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Visszaadja vagy beállítja a függőleges szöveg típusát. Olvasás/írás [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Visszaadja a cella szélességét. Csak olvasható Double. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Feldarabolja a cellát két cellára az oszlop indexe szerint. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Feldarabolja a cellát magasság szerint. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Feldarabolja a cellát két cellára a sor indexe szerint. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Feldarabolja a cellát szélesség szerint. |

### Lásd még

* interfész [ICell](../icell)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->