---
title: add_chart_from_workbook method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

### Restituisce

Il grafico che è stato aggiunto alla collezione di forme.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection) | La collezione di forme a cui verrà aggiunto il grafico. |
| x | **float** | La coordinata X per posizionare il grafico. |
| y | **float** | La coordinata Y per posizionare il grafico. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/it/aspose.slides.excel/iexceldataworkbook) | La cartella di lavoro Excel. |
| worksheet_name | **str** | Il nome del foglio di lavoro che contiene il grafico. |
| chart_index | **int** | L'indice basato su zero della forma grafico da inserire. <br/><br/>            Questo indice può essere ottenuto usando il metodo **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | Se `true`, l'intera cartella di lavoro sarà incorporata nel grafico; <br/><br/>            se `false`, verranno incorporati solo i dati del grafico. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando un parametro richiesto è None, vuoto, o se il grafico non può essere trovato nella cartella di lavoro. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

### Restituisce

Il grafico che è stato aggiunto alla collezione di forme.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection) | La collezione di forme a cui verrà aggiunto il grafico. |
| x | **float** | La coordinata X per posizionare il grafico. |
| y | **float** | La coordinata Y per posizionare il grafico. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/it/aspose.slides.excel/iexceldataworkbook) | La cartella di lavoro Excel. |
| worksheet_name | **str** | Il nome del foglio di lavoro che contiene il grafico. |
| chart_name | **str** | Il nome del grafico da aggiungere. |
| embed_all_workbook | **bool** | Se `true`, l'intera cartella di lavoro sarà incorporata nel grafico; <br/><br/>            se `false`, verranno incorporati solo i dati del grafico. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando un parametro richiesto è None, vuoto, o se il grafico non può essere trovato nella cartella di lavoro. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

### Restituisce

Il grafico che è stato aggiunto alla collezione di forme.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection) | La collezione di forme a cui verrà aggiunto il grafico. |
| x | **float** | La coordinata X per posizionare il grafico. |
| y | **float** | La coordinata Y per posizionare il grafico. |
| workbook_stream | **io.RawIOBase** | Un flusso contenente i dati della cartella di lavoro. |
| worksheet_name | **str** | Il nome del foglio di lavoro che contiene il grafico. |
| chart_name | **str** | Il nome del grafico da aggiungere. |
| embed_all_workbook | **bool** | Se `true`, l'intera cartella di lavoro sarà incorporata nel grafico; <br/><br/>            se `false`, verranno incorporati solo i dati del grafico. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando un parametro richiesto è None, vuoto, o se il grafico non può essere trovato nella cartella di lavoro. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generata quando i dati di input sono in un formato non supportato. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

### Restituisce

Il grafico che è stato aggiunto alla collezione di forme.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection) | La collezione di forme a cui verrà aggiunto il grafico. |
| x | **float** | La coordinata X per posizionare il grafico. |
| y | **float** | La coordinata Y per posizionare il grafico. |
| workbook_path | **str** | Il percorso del file della cartella di lavoro contenente il grafico. |
| worksheet_name | **str** | Il nome del foglio di lavoro che contiene il grafico. |
| chart_name | **str** | Il nome del grafico da aggiungere. |
| embed_workbook | **bool** | Se `true`, la cartella di lavoro sarà incorporata nel grafico; <br/><br/>            se `false`, il grafico collegherà la cartella di lavoro esterna. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando un parametro richiesto è None, vuoto, o se il grafico non può essere trovato nella cartella di lavoro. |
| **RuntimeError(Proxy error(IOException))** | Generata quando si verifica un errore I/O durante l'accesso al file. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generata quando i dati di input sono in un formato non supportato. |



### Vedi anche
* classe [`ExcelWorkbookImporter`](/slides/python-net/it/aspose.slides.importing/excelworkbookimporter)
* classe [`IExcelDataWorkbook`](/slides/python-net/it/aspose.slides.excel/iexceldataworkbook)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* modulo [`aspose.slides.importing`](/slides/python-net/it/aspose.slides.importing)
* libreria [`Aspose.Slides`](/slides/python-net)