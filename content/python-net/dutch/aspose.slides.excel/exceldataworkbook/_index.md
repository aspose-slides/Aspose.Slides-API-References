---
title: ExcelDataWorkbook class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook klasse

Representeert een werkmap die toegang biedt tot Excel-gegevens voor algemeen gebruik.

Het ExcelDataWorkbook-type biedt de volgende leden:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/__init__/#str) | Initialiseert een nieuwe instantie met het opgegeven bestandspad. |
| [`__init__(self, stream)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Initialiseert een nieuwe instantie van de klasse met de opgegeven stream. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Haalt een cel op uit het opgegeven werkblad met behulp van de index en celcoördinaten. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Haalt een cel op uit het opgegeven werkblad met behulp van de naam en celcoördinaten. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Haalt een cel op uit het opgegeven werkblad met behulp van de index en Excel-achtige celnaam (bijv. "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Haalt een cel op uit het opgegeven werkblad met behulp van een Excel-achtige celnaam (bijv. "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Haalt een verzameling cellen op uit de werkmap die overeenkomen met de opgegeven formule. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Haalt een woordenboek op dat de indexen en namen van alle grafieken in het opgegeven werkblad van een Excel-werkmap bevat. |
| [`get_worksheet_names(self)`](/slides/python-net/nl/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Haalt de namen op van alle werkbladen die in de Excel-werkmap aanwezig zijn. |

### Zie ook
* module [`aspose.slides.excel`](/slides/python-net/nl/aspose.slides.excel)
* bibliotheek [`Aspose.Slides`](/slides/python-net)