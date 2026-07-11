---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Provides access to embedded Excel workbook
type: docs
url: /ru/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Обеспечивает доступ к встроенной книге Excel
## Методы

| Метод | Описание |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Вычисляет все формулы в книге и обновляет соответствующие значения ячеек. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Возвращает набор ячеек. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий |
| [clear(int sheetIndex)](#clear-int-) | Очистить все значения ячеек на листе |
| [getWorksheets()](#getWorksheets--) | Возвращает коллекцию листов. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

Вычисляет все формулы в книге и обновляет соответствующие значения ячеек.

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

Возвращает набор ячеек.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | java.lang.String | Формула Excel, например "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Если true, метод возвращает коллекцию без скрытых ячеек. |

**Возвращаемое значение:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Set of cells [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | java.lang.String | Имя листа. |
| row | int | Строка. |
| column | int | Столбец. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| row | int | Строка. |
| column | int | Столбец. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| cellName | java.lang.String | Имя ячейки. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| cellName | java.lang.String | Имя ячейки. |
| value | java.lang.Object | Значение. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Возвращает ячейку, которую можно использовать для рядов диаграммы или категорий

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| row | int | Строка. |
| column | int | Столбец. |
| value | java.lang.Object | Значение. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

Очистить все значения ячеек на листе

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sheetIndex | int | Индекс листа |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

Возвращает коллекцию листов.

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