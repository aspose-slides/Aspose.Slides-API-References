---
title: ChartDataWorkbook
second_title: Referencia de API Java para Aspose.Slides para Android
description: Proporciona acceso a un libro de Excel incrustado
type: docs
url: /es/com.aspose.slides/chartdataworkbook/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Proporciona acceso a un libro de Excel incrustado
## Métodos

| Método | Descripción |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Obtiene una colección de hojas de cálculo. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Obtiene el conjunto de celdas. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Obtiene la celda que se puede usar para series o categorías de gráfico |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Obtiene la celda que se puede usar para series o categorías de gráfico |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Obtiene la celda que se puede usar para series o categorías de gráfico |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Obtiene la celda que se puede usar para series o categorías de gráfico |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Obtiene la celda que se puede usar para series o categorías de gráfico |
| [clear(int sheetIndex)](#clear-int-) | Borra todos los valores de celdas en la hoja |
| [calculateFormulas()](#calculateFormulas--) | Calcula todas las fórmulas en el libro de trabajo y actualiza los valores correspondientes de las celdas. |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Obtiene el conjunto de celdas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formula | java.lang.String | Fórmula de Excel como "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Si es true, el método devuelve la colección sin celdas ocultas. |

**Devuelve:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Obtiene la celda que se puede usar para series o categorías de gráfico

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetName | java.lang.String | Nombre de la hoja de cálculo. |
| row | int | La fila. |
| column | int | La columna. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Obtiene la celda que se puede usar para series o categorías de gráfico

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | int | Índice de la hoja de cálculo. |
| row | int | La fila. |
| column | int | La columna. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Obtiene la celda que se puede usar para series o categorías de gráfico

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | int | Índice de la hoja de cálculo. |
| cellName | java.lang.String | Nombre de la celda. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Obtiene la celda que se puede usar para series o categorías de gráfico

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | int | Índice de la hoja de cálculo. |
| cellName | java.lang.String | Nombre de la celda. |
| value | java.lang.Object | El valor. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Obtiene la celda que se puede usar para series o categorías de gráfico

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | int | Índice de la hoja de cálculo. |
| row | int | La fila. |
| column | int | La columna. |
| value | java.lang.Object | El valor. |

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Borra todos los valores de celdas en la hoja

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sheetIndex | int | Índice de la hoja |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

Calcula todas las fórmulas en el libro de trabajo y actualiza los valores correspondientes de las celdas.

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
