---
title: ExcelDataWorkbook class
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook klasa

Reprezentuje skoroszyt, który zapewnia dostęp do danych Excel do ogólnego użytku.

Typ ExcelDataWorkbook udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/__init__/#str) | Inicjalizuje nową instancję przy użyciu określonej ścieżki pliku. |
| [`__init__(self, stream)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Inicjalizuje nową instancję klasy przy użyciu dostarczonego strumienia. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Pobiera komórkę z określonego arkusza przy użyciu jego indeksu i współrzędnych komórki. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Pobiera komórkę z określonego arkusza przy użyciu jego nazwy i współrzędnych komórki. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Pobiera komórkę z określonego arkusza przy użyciu jego indeksu i nazwy komórki w stylu Excel (np. "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Pobiera komórkę z określonego arkusza przy użyciu nazwy komórki w stylu Excel (np. "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Pobiera kolekcję komórek z skoroszytu, które spełniają określoną formułę. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Pobiera słownik zawierający indeksy i nazwy wszystkich wykresów w określonym arkuszu skoroszytu Excel. |
| [`get_worksheet_names(self)`](/slides/python-net/pl/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Pobiera nazwy wszystkich arkuszy zawartych w skoroszycie Excel. |

### Zobacz także
* moduł [`aspose.slides.excel`](/slides/python-net/pl/aspose.slides.excel)
* biblioteka [`Aspose.Slides`](/slides/python-net)