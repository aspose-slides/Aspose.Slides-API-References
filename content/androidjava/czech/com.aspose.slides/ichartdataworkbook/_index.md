---
title: IChartDataWorkbook
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Poskytuje přístup k vloženému sešitu Excelu
type: docs
url: /cs/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Poskytuje přístup k vloženému sešitu Excelu
## Metody

| Metoda | Popis |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Vypočítá všechny vzorce v sešitu a aktualizuje odpovídající hodnoty buněk. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Získá množinu buněk. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Získá buňku, která může být použita pro sérii grafu nebo kategorie |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Získá buňku, která může být použita pro sérii grafu nebo kategorie |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Získá buňku, která může být použita pro sérii grafu nebo kategorie |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Získá buňku, která může být použita pro sérii grafu nebo kategorie |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Získá buňku, která může být použita pro sérii grafu nebo kategorie |
| [clear(int sheetIndex)](#clear-int-) | Vymaže všechny hodnoty buněk na listu |
| [getWorksheets()](#getWorksheets--) | Získá kolekci listů. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```


Vypočítá všechny vzorce v sešitu a aktualizuje odpovídající hodnoty buněk.

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


Získá množinu buněk.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formula | java.lang.String | Excel formula, například "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Pokud je true, metoda vrátí kolekci bez skrytých buněk. |

**Vrací:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Množina buněk [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


Získá buňku, která může být použita pro sérii grafu nebo kategorie

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | java.lang.String | Název listu. |
| row | int | Řádek. |
| column | int | Sloupec. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Objekt buňky
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Získá buňku, která může být použita pro sérii grafu nebo kategorie

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu. |
| row | int | Řádek. |
| column | int | Sloupec. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Objekt buňky
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


Získá buňku, která může být použita pro sérii grafu nebo kategorie

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu. |
| cellName | java.lang.String | Název buňky. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Objekt buňky
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Získá buňku, která může být použita pro sérii grafu nebo kategorie

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu. |
| cellName | java.lang.String | Název buňky. |
| value | java.lang.Object | Hodnota. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Objekt buňky
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Získá buňku, která může být použita pro sérii grafu nebo kategorie

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu. |
| row | int | Řádek. |
| column | int | Sloupec. |
| value | java.lang.Object | Hodnota. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Objekt buňky
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


Vymaže všechny hodnoty buněk na listu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sheetIndex | int | Index listu |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```


Získá kolekci listů.

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

**Vrací:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)