---
title: ICell class
second_title: Aspose.Slides für Python via .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/icell/
---
## ICell Klasse

Represents a cell in a table.

The ICell type exposes the following members:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/de/aspose.slides/icell/offset_x/) | Liefert die Entfernung von der linken Seite einer Tabelle zur linken Seite einer Zelle.<br/>            Nur lesbar **float**. |
| [`offset_y`](/slides/python-net/de/aspose.slides/icell/offset_y/) | Liefert die Entfernung von der oberen Seite einer Tabelle zur oberen Seite einer Zelle.<br/>            Nur lesbar **float**. |
| [`first_row_index`](/slides/python-net/de/aspose.slides/icell/first_row_index/) | Liefert den Index der ersten Zeile, die von der Zelle abgedeckt wird.<br/>            Nur lesbar **int**. |
| [`first_column_index`](/slides/python-net/de/aspose.slides/icell/first_column_index/) | Liefert den Index der ersten Spalte, die von der Zelle abgedeckt wird.<br/>            Nur lesbar **int**. |
| [`width`](/slides/python-net/de/aspose.slides/icell/width/) | Liefert die Breite der Zelle.<br/>            Nur lesbar **float**. |
| [`height`](/slides/python-net/de/aspose.slides/icell/height/) | Liefert die Höhe der Zelle.<br/>            Nur lesbar **float**. |
| [`minimal_height`](/slides/python-net/de/aspose.slides/icell/minimal_height/) | Liefert die minimale Höhe einer Zelle. Dies ist die Summe der minimalen Höhen aller von der Zelle abgedeckten Zeilen.<br/>            Nur lesbar **float**. |
| [`margin_left`](/slides/python-net/de/aspose.slides/icell/margin_left/) | Liefert oder setzt den linken Rand in einem TextFrame.<br/>            Lesen/Schreiben **float**. |
| [`margin_right`](/slides/python-net/de/aspose.slides/icell/margin_right/) | Liefert oder setzt den rechten Rand in einem TextFrame.<br/>            Lesen/Schreiben **float**. |
| [`margin_top`](/slides/python-net/de/aspose.slides/icell/margin_top/) | Liefert oder setzt den oberen Rand in einem TextFrame.<br/>            Lesen/Schreiben **float**. |
| [`margin_bottom`](/slides/python-net/de/aspose.slides/icell/margin_bottom/) | Liefert oder setzt den unteren Rand in einem TextFrame.<br/>            Lesen/Schreiben **float**. |
| [`text_vertical_type`](/slides/python-net/de/aspose.slides/icell/text_vertical_type/) | Liefert oder setzt den Typ des vertikalen Textes.<br/>            Lesen/Schreiben [`TextVerticalType`](/slides/python-net/de/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/de/aspose.slides/icell/text_anchor_type/) | Liefert oder setzt den Textanker-Typ.<br/>            Lesen/Schreiben [`TextAnchorType`](/slides/python-net/de/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/de/aspose.slides/icell/anchor_center/) | Bestimmt, ob ein Textfeld innerhalb einer Zelle zentriert ist oder nicht.<br/>            Lesen/Schreiben **bool**. |
| [`first_column`](/slides/python-net/de/aspose.slides/icell/first_column/) | Liefert die erste Spalte der Zelle.<br/>            Nur lesbar [`IColumn`](/slides/python-net/de/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/de/aspose.slides/icell/first_row/) | Liefert die erste Zeile der Zelle.<br/>            Nur lesbar [`IRow`](/slides/python-net/de/aspose.slides/irow). |
| [`col_span`](/slides/python-net/de/aspose.slides/icell/col_span/) | Liefert die Anzahl der Rasterspalten im Tabellenraster der übergeordneten Tabelle, die von der aktuellen Zelle überspannt werden sollen. Diese Eigenschaft ermöglicht es Zellen, den Anschein einer Zusammenführung zu haben, da sie vertikale Grenzen anderer Zellen in der Tabelle überspannen.<br/>            Nur lesbar **int**. |
| [`row_span`](/slides/python-net/de/aspose.slides/icell/row_span/) | Liefert die Anzahl der Zeilen, die eine zusammengeführte Zelle überspannt. Dies wird in Kombination mit dem vMerge-Attribut anderer Zellen verwendet, um die Ausgangszelle einer horizontalen Zusammenführung festzulegen.<br/>            Nur lesbar **int**. |
| [`text_frame`](/slides/python-net/de/aspose.slides/icell/text_frame/) | Liefert den Textframe einer Zelle.<br/>            Nur lesbar [`ITextFrame`](/slides/python-net/de/aspose.slides/itextframe). |
| [`table`](/slides/python-net/de/aspose.slides/icell/table/) | Liefert das übergeordnete Table-Objekt einer Zelle.<br/>            Nur lesbar [`ITable`](/slides/python-net/de/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/de/aspose.slides/icell/is_merged_cell/) | Liefert true, wenn die Zelle mit einer angepassten Zelle zusammengeführt ist, andernfalls false.<br/>            Nur lesbar **bool**. |
| [`cell_format`](/slides/python-net/de/aspose.slides/icell/cell_format/) | Liefert das CellFormat-Objekt, das Formatierungseigenschaften für diese Zelle enthält.<br/>            Nur lesbar [`ICellFormat`](/slides/python-net/de/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/de/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/icell/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/de/aspose.slides/icell/split_by_col_span/#int) | Teilt die Zelle anhand des Spaltenindexes in zwei Zellen. |
| [`split_by_row_span(self, index)`](/slides/python-net/de/aspose.slides/icell/split_by_row_span/#int) | Teilt die Zelle anhand des Zeilenindexes in zwei Zellen. |
| [`split_by_height(self, height)`](/slides/python-net/de/aspose.slides/icell/split_by_height/#float) | Teilt die Zelle nach Höhe. |
| [`split_by_width(self, width)`](/slides/python-net/de/aspose.slides/icell/split_by_width/#float) | Teilt die Zelle nach Breite. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)