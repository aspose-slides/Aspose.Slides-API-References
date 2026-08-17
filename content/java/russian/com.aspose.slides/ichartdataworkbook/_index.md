---
title: IChartDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: Предоставляет доступ к встроенной книге Excel
type: docs
url: /ru/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Предоставляет доступ к встроенной книге Excel
## Методы

| Методы | Описание |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Вычисляет все формулы в книге и обновляет соответствующие значения ячеек. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Получает набор ячеек. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Получает ячейку, которую можно использовать для серии или категорий диаграммы |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Получает ячейку, которую можно использовать для серии или категорий диаграммы |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Получает ячейку, которую можно использовать для серии или категорий диаграммы |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Получает ячейку, которую можно использовать для серии или категорий диаграммы |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Получает ячейку, которую можно использовать для серии или категорий диаграммы |
| [clear(int sheetIndex)](#clear-int-) | Очищает все значения ячеек на листе |
| [getWorksheets()](#getWorksheets--) | Получает коллекцию листов. |

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

Получает набор ячеек.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | java.lang.String | Excel-формула, например "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Если true, метод возвращает коллекцию без скрытых ячеек. |

**Возвращает:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - набор ячеек [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

Получает ячейку, которую можно использовать для серии или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | java.lang.String | Имя листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |

**Возвращает:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Получает ячейку, которую можно использовать для серии или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |

**Возвращает:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

Получает ячейку, которую можно использовать для серии или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| cellName | java.lang.String | Имя ячейки. |

**Возвращает:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Получает ячейку, которую можно использовать для серии или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| cellName | java.lang.String | Имя ячейки. |
| value | java.lang.Object | Значение. |

**Возвращает:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Получает ячейку, которую можно использовать для серии или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |
| value | java.lang.Object | Значение. |

**Возвращает:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - объект Cell

### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

Очищает все значения ячеек на листе

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sheetIndex | int | Индекс листа |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

Получает коллекцию листов.

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

**Возвращает:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)