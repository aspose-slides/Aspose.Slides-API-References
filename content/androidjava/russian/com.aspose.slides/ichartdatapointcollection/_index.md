---
title: IChartDataPointCollection
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет коллекцию точек данных серии.
type: docs
url: /ru/com.aspose.slides/ichartdatapointcollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Представляет коллекцию точек данных серии.
## Методы

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает точку данных серии по индексу (его порядковый номер в этой коллекции). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Возвращает индекс (порядковый номер в этой коллекции) точки данных в этой коллекции. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства XValue точек данных. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства XValue точек данных. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства YValue точек данных. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства YValue точек данных. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства BubbleSize точек данных. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства BubbleSize точек данных. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства Value точек данных. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства Value точек данных. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Указывает тип значений в списке свойств ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Если коллекция уже содержит точку данных с индексом index, то возвращает эту точку данных. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Удаляет указанное значение. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по заданному индексу. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Возвращает точку данных серии по индексу (его порядковый номер в этой коллекции).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Возвращает индекс (порядковый номер в этой коллекции) точки данных в этой коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Возвращаемое значение:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства XValue точек данных. Другими словами, указывает тип значения свойства ChartDataPointEx.XValue.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Возвращаемое значение:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства XValue точек данных. Другими словами, указывает тип значения свойства ChartDataPointEx.XValue.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства YValue точек данных. Другими словами, указывает тип значения свойства ChartDataPointEx.YValue.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Возвращаемое значение:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства YValue точек данных. Другими словами, указывает тип значения свойства ChartDataPointEx.YValue.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства BubbleSize точек данных. Другими словами, указывает тип значения свойства ChartDataPointEx.BubbleSize.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Возвращаемое значение:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства BubbleSize точек данных. Другими словами, указывает тип значения свойства ChartDataPointEx.BubbleSize.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства Value точек данных. Другими словами, указывает тип значения свойства ChartDataPoint.Value.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Возвращаемое значение:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Указывает, является ли свойство AsCell или AsLiteralString или AsLiteralDouble актуальным в объекте свойства Value точек данных. Другими словами, указывает тип значения свойства ChartDataPoint.Value.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Указывает тип значений в списке свойств ChartDataPoint.ErrorBarsCustomValues. Только для чтения [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Возвращаемое значение:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Если коллекция уже содержит точку данных с индексом index, то возвращает эту точку данных. Если в коллекции нет точки данных с индексом index==N (когда количество точек данных в этой коллекции меньше или равно N), то добавляет недостающие точки данных и возвращает последнюю (которая имеет запрошенный индекс). Например, индексы коллекции \{0, 1, 2\}, а запрошенный индекс 5. Тогда метод добавляет недостающие точки данных: \{0, 1, 2, 3, 4, 5\}. И возвращает точку данных с индексом 5.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | long | Индекс. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Возвращает точку данных с запрошенным индексом.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Stock (см. также метод ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Stock (см. также метод ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Line (см. также метод ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Line (см. также метод ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Scatter (см. также метод ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Scatter (см. также метод ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Scatter (см. также метод ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Scatter (см. также метод ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue точки данных |
| yValue | double | YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Scatter (см. также метод ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | XValue точки данных |
| yValue | double | YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Scatter (см. также метод ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | XValue точки данных |
| yValue | double | YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Radar (см. также метод ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Radar (см. также метод ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Column или Bar (см. также методы ChartTypeCharacterizer.IsChartTypeColumn(ChartType) и ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Column или Bar (см. также методы ChartTypeCharacterizer.IsChartTypeColumn(ChartType) и ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Area (см. также метод ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Area (см. также метод ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Pie (см. также метод ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Pie (см. также метод ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Doughnut (см. также метод ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Doughnut (см. также метод ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue точки данных |
| yValue | double | YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | XValue точки данных |
| yValue | double | YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | XValue точки данных |
| yValue | double | YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |
| bubbleSize | double | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |
| bubbleSize | double | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue точки данных |
| bubbleSize | double | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue точки данных |
| yValue | double | YValue точки данных |
| bubbleSize | double | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | XValue точки данных |
| yValue | double | YValue точки данных |
| bubbleSize | double | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Bubble (см. также метод ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | XValue точки данных |
| yValue | double | YValue точки данных |
| bubbleSize | double | BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Surface (см. также метод ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых chartType является одним из подтипов Surface (см. также метод ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых тип диаграммы Sunburst.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых тип диаграммы Waterfall.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых тип диаграммы BoxAndWhisker.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых тип диаграммы Treemap.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых тип диаграммы Histogram.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых тип диаграммы Funnel.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо к сериям, у которых тип диаграммы Map.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы из коллекции.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Удаляет указанное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Значение. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс точки данных для удаления. |