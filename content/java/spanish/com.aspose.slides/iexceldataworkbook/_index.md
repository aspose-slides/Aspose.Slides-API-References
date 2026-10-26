---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /es/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Representa un libro de trabajo que brinda acceso a datos de Excel para uso general.
## Métodos

| Method | Description |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Recupera una colección de celdas del libro de trabajo que coinciden con la fórmula especificada. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Recupera una celda de la hoja de trabajo especificada usando su índice y coordenadas de celda. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Recupera una celda de la hoja de trabajo especificada usando su nombre y coordenadas de celda. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Recupera una celda de la hoja de trabajo especificada usando su índice y nombre de celda al estilo Excel (p. ej., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Recupera una celda de la hoja de trabajo especificada usando el nombre de celda al estilo Excel (p. ej., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Recupera un diccionario que contiene los índices y nombres de todos los gráficos en la hoja de trabajo especificada de un libro de trabajo Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Recupera los nombres de todas las hojas de trabajo contenidas en el libro de trabajo Excel. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Recupera una colección de celdas del libro de trabajo que coinciden con la fórmula especificada.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Salida: 5
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formula | java.lang.String | Una fórmula o expresión de rango (p. ej., "Sheet1!A1:B3") utilizada para identificar las celdas objetivo. |
| skipHiddenCells | boolean | Si es true, las celdas ocultas (p. ej., en filas o columnas ocultas) se excluyen del resultado. |

**Devuelve:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Una lista de celdas de solo lectura que coinciden con la fórmula especificada.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Recupera una celda de la hoja de trabajo especificada usando su índice y coordenadas de celda.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | int | Índice basado en cero de la hoja de trabajo. |
| row | int | Índice basado en cero de la fila de la celda. |
| column | int | Índice basado en cero de la columna de la celda. |

**Devuelve:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La celda en la ubicación especificada.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Recupera una celda de la hoja de trabajo especificada usando su nombre y coordenadas de celda.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetName | java.lang.String | El nombre de la hoja de trabajo. |
| row | int | Índice basado en cero de la fila de la celda. |
| column | int | Índice basado en cero de la columna de la celda. |

**Devuelve:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La celda en la ubicación especificada.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Recupera una celda de la hoja de trabajo especificada usando su índice y nombre de celda al estilo Excel (p. ej., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | int | Índice basado en cero de la hoja de trabajo. |
| cellName | java.lang.String | La referencia de celda al estilo Excel (p. ej., "A1", "C5"). |

**Devuelve:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La celda en la ubicación especificada.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Recupera una celda de la hoja de trabajo especificada usando el nombre de celda al estilo Excel (p. ej., "B2").

--------------------

> ```
> Ejemplo:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetName | java.lang.String | El nombre de la hoja de trabajo. |
| cellName | java.lang.String | La referencia de celda al estilo Excel (p. ej., "A1", "C5"). |

**Devuelve:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - La celda en la ubicación especificada.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Recupera un diccionario que contiene los índices y nombres de todos los gráficos en la hoja de trabajo especificada de un libro de trabajo Excel.

--------------------

> ```
> Ejemplo:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetName | java.lang.String | El nombre de la hoja de trabajo donde buscar los gráficos. |

**Devuelve:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Un diccionario donde la clave es el índice del gráfico y el valor es el nombre del gráfico.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Recupera los nombres de todas las hojas de trabajo contenidas en el libro de trabajo Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Devuelve:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Una lista de nombres de hojas de trabajo