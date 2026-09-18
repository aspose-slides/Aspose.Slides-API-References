---
title: Cell class
second_title: Aspose.Slides dla Pythona przez .NET API
description: 
type: docs
url: /pl/aspose.slides/cell/
---
## Klasa Cell

Reprezentuje komórkę tabeli.

Typ Cell udostępnia następujące elementy:

## Właściwość

| Właściwość | Opis |
| :- | :- |
| [`offset_x`](/slides/python-net/pl/aspose.slides/cell/offset_x/) | Zwraca odległość od lewej krawędzi tabeli do lewej krawędzi komórki.<br/>            tylko do odczytu **float**. |
| [`offset_y`](/slides/python-net/pl/aspose.slides/cell/offset_y/) | Zwraca odległość od górnej krawędzi tabeli do górnej krawędzi komórki.<br/>            tylko do odczytu **float**. |
| [`first_row_index`](/slides/python-net/pl/aspose.slides/cell/first_row_index/) | Zwraca indeks pierwszego wiersza pokrywanego przez komórkę.<br/>            tylko do odczytu **int**. |
| [`first_column_index`](/slides/python-net/pl/aspose.slides/cell/first_column_index/) | Zwraca indeks pierwszej kolumny pokrywanej przez komórkę.<br/>            tylko do odczytu **int**. |
| [`width`](/slides/python-net/pl/aspose.slides/cell/width/) | Zwraca szerokość komórki.<br/>            tylko do odczytu **float**. |
| [`height`](/slides/python-net/pl/aspose.slides/cell/height/) | Zwraca wysokość komórki.<br/>            tylko do odczytu **float**. |
| [`minimal_height`](/slides/python-net/pl/aspose.slides/cell/minimal_height/) | Zwraca minimalną wysokość komórki.<br/>            Jest to suma minimalnych wysokości wszystkich wierszy pokrywanych przez komórkę.<br/>            tylko do odczytu **float**. |
| [`margin_left`](/slides/python-net/pl/aspose.slides/cell/margin_left/) | Zwraca lub ustawia lewy margines w TextFrame.<br/>            odczyt/zapis **float**. |
| [`margin_right`](/slides/python-net/pl/aspose.slides/cell/margin_right/) | Zwraca lub ustawia prawy margines w TextFrame.<br/>            odczyt/zapis **float**. |
| [`margin_top`](/slides/python-net/pl/aspose.slides/cell/margin_top/) | Zwraca lub ustawia górny margines w TextFrame.<br/>            odczyt/zapis **float**. |
| [`margin_bottom`](/slides/python-net/pl/aspose.slides/cell/margin_bottom/) | Zwraca lub ustawia dolny margines w TextFrame.<br/>            odczyt/zapis **float**. |
| [`text_vertical_type`](/slides/python-net/pl/aspose.slides/cell/text_vertical_type/) | Zwraca lub ustawia typ pionowego tekstu.<br/>            odczyt/zapis [`TextVerticalType`](/slides/python-net/pl/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/pl/aspose.slides/cell/text_anchor_type/) | Zwraca lub ustawia typ zakotwiczenia tekstu.<br/>            odczyt/zapis [`TextAnchorType`](/slides/python-net/pl/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/pl/aspose.slides/cell/anchor_center/) | Określa, czy pole tekstowe jest wyśrodkowane wewnątrz komórki.<br/>            odczyt/zapis **bool**. |
| [`first_row`](/slides/python-net/pl/aspose.slides/cell/first_row/) | Pobiera pierwszy wiersz komórki.<br/>            tylko do odczytu [`IRow`](/slides/python-net/pl/aspose.slides/irow). |
| [`first_column`](/slides/python-net/pl/aspose.slides/cell/first_column/) | Pobiera pierwszą kolumnę komórki.<br/>            tylko do odczytu [`IColumn`](/slides/python-net/pl/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/pl/aspose.slides/cell/col_span/) | Zwraca liczbę kolumn siatki w siatce tabeli nadrzędnej, które mają być rozciągnięte przez bieżącą komórkę. To własność pozwala komórkom mieć wygląd połączonych, ponieważ rozciągają pionowe granice innych komórek w tabeli.<br/>            tylko do odczytu **int**. |
| [`row_span`](/slides/python-net/pl/aspose.slides/cell/row_span/) | Zwraca liczbę wierszy, które rozciąga połączona komórka. Jest to używane w połączeniu z atrybutem vMerge w innych komórkach w celu określenia komórki początkowej poziomego połączenia.<br/>            tylko do odczytu **int**. |
| [`text_frame`](/slides/python-net/pl/aspose.slides/cell/text_frame/) | Zwraca ramkę tekstową komórki.<br/>            tylko do odczytu [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe). |
| [`table`](/slides/python-net/pl/aspose.slides/cell/table/) | Zwraca obiekt Table nadrzędny dla komórki.<br/>            tylko do odczytu [`ITable`](/slides/python-net/pl/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/pl/aspose.slides/cell/is_merged_cell/) | Zwraca prawda, jeśli komórka jest połączona z dowolną dopasowaną komórką, w przeciwnym razie fałsz.<br/>            tylko do odczytu **bool**. |
| [`cell_format`](/slides/python-net/pl/aspose.slides/cell/cell_format/) | Zwraca obiekt CellFormat zawierający właściwości formatowania dla tej komórki.<br/>            tylko do odczytu [`ICellFormat`](/slides/python-net/pl/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/pl/aspose.slides/cell/slide/) | Zwraca slajd nadrzędny komórki.<br/>            tylko do odczytu [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pl/aspose.slides/cell/presentation/) | Zwraca prezentację nadrzędną komórki.<br/>            tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/pl/aspose.slides/cell/split_by_col_span/#int) | Rozdziela komórkę na dwie komórki według indeksu kolumny. |
| [`split_by_row_span(self, index)`](/slides/python-net/pl/aspose.slides/cell/split_by_row_span/#int) | Rozdziela komórkę na dwie komórki według indeksu wiersza. |
| [`split_by_height(self, height)`](/slides/python-net/pl/aspose.slides/cell/split_by_height/#float) | Rozdziela komórkę według wysokości. |
| [`split_by_width(self, width)`](/slides/python-net/pl/aspose.slides/cell/split_by_width/#float) | Rozdziela komórkę według szerokości. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)