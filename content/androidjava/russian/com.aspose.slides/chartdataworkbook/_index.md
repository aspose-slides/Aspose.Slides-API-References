---
title: ChartDataWorkbook
second_title: Aspose.Slides для Android через справочник Java API
description: Обеспечивает доступ к встроенной книге Excel
type: docs
url: /ru/com.aspose.slides/chartdataworkbook/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Обеспечивает доступ к встроенной книге Excel
## Методы

| Метод | Описание |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Получает коллекцию worksheets. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Получает набор cells. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Получает cell, который можно использовать для series или categories диаграммы |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Получает cell, который можно использовать для series или categories диаграммы |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Получает cell, который можно использовать для series или categories диаграммы |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Получает cell, который можно использовать для series или categories диаграммы |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Получает cell, который можно использовать для series или categories диаграммы |
| [clear(int sheetIndex)](#clear-int-) | Очищает все значения cells на листе |
| [calculateFormulas()](#calculateFormulas--) | Вычисляет все формулы в рабочей книге и обновляет соответствующие значения cells. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

Получает коллекцию worksheets.

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

**Возвращаемое значение:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Получает набор cells.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | java.lang.String | Формула Excel, например "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Если true, метод возвращает набор без скрытых cells. |

**Возвращаемое значение:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

Получает cell, который можно использовать для series или categories диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | java.lang.String | Имя листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Получает cell, который можно использовать для series или categories диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

Получает cell, который можно использовать для series или categories диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| cellName | java.lang.String | Имя cell. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Получает cell, который можно использовать для series или categories диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| cellName | java.lang.String | Имя cell. |
| value | java.lang.Object | Значение. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Получает cell, который можно использовать для series или categories диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |
| value | java.lang.Object | Значение. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

Очищает все значения cells на листе

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sheetIndex | int | Индекс листа |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

Вычисляет все формулы в рабочей книге и обновляет соответствующие значения cells.

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