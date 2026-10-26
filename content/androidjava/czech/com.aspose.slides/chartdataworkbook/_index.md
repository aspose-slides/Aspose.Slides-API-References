---
title: ChartDataWorkbook
second_title: Aspose.Slides pro Android přes referenci Java API
description: Poskytuje přístup k vloženému sešitu Excel
type: docs
url: /cs/com.aspose.slides/chartdataworkbook/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Poskytuje přístup k vloženému sešitu Excel
## Metody

| Metoda | Popis |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Získá kolekci listů. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Získá sadu buněk. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Získá buňku, která může být použita pro řady nebo kategorie grafu |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Získá buňku, která může být použita pro řady nebo kategorie grafu |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Získá buňku, která může být použita pro řady nebo kategorie grafu |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Získá buňku, která může být použita pro řady nebo kategorie grafu |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Získá buňku, která může být použita pro řady nebo kategorie grafu |
| [clear(int sheetIndex)](#clear-int-) | Vymaže všechny hodnoty buněk na listu |
| [calculateFormulas()](#calculateFormulas--) | Vypočítá všechny vzorce v sešitu a aktualizuje odpovídající hodnoty buněk. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
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
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Získá sadu buněk.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formula | java.lang.String | Excelový vzorec, např. "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Pokud je true, metoda vrátí kolekci bez skrytých buněk. |

**Vrací:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


Získá buňku, která může být použita pro řady nebo kategorie grafu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetName | java.lang.String | Název listu. |
| row | int | Řádek. |
| column | java.lang.Integer | Sloupec. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Získá buňku, která může být použita pro řady nebo kategorie grafu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu. |
| row | int | Řádek. |
| column | int | Sloupec. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


Získá buňku, která může být použita pro řady nebo kategorie grafu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu. |
| cellName | java.lang.String | Název buňky. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Získá buňku, která může být použita pro řady nebo kategorie grafu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu. |
| cellName | java.lang.String | Název buňky. |
| value | java.lang.Object | Hodnota. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Získá buňku, která může být použita pro řady nebo kategorie grafu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| worksheetIndex | int | Index listu. |
| row | int | Řádek. |
| column | int | Sloupec. |
| value | java.lang.Object | Hodnota. |

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


Vymaže všechny hodnoty buněk na listu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sheetIndex | int | Index listu |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Vypočítá všechny vzorce v sešitu a aktualizuje odpovídající hodnoty buněk.

--------------------

> ```
> Příklad ukazuje, jak přiřadit buňce vzorec a vypočítat hodnotu. Hodnota buňky "B4" je nastavena na 5.
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