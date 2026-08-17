---
title: ChartDataWorkbook
second_title: Справочник API Aspose.Slides для Java
description: Обеспечивает доступ к встроенному Excel workbook
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

Обеспечивает доступ к встроенной рабочей книге Excel
## Методы

| Метод | Описание |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Получает коллекцию листов. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Получает набор ячеек. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Получает ячейку, которую можно использовать для рядов или категорий диаграммы |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Получает ячейку, которую можно использовать для рядов или категорий диаграммы |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Получает ячейку, которую можно использовать для рядов или категорий диаграммы |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Получает ячейку, которую можно использовать для рядов или категорий диаграммы |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Получает ячейку, которую можно использовать для рядов или категорий диаграммы |
| [clear(int sheetIndex)](#clear-int-) | Очищает все значения ячеек на листе |
| [calculateFormulas()](#calculateFormulas--) | Вычисляет все формулы в рабочей книге и обновляет соответствующие значения ячеек. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
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

**Возвращаемое значение:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Получает набор ячеек.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | java.lang.String | Формула Excel, например "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Если true, метод возвращает коллекцию без скрытых ячеек. |

**Возвращаемое значение:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


Получает ячейку, которую можно использовать для рядов или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | java.lang.String | Имя листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Получает ячейку, которую можно использовать для рядов или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


Получает ячейку, которую можно использовать для рядов или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| cellName | java.lang.String | Имя ячейки. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Получает ячейку, которую можно использовать для рядов или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| cellName | java.lang.String | Имя ячейки. |
| value | java.lang.Object | Значение. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Получает ячейку, которую можно использовать для рядов или категорий диаграммы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | int | Индекс листа. |
| row | int | Номер строки. |
| column | int | Номер столбца. |
| value | java.lang.Object | Значение. |

**Возвращаемое значение:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


Очищает все значения ячеек на листе

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sheetIndex | int | Индекс листа |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Вычисляет все формулы в рабочей книге и обновляет соответствующие значения ячеек.

--------------------

> ```
> Пример показывает, как присвоить ячейке формулу и вычислить значение. Значение ячейки "B4" устанавливается в 5.
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