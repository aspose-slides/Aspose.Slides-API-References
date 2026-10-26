---
title: add_table_from_workbook method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Recupera una tabella dal workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

### Restituisce

La tabella che è stata aggiunta alla collezione di forme.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection) | La collezione di forme a cui la tabella sarà aggiunta. |
| x | **float** | La coordinata X per posizionare la tabella. |
| y | **float** | La coordinata Y per posizionare la tabella. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/it/aspose.slides.excel/iexceldataworkbook) | Il workbook Excel. |
| worksheet_name | **str** | Il nome del foglio di lavoro che contiene la tabella. |
| cell_range | **str** | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando un parametro richiesto è None o vuoto, o quando il foglio di lavoro o l'intervallo di celle specificato non è valido. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generata quando i dati di input sono in un formato non supportato. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Recupera una tabella dal file workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

### Restituisce

La tabella che è stata aggiunta alla collezione di forme.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection) | La collezione di forme a cui la tabella sarà aggiunta. |
| x | **float** | La coordinata X per posizionare la tabella. |
| y | **float** | La coordinata Y per posizionare la tabella. |
| workbook_path | **str** | Il percorso al file workbook Excel. |
| worksheet_name | **str** | Il nome del foglio di lavoro che contiene la tabella. |
| cell_range | **str** | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando un parametro richiesto è None o vuoto, o quando il foglio di lavoro o l'intervallo di celle specificato non è valido. |
| **RuntimeError(Proxy error(IOException))** | Generata quando si verifica un errore I/O durante l'accesso al file del workbook. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generata quando i dati di input sono in un formato non supportato. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Recupera una tabella dal file workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

### Restituisce

La tabella che è stata aggiunta alla collezione di forme.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection) | La collezione di forme a cui la tabella sarà aggiunta. |
| x | **float** | La coordinata X per posizionare la tabella. |
| y | **float** | La coordinata Y per posizionare la tabella. |
| workbook_stream | **io.RawIOBase** | Un flusso contenente i dati del workbook. |
| worksheet_name | **str** | Il nome del foglio di lavoro che contiene la tabella. |
| cell_range | **str** | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando un parametro richiesto è None o vuoto, o quando il foglio di lavoro o l'intervallo di celle specificato non è valido. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generata quando i dati di input sono in un formato non supportato. |



### Vedi anche
* classe [`ExcelWorkbookImporter`](/slides/python-net/it/aspose.slides.importing/excelworkbookimporter)
* classe [`IExcelDataWorkbook`](/slides/python-net/it/aspose.slides.excel/iexceldataworkbook)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* classe [`ITable`](/slides/python-net/it/aspose.slides/itable)
* modulo [`aspose.slides.importing`](/slides/python-net/it/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)