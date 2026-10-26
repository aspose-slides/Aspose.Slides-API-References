---
title: ExcelDataWorkbook class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook Klasse

Stellt eine Arbeitsmappe dar, die Zugriff auf Excel-Daten für den allgemeinen Gebrauch bietet.

Der Typ ExcelDataWorkbook stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/__init__/#str) | Initialisiert eine neue Instanz mit dem angegebenen Dateipfad. |
| [`__init__(self, stream)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Initialisiert eine neue Instanz der Klasse mit dem bereitgestellten Stream. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und ihrer Zellkoordinaten ab. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Namens und ihrer Zellkoordinaten ab. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand ihres Index und des Excel-artigen Zellnamens (z.B. "B2") ab. |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Ruft eine Zelle aus dem angegebenen Arbeitsblatt anhand des Excel-artigen Zellnamens (z.B. "B2") ab. |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Ruft eine Sammlung von Zellen aus der Arbeitsmappe ab, die der angegebenen Formel entsprechen. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Ruft ein Wörterbuch ab, das die Indizes und Namen aller Diagramme im angegebenen Arbeitsblatt einer Excel-Arbeitsmappe enthält. |
| [`get_worksheet_names(self)`](/slides/python-net/de/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Ruft die Namen aller Arbeitsblätter ab, die in der Excel-Arbeitsmappe enthalten sind. |

### Siehe auch
* Modul [`aspose.slides.excel`](/slides/python-net/de/aspose.slides.excel)
* Bibliothek [`Aspose.Slides`](/slides/python-net)