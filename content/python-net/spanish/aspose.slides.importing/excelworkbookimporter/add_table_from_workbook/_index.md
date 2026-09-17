---
title: add_table_from_workbook method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
Recupera una tabla del libro de Excel especificado y la añade al final de la colección de formas proporcionada en las coordenadas especificadas.

### Devuelve

La tabla que se añadió a la colección de formas.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection) | La colección de formas a la que se añadirá la tabla. |
| x | **float** | La coordenada X para posicionar la tabla. |
| y | **float** | La coordenada Y para posicionar la tabla. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/es/aspose.slides.excel/iexceldataworkbook) | El libro de Excel. |
| worksheet_name | **str** | El nombre de la hoja de cálculo que contiene la tabla. |
| cell_range | **str** | El rango de celdas que define la tabla (por ejemplo, "A1:D10"). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzada cuando cualquier parámetro requerido es None o está vacío, o cuando la hoja de cálculo o el rango de celdas especificados son inválidos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lanzada cuando los datos de entrada están en un formato no compatible. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
Recupera una tabla del archivo de libro de Excel especificado y la añade al final de la colección de formas proporcionada en las coordenadas especificadas.

### Devuelve

La tabla que se añadió a la colección de formas.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection) | La colección de formas a la que se añadirá la tabla. |
| x | **float** | La coordenada X para posicionar la tabla. |
| y | **float** | La coordenada Y para posicionar la tabla. |
| workbook_path | **str** | La ruta al archivo de libro de Excel. |
| worksheet_name | **str** | El nombre de la hoja de cálculo que contiene la tabla. |
| cell_range | **str** | El rango de celdas que define la tabla (por ejemplo, "A1:D10"). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzada cuando cualquier parámetro requerido es None o está vacío, o cuando la hoja de cálculo o el rango de celdas especificados son inválidos. |
| **RuntimeError(Proxy error(IOException))** | Lanzada cuando ocurre un error de E/S al acceder al archivo del libro. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lanzada cuando los datos de entrada están en un formato no compatible. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
Recupera una tabla del archivo de libro de Excel especificado y la añade al final de la colección de formas proporcionada en las coordenadas especificadas.

### Devuelve

La tabla que se añadió a la colección de formas.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection) | La colección de formas a la que se añadirá la tabla. |
| x | **float** | La coordenada X para posicionar la tabla. |
| y | **float** | La coordenada Y para posicionar la tabla. |
| workbook_stream | **io.RawIOBase** | Un flujo que contiene los datos del libro. |
| worksheet_name | **str** | El nombre de la hoja de cálculo que contiene la tabla. |
| cell_range | **str** | El rango de celdas que define la tabla (por ejemplo, "A1:D10"). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Lanzada cuando cualquier parámetro requerido es None o está vacío, o cuando la hoja de cálculo o el rango de celdas especificados son inválidos. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lanzada cuando los datos de entrada están en un formato no compatible. |



### Ver también
* clase [`ExcelWorkbookImporter`](/slides/python-net/es/aspose.slides.importing/excelworkbookimporter)
* clase [`IExcelDataWorkbook`](/slides/python-net/es/aspose.slides.excel/iexceldataworkbook)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* clase [`ITable`](/slides/python-net/es/aspose.slides/itable)
* módulo [`aspose.slides.importing`](/slides/python-net/es/aspose.slides.importing)
* biblioteca [`Aspose.Slides`](/slides/python-net)