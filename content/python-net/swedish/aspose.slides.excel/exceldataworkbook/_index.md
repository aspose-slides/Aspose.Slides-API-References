---
title: ExcelDataWorkbook class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook klass

Representerar en arbetsbok som ger åtkomst till Excel-data för allmänt bruk.

ExcelDataWorkbook-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/__init__/#str) | Initierar en ny instans med den angivna filsökvägen. |
| [`__init__(self, stream)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Initierar en ny instans av klassen med den angivna strömmen. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Hämtar en cell från det angivna kalkylbladet med dess index och cellkoordinater. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Hämtar en cell från det angivna kalkylbladet med dess namn och cellkoordinater. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Hämtar en cell från det angivna kalkylbladet med dess index och Excel-liknande cellnamn (t.ex. "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Hämtar en cell från det angivna kalkylbladet med Excel-liknande cellnamn (t.ex. "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Hämtar en samling celler från arbetsboken som matchar den angivna formeln. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Hämtar en ordbok som innehåller index och namn på alla diagram i det angivna kalkylbladet i en Excel-arbetsbok. |
| [`get_worksheet_names(self)`](/slides/python-net/sv/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Hämtar namnen på alla kalkylblad som finns i Excel-arbetsboken. |


### Se även
* modul [`aspose.slides.excel`](/slides/python-net/sv/aspose.slides.excel)
* bibliotek [`Aspose.Slides`](/slides/python-net)