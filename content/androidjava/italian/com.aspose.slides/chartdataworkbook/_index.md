---
title: ChartDataWorkbook
second_title: Riferimento API Java di Aspose.Slides per Android
description: Fornisce l'accesso a una cartella di lavoro Excel incorporata
type: docs
url: /it/com.aspose.slides/chartdataworkbook/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Fornisce l'accesso a una cartella di lavoro Excel incorporata
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Restituisce una raccolta di fogli di lavoro. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Restituisce l'insieme delle celle. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Restituisce la cella che può essere utilizzata per le serie o le categorie del grafico |
| [clear(int sheetIndex)](#clear-int-) | Cancella tutti i valori delle celle nel foglio |
| [calculateFormulas()](#calculateFormulas--) | Calcola tutte le formule nella cartella di lavoro e aggiorna i valori delle celle corrispondenti. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


Restituisce una raccolta di fogli di lavoro.

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
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Restituisce l'insieme delle celle.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | java.lang.String | Formula Excel come "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Se true, il metodo restituisce la raccolta senza le celle nascoste. |

**Restituisce:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
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
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
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
public final IChartDataCell getCell(int worksheetIndex, String cellName)
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
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
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
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
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
public final void clear(int sheetIndex)
```


Cancella tutti i valori delle celle nel foglio

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sheetIndex | int | Indice del foglio |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Calcola tutte le formule nella cartella di lavoro e aggiorna i valori delle celle corrispondenti.

--------------------

> ```
> Esempio mostra come assegnare una formula alla cella e calcolare un valore. Il valore della cella "B4" viene impostato a 5.
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