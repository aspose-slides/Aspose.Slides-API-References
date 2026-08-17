---
title: ChartData
second_title: Справочник API Aspose.Slides для Java
description: Представляет данные, используемые для построения диаграммы.
type: docs
url: /ru/com.aspose.slides/chartdata/
---
**Наследование:**  
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**  
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)  
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Представляет данные, используемые для построения диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Получает фабрику ячеек для создания ячеек, используемых в сериях диаграммы или категориях. |
| [getSeries()](#getSeries--) | Получает серии. |
| [getSeriesGroups()](#getSeriesGroups--) | Получает группы серий. |
| [getCategories()](#getCategories--) | Получает первичные категории (или обе первичные и вторичные категории, если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Если false, то свойство \#getSecondaryCategories.getSecondaryCategories возвращает null, и данные в свойстве \#getCategories.getCategories используются как для первичных, так и для вторичных серий. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Если false, то свойство \#getSecondaryCategories.getSecondaryCategories возвращает null, и данные в свойстве \#getCategories.getCategories используются как для первичных, так и для вторичных серий. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Получает вторичные категории, если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно true. |
| [readWorkbookStream()](#readWorkbookStream--) | Записывает внутреннюю книгу Excel в поток в памяти. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Инициализирует внутреннюю книгу Excel значением, заданным пользователем. |
| [getDataSourceType()](#getDataSourceType--) | Представляет путь к внешней книге, если внешний источник данных, иначе null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Представляет источник данных диаграммы. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Получает тип внедрённой книги. |
| [getRange()](#getRange--) | Получает диапазон данных диаграммы. |
| [setRange(String formula)](#setRange-java.lang.String-) | Устанавливает диапазон данных диаграммы. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Устанавливает внешнюю книгу в качестве источника данных для диаграммы. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Устанавливает внешнюю книгу в качестве источника данных для диаграммы. |
| [switchRowColumn()](#switchRowColumn--) | Меняет данные местами по оси. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Получает фабрику ячеек для создания ячеек, используемых в сериях диаграммы или категориях. Только для чтения [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Возвращаемое значение:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Получает серии. Только для чтения [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Возвращаемое значение:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Получает группы серий. Только для чтения [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Каждая группа серий содержит серии совместимых типов. Группы совместимых типов серий определены и описаны перечислением CombinableSeriesTypesGroup. Кроме того, каждая группа серий содержит серии, которые отображаются либо на первичной оси, либо на вторичной оси (не оба варианта в одной группе). Таким образом, принцип группировки серий — группировка по типам групп, упомянутым выше, и по типу отображения (первичная/вторичная). 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («свойства группы серий»). «Свойства группы серий» в классе ChartSeriesGroup доступны для чтения/записи. Каждое из «свойств группы серий» может иметь только для чтения проекцию в классе ChartSeries.

**Возвращаемое значение:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Получает первичные категории (или обе первичные и вторичные категории, если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно false). Только для чтения [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории — series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории — series.getChart().getChartData().getCategories()
>  }
> ```


--------------------

Если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, и данные в свойстве \#getCategories.getCategories используются как для первичных, так и для вторичных серий. Если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно true, то данные в свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных серий, а данные в свойстве \#getCategories.getCategories — для первичных серий.

**Возвращаемое значение:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Если false, то свойство \#getSecondaryCategories.getSecondaryCategories возвращает null, и данные в свойстве \#getCategories.getCategories используются как для первичных, так и для вторичных серий. Если true, то данные в свойстве \#getSecondaryCategories.getSecondaryCategories используются для вторичных серий, а данные в свойстве \#getCategories.getCategories — для первичных серий. Чтение/запись boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории — series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории — series.getChart().getChartData().getCategories()
>  }
> ```

**Возвращаемое значение:**  
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Если false, то свойство \#getSecondaryCategories.getSecondaryCategories возвращает null, и данные в свойстве \#getCategories.getCategories используются как для первичных, так и для вторичных серий. Если true, то данные в свойстве \#getSecondaryCategories.getSecondaryCategories используются для вторичных серий, а данные в свойстве \#getCategories.getCategories — для первичных серий. Чтение/запись boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории — series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории — series.getChart().getChartData().getCategories()
>  }
> ```

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Получает вторичные категории, если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно true. Только для чтения [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории — series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории — series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно false, то это свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, и данные в свойстве \#getCategories.getCategories используются как для первичных, так и для вторичных серий. Если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно true, то данные в этом свойстве \#getSecondaryCategories.getSecondaryCategories используются для вторичных серий, а данные в свойстве \#getCategories.getCategories — для первичных серий.

**Возвращаемое значение:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Записывает внутреннюю книгу Excel в поток в памяти.

**Возвращаемое значение:**  
byte[] - Возвращает экземпляр массива байтов, содержащий копию внутренней книги Excel.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Инициализирует внутреннюю книгу Excel значением, заданным пользователем.

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| ms | byte[] | Поток, предоставленный пользователем, содержащий всю книгу Excel. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Представляет путь к внешней книге, если внешний источник данных, иначе null.

**Возвращаемое значение:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Представляет источник данных диаграммы.

**Возвращаемое значение:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Получает тип внедрённой книги. Возвращает [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined), если DataSourceType (\#getDataSourceType.getDataSourceType) равен [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Только для чтения [WorkbookType](../../com.aspose.slides/workbooktype).

**Возвращаемое значение:**  
int

### getRange() {#getRange--}
```
public final String getRange()
```

Получает диапазон данных диаграммы.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Возвращаемое значение:**  
java.lang.String - Формула диапазона данных ячеек. Например: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Устанавливает диапазон данных диаграммы. Серии и категории будут обновлены в соответствии с новым диапазоном данных. Если количество серий в диапазоне данных превышает количество серий в данных диаграммы, то дополнительные серии того же типа, что и последняя серия в текущей коллекции, будут добавлены в конец коллекции.

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | java.lang.String | Формула диапазона данных ячеек. Например: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Устанавливает внешнюю книгу в качестве источника данных для диаграммы. Данные диаграммы будут обновлены из целевой книги.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | java.lang.String | Путь к целевой книге |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Устанавливает внешнюю книгу в качестве источника данных для диаграммы.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | java.lang.String | Путь к целевой книге |
| updateChartData | boolean | Если значение false, будет обновлен только путь к книге. Данные диаграммы не будут загружены и обновлены из целевой книги. Может использоваться, когда целевая книга не существует или недоступна. Если значение true, данные диаграммы будут обновлены из целевой книги. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Меняет данные местами по оси. Данные, построенные по оси X, перемещаются на ось Y и наоборот.