---
title: IChartDataWorkbook
second_title: Aspose.Slides for Java – Referencja API
description: Zapewnia dostęp do osadzonego skoroszytu Excel
type: docs
url: /pl/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Zapewnia dostęp do osadzonego skoroszytu Excel
## Metody

| Metoda | Opis |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Calculates all formulas in the workbook and updates corresponding cells values. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Gets the set of cells. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Gets the cell that can be used for chart series or categories |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Gets the cell that can be used for chart series or categories |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Gets the cell that can be used for chart series or categories |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Gets the cell that can be used for chart series or categories |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Gets the cell that can be used for chart series or categories |
| [clear(int sheetIndex)](#clear-int-) | Clear all cells values on sheet |
| [getWorksheets()](#getWorksheets--) | Gets a collection of worksheets. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

Oblicza wszystkie formuły w skoroszycie i aktualizuje odpowiadające wartości komórek.

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

Pobiera zestaw komórek.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formula | java.lang.String | Formuła Excel, np. "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Jeśli true, metoda zwraca kolekcję bez ukrytych komórek. |

**Zwraca:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Zestaw komórek [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

Pobiera komórkę, którą można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | java.lang.String | Nazwa arkusza. |
| row | int | Wiersz. |
| column | int | Kolumna. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Obiekt Cell
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Pobiera komórkę, którą można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza. |
| row | int | Wiersz. |
| column | int | Kolumna. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Obiekt Cell
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

Pobiera komórkę, którą można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza. |
| cellName | java.lang.String | Nazwa komórki. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Obiekt Cell
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Pobiera komórkę, którą można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza. |
| cellName | java.lang.String | Nazwa komórki. |
| value | java.lang.Object | Wartość. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Obiekt Cell
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Pobiera komórkę, którą można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza. |
| row | int | Wiersz. |
| column | int | Kolumna. |
| value | java.lang.Object | Wartość. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Obiekt Cell
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

Czyści wszystkie wartości komórek na arkuszu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sheetIndex | int | Indeks arkusza |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

Pobiera kolekcję arkuszy.

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

**Zwraca:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)