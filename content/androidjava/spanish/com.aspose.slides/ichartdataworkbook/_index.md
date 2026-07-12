---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Proporciona acceso al libro de Excel incrustado
type: docs
url: /es/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Proporciona acceso al libro de Excel incrustado
## Métodos

| Method | Description |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Calcula todas las fórmulas en el libro de trabajo y actualiza los valores de las celdas correspondientes. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Obtiene el conjunto de celdas. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Obtiene la celda que puede usarse para series o categorías del gráfico |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Obtiene la celda que puede usarse para series o categorías del gráfico |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Obtiene la celda que puede usarse para series o categorías del gráfico |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Obtiene la celda que puede usarse para series o categorías del gráfico |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Obtiene la celda que puede usarse para series o categorías del gráfico |
| [clear(int sheetIndex)](#clear-int-) | Borra todos los valores de celdas en la hoja |
| [getWorksheets()](#getWorksheets--) | Obtiene una colección de hojas de cálculo. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```


Calcula todas las fórmulas en el libro de trabajo y actualiza los valores de las celdas correspondientes.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Obtiene el conjunto de celdas.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Fórmula de Excel como "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Si es true, el método devuelve la colección sin celdas ocultas. |

**Devuelve:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Conjunto de celdas [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


Obtiene la celda que puede usarse para series o categorías del gráfico

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | Nombre de la hoja de cálculo. |
| row | int | La fila. |
| column | int | La columna. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Obtiene la celda que puede usarse para series o categorías del gráfico

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Índice de la hoja de cálculo. |
| row | int | La fila. |
| column | int | La columna. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


Obtiene la celda que puede usarse para series o categorías del gráfico

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Índice de la hoja de cálculo. |
| cellName | java.lang.String | Nombre de la celda. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Obtiene la celda que puede usarse para series o categorías del gráfico

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Índice de la hoja de cálculo. |
| cellName | java.lang.String | Nombre de la celda. |
| value | java.lang.Object | El valor. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Obtiene la celda que puede usarse para series o categorías del gráfico

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | Índice de la hoja de cálculo. |
| row | int | La fila. |
| column | int | La columna. |
| value | java.lang.Object | El valor. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


Borra todos los valores de celdas en la hoja

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetIndex | int | Índice de la hoja |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```


Obtiene una colección de hojas de cálculo.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)