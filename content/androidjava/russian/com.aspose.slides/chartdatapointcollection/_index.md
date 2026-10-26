---
title: ChartDataPointCollection
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет коллекцию точек данных серии.
type: docs
url: /ru/com.aspose.slides/chartdatapointcollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Представляет коллекцию точек данных серии.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Возвращает точку данных серии по индексу (ее порядковый номер в этой коллекции). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Возвращает индекс (порядковый номер) точки данных в этой коллекции. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства XValue точек данных. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства XValue точек данных. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства YValue точек данных. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства YValue точек данных. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства BubbleSize точек данных. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства BubbleSize точек данных. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства Value точек данных. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства Value точек данных. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Указывает типы значений в списке свойств ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Если коллекция уже содержит точку данных с индексом index, то возвращает эту точку данных. |
| [size()](#size--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корневой объект синхронизации. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по элементам коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
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
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Создает новую точку данных и добавляет её в конец коллекции. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Удаляет указанное значение. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Возвращает точку данных серии по индексу (ее порядковый номер в этой коллекции).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

Возвращает индекс (порядковый номер) точки данных в этой коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Возвращаемое значение:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства XValue точек данных. Другими словами, задает тип значения свойства ChartDataPoint.XValue.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Возвращаемое значение:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceForXValues(int value)
```

Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства XValue точек данных. Другими словами, задает тип значения свойства ChartDataPoint.XValue.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства YValue точек данных. Другими словами, задает тип значения свойства ChartDataPoint.YValue.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Возвращаемое значение:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства YValue точек данных. Другими словами, задает тип значения свойства ChartDataPoint.YValue.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства BubbleSize точек данных. Другими словами, задает тип значения свойства ChartDataPoint.BubbleSize.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Возвращаемое значение:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства BubbleSize точек данных. Другими словами, задает тип значения свойства ChartDataPoint.BubbleSize.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства Value точек данных. Другими словами, задает тип значения свойства ChartDataPoint.Value.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Возвращаемое значение:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Указывает, активировано ли свойство AsCell или AsLiteralString или AsLiteralDouble в объекте свойства Value точек данных. Другими словами, задает тип значения свойства ChartDataPoint.Value.Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Указывает типы значений в списке свойств ChartDataPoint.ErrorBarsCustomValues. Только для чтения [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Возвращаемое значение:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Если коллекция уже содержит точку данных с индексом index, то возвращает эту точку данных. Если в коллекции нет точки данных с индексом index==N (когда количество точек данных в этой коллекции меньше или равно N), то добавляются недостающие точки данных и возвращается последняя (которая имеет запрошенный индекс). Например, индексы коллекции — {0, 1, 2}, а запрошенный индекс — 5. Тогда метод добавит недостающие точки: {0, 1, 2, 3, 4, 5} и вернёт точку данных с индексом 5.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | long | Индекс. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Возвращает точку данных с запрошенным индексом.
### size() {#size--}
```
public final int size()
```

Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращаемое значение:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Копирует в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Массив для копирования. |
| arrayIndex | int | Индекс начала копирования. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает корневой объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Возвращает перечислитель, который проходит по элементам коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator для всей коллекции.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Stock (см. также метод [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Stock (см. также метод [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Line (см. также метод [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Line (см. также метод [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных. |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Scatter (см. также метод [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Scatter (см. также метод [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Scatter (см. также метод [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Scatter (см. также метод [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Scatter (см. также метод [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Scatter (см. также метод [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Radar (см. также метод [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Radar (см. также метод [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Column или Bar (см. также метод [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) и [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Column или Bar (см. также метод [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) и [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Area (см. также метод [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Area (см. также метод [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Pie (см. также метод [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Pie (см. также метод [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Doughnut (см. также метод [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Doughnut (см. также метод [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |
| bubbleSize | double | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры::
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |
| bubbleSize | double | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | Значение XValue точки данных |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение YValue точки данных |
| bubbleSize | double | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |
| bubbleSize | double | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | double | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |
| bubbleSize | double | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Bubble (см. также метод [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xValue | java.lang.String | Значение XValue точки данных |
| yValue | double | Значение YValue точки данных |
| bubbleSize | double | Значение BubbleSize точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Surface (см. также метод [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых chartType является одним из подтипов Surface (см. также метод [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых тип диаграммы — Sunburst.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение SizeValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых тип диаграммы — Treemap.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение SizeValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых тип диаграммы — BoxAndWhisker.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public **** **?****
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых тип диаграммы — Waterfall.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых тип диаграммы — Histogram.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых тип диаграммы — Funnel.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Создает новую точку данных и добавляет её в конец коллекции. Применимо для серий, у которых тип диаграммы — Map.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Значение ColorValue точки данных |

**Возвращаемое значение:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Новая точка данных.
### clear() {#clear--}
```
public final void clear()
```

Удаляет все элементы из коллекции.
### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Удаляет указанное значение.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Значение. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс точки данных для удаления. |