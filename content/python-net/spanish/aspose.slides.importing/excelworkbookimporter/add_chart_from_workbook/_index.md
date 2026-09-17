---
title: add_chart_from_workbook method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

### Devuelve

El gráfico que se agregó a la colección de formas.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection) | La colección de formas a la que se agregará el gráfico. |
| x | **float** | La coordenada X para posicionar el gráfico. |
| y | **float** | La coordenada Y para posicionar el gráfico. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/es/aspose.slides.excel/iexceldataworkbook) | El libro de Excel. |
| worksheet_name | **str** | El nombre de la hoja de cálculo que contiene el gráfico. |
| chart_index | **int** | El índice basado en cero de la forma del gráfico a insertar. <br/><br/>            Este índice se puede obtener usando el método **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste**. |
| embed_all_workbook | **bool** | Si `true`, todo el libro de trabajo se incorporará en el gráfico; <br/><br/>            si `false`, solo se incorporarán los datos del gráfico. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando algún parámetro requerido es None, está vacío, o si el gráfico no se puede encontrar en el libro de trabajo. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

### Devuelve

El gráfico que se agregó a la colección de formas.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection) | La colección de formas a la que se agregará el gráfico. |
| x | **float** | La coordenada X para posicionar el gráfico. |
| y | **float** | La coordenada Y para posicionar el gráfico. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/es/aspose.slides.excel/iexceldataworkbook) | El libro de Excel. |
| worksheet_name | **str** | El nombre de la hoja de cálculo que contiene el gráfico. |
| chart_name | **str** | El nombre del gráfico que se agregará. |
| embed_all_workbook | **bool** | Si `true`, todo el libro de trabajo se incorporará en el gráfico; <br/><br/>            si `false`, solo se incorporarán los datos del gráfico. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando algún parámetro requerido es None, está vacío, o si el gráfico no se puede encontrar en el libro de trabajo. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

### Devuelve

El gráfico que se agregó a la colección de formas.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection) | La colección de formas a la que se agregará el gráfico. |
| x | **float** | La coordenada X para posicionar el gráfico. |
| y | **float** | La coordenada Y para posicionar el gráfico. |
| workbook_stream | **io.RawIOBase** | Un flujo que contiene los datos del libro de trabajo. |
| worksheet_name | **str** | El nombre de la hoja de cálculo que contiene el gráfico. |
| chart_name | **str** | El nombre del gráfico que se agregará. |
| embed_all_workbook | **bool** | Si `true`, todo el libro de trabajo se incorporará en el gráfico; <br/><br/>            si `false`, solo se incorporarán los datos del gráfico. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando algún parámetro requerido es None, está vacío, o si el gráfico no se puede encontrar en el libro de trabajo. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Se lanza cuando los datos de entrada están en un formato no compatible. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
Recupera un gráfico del libro de Excel especificado y lo agrega al final de la colección de formas proporcionada en las coordenadas especificadas.

### Devuelve

El gráfico que se agregó a la colección de formas.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection) | La colección de formas a la que se agregará el gráfico. |
| x | **float** | La coordenada X para posicionar el gráfico. |
| y | **float** | La coordenada Y para posicionar el gráfico. |
| workbook_path | **str** | La ruta del archivo al libro que contiene el gráfico. |
| worksheet_name | **str** | El nombre de la hoja de cálculo que contiene el gráfico. |
| chart_name | **str** | El nombre del gráfico que se agregará. |
| embed_workbook | **bool** | Si `true`, el libro de trabajo se incorporará en el gráfico; <br/><br/>            si `false`, el gráfico enlazará al libro de trabajo externo. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Se lanza cuando algún parámetro requerido es None, está vacío, o si el gráfico no se puede encontrar en el libro de trabajo. |
| **RuntimeError(Proxy error(IOException))** | Se lanza cuando ocurre un error de E/S al acceder al archivo. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Se lanza cuando los datos de entrada están en un formato no compatible. |



### Ver también
* clase [`ExcelWorkbookImporter`](/slides/python-net/es/aspose.slides.importing/excelworkbookimporter)
* clase [`IExcelDataWorkbook`](/slides/python-net/es/aspose.slides.excel/iexceldataworkbook)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides.importing`](/slides/python-net/es/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)