---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Fornisce l'accesso a una cartella di lavoro Excel incorporata
type: docs
url: /it/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Fornisce l'accesso a una cartella di lavoro Excel incorporata
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Calcola tutte le formule nel workbook e aggiorna i valori delle celle corrispondenti. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Restituisce l'insieme delle celle. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [clear(int sheetIndex)](#clear-int-) | Cancella tutti i valori delle celle nel foglio |
| [getWorksheets()](#getWorksheets--) | Restituisce una collezione di fogli di lavoro. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```


Calcola tutte le formule nel workbook e aggiorna i valori delle celle corrispondenti.

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


Restituisce l'insieme delle celle.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | java.lang.String | Formula Excel come "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Se true il metodo restituisce la collezione senza celle nascoste. |

**Restituisce:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Set di celle [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetName | java.lang.String | Nome del foglio di lavoro. |
| row | int | La riga. |
| column | int | La colonna. |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - oggetto Cell
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | int | Indice del foglio di lavoro. |
| row | int | La riga. |
| column | int | La colonna. |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - oggetto Cell
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | int | Indice del foglio di lavoro. |
| cellName | java.lang.String | Nome della cella. |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - oggetto Cell
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | int | Indice del foglio di lavoro. |
| cellName | java.lang.String | Nome della cella. |
| value | java.lang.Object | Il valore. |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - oggetto Cell
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheetIndex | int | Indice del foglio di lavoro. |
| row | int | La riga. |
| column | int | La colonna. |
| value | java.lang.Object | Il valore. |

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - oggetto Cell
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


Cancella tutti i valori delle celle nel foglio

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sheetIndex | int | Indice del foglio |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```


Restituisce una collezione di fogli di lavoro.

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

**Restituisce:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)