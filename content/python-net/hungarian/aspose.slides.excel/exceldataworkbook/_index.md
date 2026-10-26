---
title: ExcelDataWorkbook class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook osztály

Egy munkafüzetet reprezentál, amely általános felhasználásra biztosít hozzáférést az Excel adatokhoz.

Az ExcelDataWorkbook típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/__init__/#str) | Inicializál egy új példányt a megadott fájlútvonal használatával. |
| [`__init__(self, stream)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Inicializál egy új példányt az osztályból a megadott adatfolyam használatával. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Lekéri a cellát a megadott munkalapról az index és a cellakoordináták alapján. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Lekéri a cellát a megadott munkalapról a név és a cellakoordináták alapján. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Lekéri a cellát a megadott munkalapról az index és az Excel-stílusú cellanév (pl. "B2") alapján. |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Lekéri a cellát a megadott munkalapról az Excel-stílusú cellanév (pl. "B2") alapján. |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Lekéri a munkafüzetről a megadott képlettel egyező cellák gyűjteményét. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Lekéri a szótárat, amely tartalmazza az összes diagram indexeit és neveit a megadott munkalapon egy Excel munkafüzetben. |
| [`get_worksheet_names(self)`](/slides/python-net/hu/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Lekéri az összes munkalap nevét, amely a Excel munkafüzetben szerepel. |

### Lásd még
* modul [`aspose.slides.excel`](/slides/python-net/hu/aspose.slides.excel)
* könyvtár [`Aspose.Slides`](/slides/python-net)