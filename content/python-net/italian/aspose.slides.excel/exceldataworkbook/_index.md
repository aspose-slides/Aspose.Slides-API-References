---
title: ExcelDataWorkbook class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.excel/exceldataworkbook/
---
## ExcelDataWorkbook classe

Rappresenta una cartella di lavoro che fornisce l'accesso ai dati Excel per uso generale.

Il tipo ExcelDataWorkbook espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, file_path)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/__init__/#str) | Inizializza una nuova istanza utilizzando il percorso file specificato. |
| [`__init__(self, stream)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/__init__/#iorawiobase) | Inizializza una nuova istanza della classe utilizzando lo stream fornito. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/get_cell/#int-int-int) | Recupera una cella dal foglio di lavoro specificato usando il suo indice e le coordinate della cella. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/get_cell/#str-int-int) | Recupera una cella dal foglio di lavoro specificato usando il suo nome e le coordinate della cella. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/get_cell/#int-str) | Recupera una cella dal foglio di lavoro specificato usando il suo indice e il nome della cella in stile Excel (ad esempio, "B2"). |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/get_cell/#str-str) | Recupera una cella dal foglio di lavoro specificato usando il nome della cella in stile Excel (ad esempio, "B2"). |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/get_cells/#str-bool) | Recupera una collezione di celle dalla cartella di lavoro che corrispondono alla formula specificata. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/get_charts_from_worksheet/#str) | Recupera un dizionario contenente gli indici e i nomi di tutti i grafici nel foglio di lavoro specificato di una cartella di lavoro Excel. |
| [`get_worksheet_names(self)`](/slides/python-net/it/aspose.slides.excel/exceldataworkbook/get_worksheet_names/#) | Recupera i nomi di tutti i fogli di lavoro contenuti nella cartella di lavoro Excel. |

### Vedi anche
* modulo [`aspose.slides.excel`](/slides/python-net/it/aspose.slides.excel)
* libreria [`Aspose.Slides`](/slides/python-net)