---
title: ExcelDataWorkbook class
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook třída

Reprezentuje sešit, který poskytuje přístup k datům Excelu pro obecné použití.

Typ ExcelDataWorkbook obsahuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/__init__/#str) | Inicializuje novou instanci pomocí zadané cesty k souboru. |
| [`__init__(self, stream)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Inicializuje novou instanci třídy pomocí poskytnutého proudu. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Načte buňku z určeného listu pomocí jejího indexu a souřadnic buňky. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Načte buňku z určeného listu pomocí jejího názvu a souřadnic buňky. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Načte buňku z určeného listu pomocí jejího indexu a názvu buňky v Excelovém formátu (např. "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Načte buňku z určeného listu pomocí názvu buňky v Excelovém formátu (např. "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Načte kolekci buněk ze sešitu, které odpovídají zadanému vzorci. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Načte slovník obsahující indexy a názvy všech grafů v určeném listu Excel sešitu. |
| [`get_worksheet_names(self)`](/slides/python-net/cs/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Načte názvy všech listů obsažených v Excel sešitu. |

### Viz také
* modul [`aspose.slides.excel`](/slides/python-net/cs/aspose.slides.excel)
* knihovna [`Aspose.Slides`](/slides/python-net)