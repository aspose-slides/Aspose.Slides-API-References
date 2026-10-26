---
title: Cell class
second_title: Aspose.Slides Python .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/cell/
---
## Cell osztály

Egy táblázat celláját ábrázolja.

A Cell típus a következő elemeket teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`offset_x`](/slides/python-net/hu/aspose.slides/cell/offset_x/) | Visszaadja a táblázat bal oldalától a cella bal oldaláig mért távolságot.<br/>            Csak olvasható **float**. |
| [`offset_y`](/slides/python-net/hu/aspose.slides/cell/offset_y/) | Visszaadja a táblázat felső oldalától a cella felső oldaláig mért távolságot.<br/>            Csak olvasható **float**. |
| [`first_row_index`](/slides/python-net/hu/aspose.slides/cell/first_row_index/) | Visszaadja az első sor indexét, amelyet a cella fed.<br/>            Csak olvasható **int**. |
| [`first_column_index`](/slides/python-net/hu/aspose.slides/cell/first_column_index/) | Visszaadja az első oszlop indexét, amelyet a cella fed.<br/>            Csak olvasható **int**. |
| [`width`](/slides/python-net/hu/aspose.slides/cell/width/) | Visszaadja a cella szélességét.<br/>            Csak olvasható **float**. |
| [`height`](/slides/python-net/hu/aspose.slides/cell/height/) | Visszaadja a cella magasságát.<br/>            Csak olvasható **float**. |
| [`minimal_height`](/slides/python-net/hu/aspose.slides/cell/minimal_height/) | Visszaadja a cella minimális magasságát.<br/>            Ez a cella által lefedett összes sor minimális magasságának összege.<br/>            Csak olvasható **float**. |
| [`margin_left`](/slides/python-net/hu/aspose.slides/cell/margin_left/) | Visszaadja vagy beállítja a bal margót egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_right`](/slides/python-net/hu/aspose.slides/cell/margin_right/) | Visszaadja vagy beállítja a jobb margót egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_top`](/slides/python-net/hu/aspose.slides/cell/margin_top/) | Visszaadja vagy beállítja a felső margót egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_bottom`](/slides/python-net/hu/aspose.slides/cell/margin_bottom/) | Visszaadja vagy beállítja az alsó margót egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`text_vertical_type`](/slides/python-net/hu/aspose.slides/cell/text_vertical_type/) | Visszaadja vagy beállítja a függőleges szöveg típusát.<br/>            Olvasás/írás [`TextVerticalType`](/slides/python-net/hu/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/hu/aspose.slides/cell/text_anchor_type/) | Visszaadja vagy beállítja a szöveg horgonztípusát.<br/>            Olvasás/írás [`TextAnchorType`](/slides/python-net/hu/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/hu/aspose.slides/cell/anchor_center/) | Meghatározza, hogy a szövegdoboz középre van-e helyezve a cellán belül.<br/>            Olvasás/írás **bool**. |
| [`first_row`](/slides/python-net/hu/aspose.slides/cell/first_row/) | Lekéri a cella első sorát.<br/>            Csak olvasható [`IRow`](/slides/python-net/hu/aspose.slides/irow). |
| [`first_column`](/slides/python-net/hu/aspose.slides/cell/first_column/) | Lekéri a cella első oszlopát.<br/>            Csak olvasható [`IColumn`](/slides/python-net/hu/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/hu/aspose.slides/cell/col_span/) | Visszaadja a szülő táblázat táblarácsának oszlopainak számát,<br/>            amelyet az aktuális cella lefed. Ez a tulajdonság lehetővé teszi, hogy a cellák<br/>            egyesültnek tűnjenek, mivel függőleges határokat fednek le más cellákban a táblázatban.<br/>            Csak olvasható **int**. |
| [`row_span`](/slides/python-net/hu/aspose.slides/cell/row_span/) | Visszaadja a sorok számát, amelyet egy egyesített cella lefed. Ezt a vMerge attribútummal együtt használják más cellákon, hogy meghatározzák a vízszintes egyesítés kezdőcelláját.<br/>            Csak olvasható **int**. |
| [`text_frame`](/slides/python-net/hu/aspose.slides/cell/text_frame/) | Visszaadja a cella szövegkeretét.<br/>            Csak olvasható [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`table`](/slides/python-net/hu/aspose.slides/cell/table/) | Visszaadja a cellához tartozó szülő Table objektumot.<br/>            Csak olvasható [`ITable`](/slides/python-net/hu/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/hu/aspose.slides/cell/is_merged_cell/) | Igazat ad vissza, ha a cella bármely módosított cellával egyesített, egyébként hamis.<br/>            Csak olvasható **bool**. |
| [`cell_format`](/slides/python-net/hu/aspose.slides/cell/cell_format/) | Visszaadja a CellFormat objektumot, amely a cella formázási tulajdonságait tartalmazza.<br/>            Csak olvasható [`ICellFormat`](/slides/python-net/hu/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/hu/aspose.slides/cell/slide/) | Visszaadja a cella szülő diát.<br/>            Csak olvasható [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/hu/aspose.slides/cell/presentation/) | Visszaadja a cella szülő prezentációját.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/hu/aspose.slides/cell/split_by_col_span/#int) | Felosztja a cellát két cellára az oszlop indexe alapján. |
| [`split_by_row_span(self, index)`](/slides/python-net/hu/aspose.slides/cell/split_by_row_span/#int) | Felosztja a cellát két cellára a sor indexe alapján. |
| [`split_by_height(self, height)`](/slides/python-net/hu/aspose.slides/cell/split_by_height/#float) | Felosztja a cellát magasság szerint. |
| [`split_by_width(self, width)`](/slides/python-net/hu/aspose.slides/cell/split_by_width/#float) | Felosztja a cellát szélesség szerint. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)