---
title: IChartSeries
second_title: Справочник API Aspose.Slides для Java
description: Представляет серию диаграммы.
type: docs
url: /ru/com.aspose.slides/ichartseries/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Represents a chart series.
## Методы

| Method | Description |
| --- | --- |
| [getExplosion()](#getExplosion--) | Расстояние открытого куска пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. |
| [setExplosion(int value)](#setExplosion-int-) | Расстояние открытого куска пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. |
| [getSmooth()](#getSmooth--) | Представляет сглаживание кривой. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Представляет сглаживание кривой. |
| [getMarker()](#getMarker--) | Возвращает маркер серии. |
| [getBar3DShape()](#getBar3DShape--) | Указывает форму серии трехмерной столбчатой диаграммы. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Указывает форму серии трехмерной столбчатой диаграммы. |
| [getName()](#getName--) | Возвращает имя серии. |
| [getDataPoints()](#getDataPoints--) | Возвращает коллекцию точек данных этой серии. |
| [getType()](#getType--) | Возвращает тип этой серии. |
| [setType(int value)](#setType-int-) | Возвращает тип этой серии. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Возвращает родительскую группу серий. |
| [getFormat()](#getFormat--) | Возвращает формат серии. |
| [getOrder()](#getOrder--) | Возвращает порядок серии. |
| [setOrder(int value)](#setOrder-int-) | Возвращает порядок серии. |
| [getLabels()](#getLabels--) | Возвращает метки серии. |
| [getTrendLines()](#getTrendLines--) | Коллекция линий тренда серии (только для чтения) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Представляет линии ошибок серии с направлением X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Представляет линии ошибок серии с направлением Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, построена ли эта серия на второй оси значений. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Указывает, построена ли эта серия на второй оси значений. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Возвращает или задает числовой формат значений серии. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Возвращает или задает числовой формат значений серии. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Возвращает или задает числовой формат значений X серии. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Возвращает или задает числовой формат значений X серии. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Возвращает или задает числовой формат значений Y серии. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Возвращает или задает числовой формат значений Y серии. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Возвращает или задает числовой формат размеров пузырей серии. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Возвращает или задает числовой формат размеров пузырей серии. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Указывает, что столбчатая, колонная или пузырьковая серия должна инвертировать цвета, если значение отрицательное. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Указывает, что столбчатая, колонная или пузырьковая серия должна инвертировать цвета, если значение отрицательное. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Указывает инвертировать сплошной цвет для серии. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Представляет элемент легенды, связанный с этой серией (только для чтения) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Возвращает автоматический цвет серии, основанный на индексе серии и стиле диаграммы. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Представляет внутренние точки. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Представляет внутренние точки. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Представляет выбросы. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Представляет выбросы. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Представляет маркеры среднего. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Представляет маркеры среднего. |
| [getShowMeanLine()](#getShowMeanLine--) | Представляет маркеры среднего. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Представляет маркеры среднего. |
| [getQuartileMethod()](#getQuartileMethod--) | Представляет метод квартилей. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Представляет метод квартилей. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Представляет соединительные линии. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Представляет соединительные линии. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Представляет расположение меток родительской категории. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Представляет расположение меток родительской категории. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). |
| [hasUpDownBars()](#hasUpDownBars--) | Определяет, имеет ли линейная или биржевая диаграмма восходящие/нисходящие полосы. |
| [getGapWidth()](#getGapWidth--) | Указывает расстояние между кластерами столбцов или колонок в процентах от ширины столбца или колонки. |
| [getGapDepth()](#getGapDepth--) | Возвращает или задает расстояние, в процентах от ширины маркера, между сериями данных в 3D-диаграмме. |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [hasSeriesLines()](#hasSeriesLines--) | Определяет, есть ли линии серии для этой серии и связанных серий. |
| [getOverlap()](#getOverlap--) | Указывает степень перекрытия столбцов и колонок на 2D-диаграммах в процентах (от -100% до 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Указывает размер второй части пирога или столбца в диаграмме «пирог в пироге» или «столбец в пироге», в процентах от размера первого пирога (может быть от 5% до 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Задает значение, используемое для определения, какие точки данных находятся во второй части пирога или столбце в диаграмме «пирог в пироге» или «столбец в пироге». |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определить, какие точки данных находятся во второй части пирога или столбце в диаграмме «пирог в пироге» или «столбец в пироге». |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10% до 90% от размера области построения). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Указывает угол первого куска пирога или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Пользовательская информация о разбиении для диаграммы «пирог в пироге» или «столбец в пироге» с пользовательским разбиением. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Расстояние открытого куска пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. Чтение/Запись int.

**Возврат:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Расстояние открытого куска пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. Чтение/Запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Представляет сглаживание кривой. True если сглаживание включено для линейной или точечной диаграммы, соединенной линиями. Применяется только к линейным и точечным диаграммам, соединенным линиями. Чтение/Запись boolean.

**Возврат:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Представляет сглаживание кривой. True если сглаживание включено для линейной или точечной диаграммы, соединенной линиями. Применяется только к линейным и точечным диаграммам, соединенным линиями. Чтение/Запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Возвращает маркер серии. Только для чтения [IMarker](../../com.aspose.slides/imarker).

**Возврат:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Указывает форму серии трехмерной столбчатой диаграммы. Изменение значения этого свойства может привести к автоматическому изменению типа серии. Чтение/Запись [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Возврат:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Указывает форму серии трехмерной столбчатой диаграммы. Изменение значения этого свойства может привести к автоматическому изменению типа серии. Чтение/Запись [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Возвращает имя серии. Только для чтения [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Возврат:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Возвращает коллекцию точек данных этой серии. Только для чтения [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Возврат:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Возвращает тип этой серии. Чтение/Запись [ChartType](../../com.aspose.slides/charttype).

**Возврат:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Возвращает тип этой серии. Чтение/Запись [ChartType](../../com.aspose.slides/charttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Возвращает родительскую группу серий. Только для чтения [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Возврат:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Возвращает формат серии. Только для чтения [IFormat](../../com.aspose.slides/iformat).

**Возврат:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Возвращает порядок серии. Чтение/Запись int.

**Возврат:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Возвращает порядок серии. Чтение/Запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Возвращает метки серии. Только для чтения [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Возврат:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Коллекция линий тренда серии (только для чтения) [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Возврат:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Представляет линии ошибок серии с направлением X. Только для чтения [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars с направлением X доступны для серий типов area, bar, scatter и bubble. Для остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). При использовании пользовательских значений используйте коллекцию DataPoints для задания значения (со свойством ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Возврат:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Представляет линии ошибок серии с направлением Y. Только для чтения [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars с направлением Y доступны для серий типов area, bar, line, scatter и bubble. Для остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). При использовании пользовательских значений используйте коллекцию DataPoints для задания значения (со свойством ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Возврат:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Указывает, построена ли эта серия на второй оси значений. Чтение/Запись boolean.

**Возврат:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Указывает, построена ли эта серия на второй оси значений. Чтение/Запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Возвращает или задает числовой формат значений серии. Чтение/Запись String.

**Возврат:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Возвращает или задает числовой формат значений серии. Чтение/Запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Возвращает или задает числовой формат значений X серии. Чтение/Запись String.

**Возврат:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Возвращает или задает числовой формат значений X серии. Чтение/Запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Возвращает или задает числовой формат значений Y серии. Чтение/Запись String.

**Возврат:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Возвращает или задает числовой формат значений Y серии. Чтение/Запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Возвращает или задает числовой формат размеров пузырей серии. Чтение/Запись String.

**Возврат:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Возвращает или задает числовой формат размеров пузырей серии. Чтение/Запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Указывает, что столбчатая, колонная или пузырьковая серия должна инвертировать цвета, если значение отрицательное. Чтение/Запись boolean.

**Возврат:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Указывает, что столбчатая, колонная или пузырьковая серия должна инвертировать цвета, если значение отрицательное. Чтение/Запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Указывает инвертировать сплошной цвет для серии. Чтобы применить настройку цвета, задайте формату серии FillType со значением FillType.Solid. Чтение/Запись [IColorFormat](../../com.aspose.slides/icolorformat).

**Возврат:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Представляет элемент легенды, связанный с этой серией (только для чтения) [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возврат:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Возвращает автоматический цвет серии на основе индекса серии и стиля диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined.

**Возвращаемое значение:**
java.awt.Color - Автоматический цвет серии java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Представляет внутренние точки. True, если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Представляет внутренние точки. True, если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Представляет отталкивающие точки. True, если отталкивающие точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Представляет отталкивающие точки. True, если отталкивающие точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Представляет маркеры среднего значения. True, если маркеры среднего значения отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Представляет маркеры среднего значения. True, если маркеры среднего значения отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Представляет маркеры среднего значения. True, если средняя линия отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Представляет маркеры среднего значения. True, если средняя линия отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Представляет метод квартилей. Применяется только к диаграммам BoxAndWhisker.

**Возвращаемое значение:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Представляет метод квартилей. Применяется только к диаграммам BoxAndWhisker.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Представляет соединительные линии. Применяется только к диаграммам Waterfall.

**Возвращаемое значение:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Представляет соединительные линии. Применяется только к диаграммам Waterfall.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Представляет расположение меток родительских категорий. Применяется только к диаграммам Treemap.

**Возвращаемое значение:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Представляет расположение меток родительских категорий. Применяется только к диаграммам Treemap.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Указывает коэффициент масштаба для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.BubbleSizeScale для чтения/записи, чтобы изменить значение.

--------------------

Это проекция свойства ParentSeriesGroup.BubbleSizeScale.

**Возвращаемое значение:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Определяет, имеет ли линейная или столбчатая диаграмма бары вверх/вниз. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.UpDownBars.HasUpDownBars для чтения/записи, чтобы изменить значение. Используйте свойство ParentSeriesGroup.UpDownBars для форматирования баров вверх/вниз. Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Возвращаемое значение:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Указывает расстояние между группами столбцов или полос в процентах от ширины столбца или полосы. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.GapWidth для чтения/записи, чтобы изменить значение. Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.GapWidth.

**Возвращаемое значение:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Возвращает или задает расстояние в процентах от ширины маркера между сериями данных в 3-D диаграмме. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.GapDepth для чтения/записи, чтобы изменить значение. Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.GapDepth.

**Возвращаемое значение:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Указывает, что каждый маркер данных в серии имеет разный цвет. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.IsColorVaried для чтения/записи, чтобы изменить значение. Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.IsColorVaried.

**Возвращаемое значение:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Определяет, есть ли линии серий для этой серии и связанных серий. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.HasSeriesLines для чтения/записи, чтобы изменить значение. Используйте свойство ParentSeriesGroup.SeriesLinesFormat для форматирования линий серий. Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.HasSeriesLines.

**Возвращаемое значение:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Указывает, насколько столбцы и полосы перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий. Это проекция соответствующего свойства в группе родительских серий, поэтому это свойство только для чтения. Чтобы изменить значение, используйте свойство ParentSeriesGroup.Overlap для чтения/записи. Только для чтения byte.

--------------------

Overlap указывает степень перекрытия или расстояния между столбцами и полосами в процентах от их ширины:
- -100% : максимальное расстояние (столбцы полностью разделены).
- 0% : столбцы расположены рядом без перекрытия и без промежутков.
- 100% : максимальное перекрытие (столбцы полностью накладываются друг на друга).
Это проекция свойства ParentSeriesGroup.Overlap.

**Возвращаемое значение:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Указывает размер второй части пирога или столбца в диаграмме «пирог-в-пироге» или «полоса-в-пироге» в процентах от размера первого пирога (может быть от 5 до 200 процентов). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.SecondPieSize для чтения/записи, чтобы изменить значение. Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.SecondPieSize.

**Возвращаемое значение:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Указывает значение, которое будет использовано для определения, какие точки данных находятся во второй части пирога или столбца в диаграмме «пирог-в-пироге» или «полоса-в-пироге». Используется совместно со свойством PieSplitBy. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.PieSplitPosition для чтения/записи, чтобы изменить значение. Только для чтения double.

--------------------

Это проекция свойства ParentSeriesGroup.PieSplitPosition.

**Возвращаемое значение:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Указывает, как определять, какие точки данных находятся во второй части пирога или столбца в диаграмме «пирог-в-пироге» или «полоса-в-пироге». Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.PieSplitBy для чтения/записи, чтобы изменить значение. Только для чтения [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Это проекция свойства ParentSeriesGroup.PieSplitBy. 2) Если значение свойства — PieSplitType.Custom, то можно задать пользовательскую информацию о разбиении с помощью свойства ParentSeriesGroup.PieSplitCustomPoints.

**Возвращаемое значение:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера зоны построения). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.DoughnutHoleSize для чтения/записи, чтобы изменить значение. Только для чтения byte.

--------------------

Это проекция свойства ParentSeriesGroup.DoughnutHoleSize.

**Возвращаемое значение:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Указывает угол первого сектора пирога или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.FirstSliceAngle для чтения/записи, чтобы изменить значение. Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.FirstSliceAngle.

**Возвращаемое значение:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Пользовательская информация о разбиении для диаграммы «пирог-в-пироге» или «полоса-в-пироге» с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во второй части пирога или столбца в такой диаграмме. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Только для чтения [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Это проекция свойства ParentSeriesGroup.PieSplitCustomPoints.

**Возвращаемое значение:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Указывает, как значения размеров пузырей отображаются на пузырчатой диаграмме. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего группового свойства. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Используйте свойство ParentSeriesGroup.BubbleSizeRepresentation с правом чтения/записи для изменения значения.

--------------------

Это проекция свойства ParentSeriesGroup.BubbleSizeRepresentation.

**Returns:**
int