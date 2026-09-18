---
title: ICell class
second_title: Aspose.Slides a Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/icell/
---
## ICell osztály

Egy cellát reprezentál egy táblázatban.

Az ICell típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`offset_x`](/slides/python-net/hu/aspose.slides/icell/offset_x/) | Visszaadja a táblázat bal oldalától a cella bal oldaláig mért távolságot.<br/>            Csak olvasható **float**. |
| [`offset_y`](/slides/python-net/hu/aspose.slides/icell/offset_y/) | Visszaadja a táblázat felső oldalától a cella felső oldaláig mért távolságot.<br/>            Csak olvasható **float**. |
| [`first_row_index`](/slides/python-net/hu/aspose.slides/icell/first_row_index/) | Visszaadja a cella által lefedett első sor indexét.<br/>            Csak olvasható **int**. |
| [`first_column_index`](/slides/python-net/hu/aspose.slides/icell/first_column_index/) | Visszaadja a cella által lefedett első oszlop indexét.<br/>            Csak olvasható **int**. |
| [`width`](/slides/python-net/hu/aspose.slides/icell/width/) | Visszaadja a cella szélességét.<br/>            Csak olvasható **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/icell/height/) | Visszaadja a cella magasságát.<br/>            Csak olvasható **float**. |
| [`minimal_height`](/slides/python-net/hu/aspose.slides/icell/minimal_height/) | Visszaadja a cella minimális magasságát.<br/>            Ez a cella által lefedett összes sor minimális magasságának összege.<br/>            Csak olvasható **float**. |
| [`margin_left`](/slides/python-net/hu/aspose.slides/icell/margin_left/) | Visszaadja vagy beállítja a bal margót egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_right`](/slides/python-net/hu/aspose.slides/icell/margin_right/) | Visszaadja vagy beállítja a jobb margót egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_top`](/slides/python-net/hu/aspose.slides/icell/margin_top/) | Visszaadja vagy beállítja a felső margót egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_bottom`](/slides/python-net/hu/aspose.slides/icell/margin_bottom/) | Visszaadja vagy beállítja az alsó margót egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`text_vertical_type`](/slides/python-net/hu/aspose.slides/icell/text_vertical_type/) | Visszaadja vagy beállítja a függőleges szöveg típusát.<br/>            Olvasás/írás [`TextVerticalType`](/slides/python-net/hu/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/hu/aspose.slides/icell/text_anchor_type/) | Visszaadja vagy beállítja a szöveghorgony típusát.<br/>            Olvasás/írás [`TextAnchorType`](/slides/python-net/hu/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/hu/aspose.slides/icell/anchor_center/) | Meghatározza, hogy a szövegdoboz középre legyen-e igazítva a cellán belül.<br/>            Olvasás/írás **bool**. |
| [`first_column`](/slides/python-net/hu/aspose.slides/icell/first_column/) | A cella első oszlopát adja vissza.<br/>            Csak olvasható [`IColumn`](/slides/python-net/hu/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/hu/aspose.slides/icell/first_row/) | A cella első sorát adja vissza.<br/>            Csak olvasható [`IRow`](/slides/python-net/hu/aspose.slides/irow). |
| [`col_span`](/slides/python-net/hu/aspose.slides/icell/col_span/) | Visszaadja a szülő táblázat táblarácsájában lévő rácsoszlopok számát, amelyet az aktuális cella átfog.<br/>            Ez a tulajdonság lehetővé teszi, hogy a cellák egyesítettnek tűnjenek, mivel átfedik más cellák függőleges határait a táblázatban.<br/>            Csak olvasható **int**. |
| [`row_span`](/slides/python-net/hu/aspose.slides/icell/row_span/) | Visszaadja a sorok számát, amelyet egy egyesített cella átfog. Ezt a vMerge attribútummal más cellákon kombinálva használják, hogy meghatározzák a vízszintes egyesítés kezdőcelláját.<br/>            Csak olvasható **int**. |
| [`text_frame`](/slides/python-net/hu/aspose.slides/icell/text_frame/) | Visszaadja egy cella szövegdobozát.<br/>            Csak olvasható [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`table`](/slides/python-net/hu/aspose.slides/icell/table/) | Visszaadja egy cellához tartozó szülő Table objektumot.<br/>            Csak olvasható [`ITable`](/slides/python-net/hu/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/hu/aspose.slides/icell/is_merged_cell/) | Igaz értéket ad vissza, ha a cella egyesítve van bármely módosított cellával, különben hamis.<br/>            Csak olvasható **bool**. |
| [`cell_format`](/slides/python-net/hu/aspose.slides/icell/cell_format/) | Visszaadja a CellFormat objektumot, amely a cella formázási tulajdonságait tartalmazza.<br/>            Csak olvasható [`ICellFormat`](/slides/python-net/hu/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/hu/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/icell/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/hu/aspose.slides/icell/split_by_col_span/#int) | Felosztja a cellát két cellára az oszlop indexe alapján. |
| [`split_by_row_span(self, index)`](/slides/python-net/hu/aspose.slides/icell/split_by_row_span/#int) | Felosztja a cellát két cellára a sor indexe alapján. |
| [`split_by_height(self, height)`](/slides/python-net/hu/aspose.slides/icell/split_by_height/#float) | Felosztja a cellát magasság alapján. |
| [`split_by_width(self, width)`](/slides/python-net/hu/aspose.slides/icell/split_by_width/#float) | Felosztja a cellát szélesség alapján. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)