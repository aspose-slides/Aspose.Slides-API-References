---
title: ICell class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/icell/
---
## ICell třída

Představuje buňku v tabulce.

Typ ICell vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/cs/aspose.slides/icell/offset_x/) | Vrací vzdálenost z levé strany tabulky k levé straně buňky.<br/>            Jen pro čtení **float**. |
| [`offset_y`](/slides/python-net/cs/aspose.slides/icell/offset_y/) | Vrací vzdálenost z horní strany tabulky k horní straně buňky.<br/>            Jen pro čtení **float**. |
| [`first_row_index`](/slides/python-net/cs/aspose.slides/icell/first_row_index/) | Vrací index první řady, kterou buňka pokrývá.<br/>            Jen pro čtení **int**. |
| [`first_column_index`](/slides/python-net/cs/aspose.slides/icell/first_column_index/) | Vrací index první sloupce, který buňka pokrývá.<br/>            Jen pro čtení **int**. |
| [`width`](/slides/python-net/cs/aspose.slides/icell/width/) | Vrací šířku buňky.<br/>            Jen pro čtení **float**. |
| [`height`](/slides/python-net/cs/aspose.slides/icell/height/) | Vrací výšku buňky.<br/>            Jen pro čtení **float**. |
| [`minimal_height`](/slides/python-net/cs/aspose.slides/icell/minimal_height/) | Vrací minimální výšku buňky.<br/>            Jedná se o součet minimálních výšek všech řad, které buňka pokrývá.<br/>            Jen pro čtení **float**. |
| [`margin_left`](/slides/python-net/cs/aspose.slides/icell/margin_left/) | Vrací nebo nastavuje levý okraj v TextFrame.<br/>            Čtení/Zápis **float**. |
| [`margin_right`](/slides/python-net/cs/aspose.slides/icell/margin_right/) | Vrací nebo nastavuje pravý okraj v TextFrame.<br/>            Čtení/Zápis **float**. |
| [`margin_top`](/slides/python-net/cs/aspose.slides/icell/margin_top/) | Vrací nebo nastavuje horní okraj v TextFrame.<br/>            Čtení/Zápis **float**. |
| [`margin_bottom`](/slides/python-net/cs/aspose.slides/icell/margin_bottom/) | Vrací nebo nastavuje spodní okraj v TextFrame.<br/>            Čtení/Zápis **float**. |
| [`text_vertical_type`](/slides/python-net/cs/aspose.slides/icell/text_vertical_type/) | Vrací nebo nastavuje typ vertikálního textu.<br/>            Čtení/Zápis [`TextVerticalType`](/slides/python-net/cs/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/cs/aspose.slides/icell/text_anchor_type/) | Vrací nebo nastavuje typ ukotvení textu.<br/>            Čtení/Zápis [`TextAnchorType`](/slides/python-net/cs/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/cs/aspose.slides/icell/anchor_center/) | Určuje, zda je textové pole vycentrováno uvnitř buňky.<br/>            Čtení/Zápis **bool**. |
| [`first_column`](/slides/python-net/cs/aspose.slides/icell/first_column/) | Získává první sloupec buňky.<br/>            Jen pro čtení [`IColumn`](/slides/python-net/cs/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/cs/aspose.slides/icell/first_row/) | Získává první řadu buňky.<br/>            Jen pro čtení [`IRow`](/slides/python-net/cs/aspose.slides/irow). |
| [`col_span`](/slides/python-net/cs/aspose.slides/icell/col_span/) | Vrací počet sloupců v mřížce nadřazené tabulky, které má aktuální buňka pokrýt.<br/>            Toto vlastnost umožňuje buňkám vzhled sloučených, protože přesahují vertikální hranice jiných buněk v tabulce.<br/>            Jen pro čtení **int**. |
| [`row_span`](/slides/python-net/cs/aspose.slides/icell/row_span/) | Vrací počet řad, které sloučená buňka pokrývá. Toto se používá v kombinaci<br/>            s atributem vMerge u jiných buněk pro specifikaci úvodní buňky<br/>            horizontálního sloučení.<br/>            Jen pro čtení **int**. |
| [`text_frame`](/slides/python-net/cs/aspose.slides/icell/text_frame/) | Vrací textový rámec buňky.<br/>            Jen pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`table`](/slides/python-net/cs/aspose.slides/icell/table/) | Vrací nadřazený objekt Table pro buňku.<br/>            Jen pro čtení [`ITable`](/slides/python-net/cs/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/cs/aspose.slides/icell/is_merged_cell/) | Vrací true, pokud je buňka sloučena s jakoukoliv přizpůsobenou buňkou, jinak false.<br/>            Jen pro čtení **bool**. |
| [`cell_format`](/slides/python-net/cs/aspose.slides/icell/cell_format/) | Vrací objekt CellFormat, který obsahuje vlastnosti formátování pro tuto buňku.<br/>            Jen pro čtení [`ICellFormat`](/slides/python-net/cs/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/cs/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/icell/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/cs/aspose.slides/icell/split_by_col_span/#int) | Rozdělí buňku na dvě buňky podle indexu sloupce. |
| [`split_by_row_span(self, index)`](/slides/python-net/cs/aspose.slides/icell/split_by_row_span/#int) | Rozdělí buňku na dvě buňky podle indexu řady. |
| [`split_by_height(self, height)`](/slides/python-net/cs/aspose.slides/icell/split_by_height/#float) | Rozdělí buňku podle výšky. |
| [`split_by_width(self, width)`](/slides/python-net/cs/aspose.slides/icell/split_by_width/#float) | Rozdělí buňku podle šířky. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)