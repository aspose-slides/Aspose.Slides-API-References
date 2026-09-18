---
title: ICell class
second_title: Aspose.Slides dla Pythona via .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/icell/
---
## ICell klasa

Reprezentuje komórkę w tabeli.

Typ ICell udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`offset_x`](/slides/python-net/pl/aspose.slides/icell/offset_x/) | Zwraca odległość od lewej krawędzi tabeli do lewej krawędzi komórki.<br/>            Tylko do odczytu **float**. |
| [`offset_y`](/slides/python-net/pl/aspose.slides/icell/offset_y/) | Zwraca odległość od górnej krawędzi tabeli do górnej krawędzi komórki.<br/>            Tylko do odczytu **float**. |
| [`first_row_index`](/slides/python-net/pl/aspose.slides/icell/first_row_index/) | Zwraca indeks pierwszego wiersza obejmowanego przez komórkę.<br/>            Tylko do odczytu **int**. |
| [`first_column_index`](/slides/python-net/pl/aspose.slides/icell/first_column_index/) | Zwraca indeks pierwszej kolumny obejmowanej przez komórkę.<br/>            Tylko do odczytu **int**. |
| [`width`](/slides/python-net/pl/aspose.slides/icell/width/) | Zwraca szerokość komórki.<br/>            Tylko do odczytu **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/icell/height/) | Zwraca wysokość komórki.<br/>            Tylko do odczytu **float**. |
| [`minimal_height`](/slides/python-net/pl/aspose.slides/icell/minimal_height/) | Zwraca minimalną wysokość komórki.<br/>            Jest to suma minimalnych wysokości wszystkich wierszy obejmowanych przez komórkę.<br/>            Tylko do odczytu **float**. |
| [`margin_left`](/slides/python-net/pl/aspose.slides/icell/margin_left/) | Zwraca lub ustawia lewy margines w TextFrame.<br/>            Odczyt/Zapis **float**. |
| [`margin_right`](/slides/python-net/pl/aspose.slides/icell/margin_right/) | Zwraca lub ustawia prawy margines w TextFrame.<br/>            Odczyt/Zapis **float**. |
| [`margin_top`](/slides/python-net/pl/aspose.slides/icell/margin_top/) | Zwraca lub ustawia górny margines w TextFrame.<br/>            Odczyt/Zapis **float**. |
| [`margin_bottom`](/slides/python-net/pl/aspose.slides/icell/margin_bottom/) | Zwraca lub ustawia dolny margines w TextFrame.<br/>            Odczyt/Zapis **float**. |
| [`text_vertical_type`](/slides/python-net/pl/aspose.slides/icell/text_vertical_type/) | Zwraca lub ustawia typ pionowego tekstu.<br/>            Odczyt/Zapis [`TextVerticalType`](/slides/python-net/pl/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/pl/aspose.slides/icell/text_anchor_type/) | Zwraca lub ustawia typ kotwiczenia tekstu.<br/>            Odczyt/Zapis [`TextAnchorType`](/slides/python-net/pl/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/pl/aspose.slides/icell/anchor_center/) | Określa, czy pole tekstowe jest wyśrodkowane wewnątrz komórki.<br/>            Odczyt/Zapis **bool**. |
| [`first_column`](/slides/python-net/pl/aspose.slides/icell/first_column/) | Zwraca pierwszą kolumnę komórki.<br/>            Tylko do odczytu [`IColumn`](/slides/python-net/pl/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/pl/aspose.slides/icell/first_row/) | Zwraca pierwszy wiersz komórki.<br/>            Tylko do odczytu [`IRow`](/slides/python-net/pl/aspose.slides/irow). |
| [`col_span`](/slides/python-net/pl/aspose.slides/icell/col_span/) | Zwraca liczbę kolumn siatki w tabeli nadrzędnej, które mają być objęte przez bieżącą komórkę. Ta właściwość pozwala komórkom mieć wygląd połączonych, ponieważ obejmują pionowe granice innych komórek w tabeli.<br/>            Tylko do odczytu **int**. |
| [`row_span`](/slides/python-net/pl/aspose.slides/icell/row_span/) | Zwraca liczbę wierszy, które obejmuje połączona komórka. Używane w połączeniu z atrybutem vMerge w innych komórkach w celu określenia komórki początkowej poziomego łączenia.<br/>            Tylko do odczytu **int**. |
| [`text_frame`](/slides/python-net/pl/aspose.slides/icell/text_frame/) | Zwraca ramkę tekstową komórki.<br/>            Tylko do odczytu [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe). |
| [`table`](/slides/python-net/pl/aspose.slides/icell/table/) | Zwraca obiekt Table będący rodzicem komórki.<br/>            Tylko do odczytu [`ITable`](/slides/python-net/pl/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/pl/aspose.slides/icell/is_merged_cell/) | Zwraca prawdę, jeśli komórka jest połączona z dowolną dopasowaną komórką, w przeciwnym razie fałsz.<br/>            Tylko do odczytu **bool**. |
| [`cell_format`](/slides/python-net/pl/aspose.slides/icell/cell_format/) | Zwraca obiekt CellFormat zawierający właściwości formatowania tej komórki.<br/>            Tylko do odczytu [`ICellFormat`](/slides/python-net/pl/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/pl/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/icell/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/pl/aspose.slides/icell/split_by_col_span/#int) | Dzieli komórkę na dwie komórki według indeksu kolumny. |
| [`split_by_row_span(self, index)`](/slides/python-net/pl/aspose.slides/icell/split_by_row_span/#int) | Dzieli komórkę na dwie komórki według indeksu wiersza. |
| [`split_by_height(self, height)`](/slides/python-net/pl/aspose.slides/icell/split_by_height/#float) | Dzieli komórkę według wysokości. |
| [`split_by_width(self, width)`](/slides/python-net/pl/aspose.slides/icell/split_by_width/#float) | Dzieli komórkę według szerokości. |

### Zobacz też
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)