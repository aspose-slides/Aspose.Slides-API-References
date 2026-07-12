---
title: ChartDataWorkbook
second_title: Referência da API Java Aspose.Slides para Android
description: Fornece acesso a uma pasta de trabalho Excel incorporada
type: docs
url: /pt/com.aspose.slides/chartdataworkbook/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Fornece acesso a pasta de trabalho Excel incorporada
## Métodos

| Método | Descrição |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Obtém uma coleção de planilhas. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Obtém o conjunto de células. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Obtém a célula que pode ser usada para séries ou categorias de gráfico |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Obtém a célula que pode ser usada para séries ou categorias de gráfico |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Obtém a célula que pode ser usada para séries ou categorias de gráfico |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Obtém a célula que pode ser usada para séries ou categorias de gráfico |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Obtém a célula que pode ser usada para séries ou categorias de gráfico |
| [clear(int sheetIndex)](#clear-int-) | Limpa todos os valores das células na planilha |
| [calculateFormulas()](#calculateFormulas--) | Calcula todas as fórmulas na pasta de trabalho e atualiza os valores correspondentes das células. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


Obtém uma coleção de planilhas.

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

**Retorna:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Obtém o conjunto de células.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formula | java.lang.String | Fórmula Excel como "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Se true, o método retorna a coleção sem células ocultas. |

**Retorna:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


Obtém a célula que pode ser usada para séries ou categorias de gráfico

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetName | java.lang.String | Nome da planilha. |
| row | int | A linha. |
| column | int | A coluna. |

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Obtém a célula que pode ser usada para séries ou categorias de gráfico

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | int | Índice da planilha. |
| row | int | A linha. |
| column | int | A coluna. |

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


Obtém a célula que pode ser usada para séries ou categorias de gráfico

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | int | Índice da planilha. |
| cellName | java.lang.String | Nome da célula. |

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Obtém a célula que pode ser usada para séries ou categorias de gráfico

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | int | Índice da planilha. |
| cellName | java.lang.String | Nome da célula. |
| value | java.lang.Object | O valor. |

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Obtém a célula que pode ser usada para séries ou categorias de gráfico

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| worksheetIndex | int | Índice da planilha. |
| row | int | A linha. |
| column | int | A coluna. |
| value | java.lang.Object | O valor. |

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


Limpa todos os valores das células na planilha

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sheetIndex | int | Índice da planilha |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Calcula todas as fórmulas na pasta de trabalho e atualiza os valores correspondentes das células.

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