---
title: ChartDataWorkbook
second_title: Aspose.Slides dla Java – odniesienie API
description: Zapewnia dostęp do osadzonego skoroszytu Excel
type: docs
url: /pl/com.aspose.slides/chartdataworkbook/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Zapewnia dostęp do osadzonego skoroszytu Excel
## Metody

| Metoda | Opis |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Pobiera kolekcję arkuszy. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Pobiera zestaw komórek. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Pobiera komórkę, której można użyć dla serii wykresu lub kategorii |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Pobiera komórkę, której można użyć dla serii wykresu lub kategorii |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Pobiera komórkę, której można użyć dla serii wykresu lub kategorii |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Pobiera komórkę, której można użyć dla serii wykresu lub kategorii |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Pobiera komórkę, której można użyć dla serii wykresu lub kategorii |
| [clear(int sheetIndex)](#clear-int-) | Wyczyść wszystkie wartości komórek w arkuszu |
| [calculateFormulas()](#calculateFormulas--) | Oblicza wszystkie formuły w skoroszycie i aktualizuje odpowiadające wartości komórek. |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Pobiera zestaw komórek.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formula | java.lang.String | Formuła Excel, np. "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Jeśli true, metoda zwraca kolekcję bez ukrytych komórek. |

**Zwraca:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Pobiera komórkę, której można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetName | java.lang.String | Nazwa arkusza. |
| row | int | Wiersz. |
| column | int | Kolumna. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Pobiera komórkę, której można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza. |
| row | int | Wiersz. |
| column | int | Kolumna. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Pobiera komórkę, której można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza. |
| cellName | java.lang.String | Nazwa komórki. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Pobiera komórkę, której można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza. |
| cellName | java.lang.String | Nazwa komórki. |
| value | java.lang.Object | Wartość. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Pobiera komórkę, której można użyć dla serii wykresu lub kategorii

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| worksheetIndex | int | Indeks arkusza. |
| row | int | Wiersz. |
| column | int | Kolumna. |
| value | java.lang.Object | Wartość. |

**Zwraca:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Wyczyść wszystkie wartości komórek w arkuszu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sheetIndex | int | Indeks arkusza |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

Oblicza wszystkie formuły w skoroszycie i aktualizuje odpowiadające wartości komórek.

--------------------

> ```
> Przykład pokazuje, jak przypisać formułę do komórki i obliczyć wartość. Wartość komórki "B4" jest ustawiana na 5.
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