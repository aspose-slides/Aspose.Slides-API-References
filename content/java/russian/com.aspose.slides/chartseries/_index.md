---
title: ChartSeries
second_title: Справочник API Aspose.Slides для Java
description: Представляет серию диаграммы.
type: docs
url: /ru/com.aspose.slides/chartseries/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Представляет серию диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [getExplosion()](#getExplosion--) | Расстояние открытого сегмента круговой диаграммы от центра диаграммы выражается в процентах от диаметра круговой диаграммы. |
| [setExplosion(int value)](#setExplosion-int-) | Расстояние открытого сегмента круговой диаграммы от центра диаграммы выражается в процентах от диаметра круговой диаграммы. |
| [getSmooth()](#getSmooth--) | Представляет сглаживание кривой. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Представляет сглаживание кривой. |
| [getName()](#getName--) | Возвращает имя серии. |
| [getDataPoints()](#getDataPoints--) | Возвращает коллекцию точек данных этой серии. |
| [getType()](#getType--) | Возвращает тип этой серии. |
| [setType(int value)](#setType-int-) | Возвращает тип этой серии. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, отображается ли эта серия на вторичной оси. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Указывает, отображается ли эта серия на вторичной оси. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Возвращает формат серии. |
| [getOrder()](#getOrder--) | Возвращает порядок серии. |
| [setOrder(int value)](#setOrder-int-) | Возвращает порядок серии. |
| [getLabels()](#getLabels--) | Возвращает метки серии. |
| [getTrendLines()](#getTrendLines--) | Коллекция линий тренда серии. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Представляет ErrorBars серии с направлением X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Представляет ErrorBars серии с направлением Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Представляет элемент легенды, связанный с этой серией. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Указывает форму серии 3-D столбчатой диаграммы. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Указывает форму серии 3-D столбчатой диаграммы. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Указывает, что серия столбцов, колонок или пузырей должна инвертировать цвета, если значение отрицательное. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Указывает, что серия столбцов, колонок или пузырей должна инвертировать цвета, если значение отрицательное. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Указывает инвертировать сплошной цвет для серии. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Возвращает автоматический цвет серии на основе индекса серии и стиля диаграммы. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Представляет внутренние точки. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Представляет внутренние точки. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Представляет выбросы. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Представляет выбросы. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Представляет маркеры среднего. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Представляет маркеры среднего. |
| [getShowMeanLine()](#getShowMeanLine--) | Представляет линию среднего. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Представляет линию среднего. |
| [getQuartileMethod()](#getQuartileMethod--) | Представляет метод квартилей. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Представляет метод квартилей. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Представляет соединительные линии. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Представляет соединительные линии. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Представляет расположение меток родительской категории. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Представляет расположение меток родительской категории. |
| [hasUpDownBars()](#hasUpDownBars--) | Определяет, имеет ли линейный или биржевой график восходящие/нисходящие бары. |
| [getGapWidth()](#getGapWidth--) | Указывает расстояние между кластерами столбцов или колонок в процентах от их ширины. |
| [getGapDepth()](#getGapDepth--) | Возвращает или задает расстояние между данными серий в 3D-диаграмме в процентах от ширины маркера. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Указывает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от вершины, от 0 до 360 градусов). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10% до 90% от размера области построения). |
| [getOverlap()](#getOverlap--) | Указывает степень перекрытия столбцов и колонок на 2-D диаграммах в процентах (от -100% до 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Указывает размер второго круга или столбца в диаграмме «круг в круге» или «столбец в круге» в процентах от размера первого круга (может быть от 5% до 200%). |
| [hasSeriesLines()](#hasSeriesLines--) | Определяет, есть ли линии серий для этой и сопутствующих серий. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как значения размеров пузырей отображаются на пузырьковой диаграмме. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Указывает значение, которое используется для определения, какие точки данных находятся во втором круге или столбце на диаграмме «круг в круге» или «столбец в круге». |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определить, какие точки данных находятся во втором круге или столбце на диаграмме «круг в круге» или «столбец в круге». |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Пользовательская информация о разделении для диаграммы «круг в круге» или «столбец в круге» с пользовательским разделением. |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в серии имеет различный цвет. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает масштабный коэффициент для пузырьковой диаграммы (может быть от 0% до 300% от размера по умолчанию). |
| [getSlide()](#getSlide--) | Возвращает родительский слайд FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Расстояние открытого сегмента круговой диаграммы от её центра выражается в процентах от диаметра круга. Чтение/запись int.

**Возвращаемое значение:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Расстояние открытого сегмента круговой диаграммы от её центра выражается в процентах от диаметра круга. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Представляет сглаживание кривой. true, если сглаживание включено для линейной диаграммы или диаграммы рассеяния. Применяется только к линейным и соединённым линиями диаграммам рассеяния. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Представляет сглаживание кривой. true, если сглаживание включено для линейной диаграммы или диаграммы рассеяния. Применяется только к линейным и соединённым линиями диаграммам рассеяния. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Возвращает имя серии. Только для чтения [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Возвращаемое значение:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Возвращает коллекцию точек данных этой серии. Только для чтения [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Возвращаемое значение:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Возвращает тип этой серии. Чтение/запись [ChartType](../../com.aspose.slides/charttype).

**Возвращаемое значение:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Возвращает тип этой серии. Чтение/запись [ChartType](../../com.aspose.slides/charttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Указывает, отображается ли эта серия на вторичной оси. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Указывает, отображается ли эта серия на вторичной оси. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Только для чтения [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Возвращаемое значение:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Возвращает формат серии. Только для чтения [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Возвращает порядок серии. Чтение/запись int.

**Возвращаемое значение:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Возвращает порядок серии. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Возвращает метки серии. Только для чтения [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Возвращаемое значение:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Коллекция линий тренда серии. Только для чтения [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines доступны (не null) для рядов данных в неслоенных 2-D областных, столбчатых, колонных, линейных, биржевых, xy (рассеяния) и пузырьковых диаграммах. Линия тренда недоступна для рядов данных в любой диаграмме, где тип данных стековый или 3-D. Линии тренда также недоступны для радиальных, круговых, поверхностных или кольцевых диаграмм.

**Возвращаемое значение:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Представляет ErrorBars серии с направлением X. Только для чтения [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars с направлением X доступны для серий типов area, bar, scatter и bubble. Для всех остальных типов диаграмм это свойство возвращает null (включая 3D диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с помощью свойства ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Возвращаемое значение:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Представляет ErrorBars серии с направлением Y. Только для чтения [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars с направлением Y доступны для серий типов area, bar, line, scatter и bubble. Для всех остальных типов диаграмм это свойство возвращает null (включая 3D диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с помощью свойства ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Возвращаемое значение:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Представляет элемент легенды, связанный с этой серией. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возвращаемое значение:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Только для чтения [IMarker](../../com.aspose.slides/imarker).

**Возвращаемое значение:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Указывает форму серии 3-D столбчатой диаграммы. Изменение значения этого свойства может привести к автоматическому изменению типа серии. Чтение/запись [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Возвращаемое значение:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Указывает форму серии 3-D столбчатой диаграммы. Изменение значения этого свойства может привести к автоматическому изменению типа серии. Чтение/запись [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Указывает, что серия столбцов, колонок или пузырей должна инвертировать цвета, если значение отрицательное. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Указывает, что серия столбцов, колонок или пузырей должна инвертировать цвета, если значение отрицательное. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Read/write [ColorFormat](../../com.aspose.slides/colorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Возвращает автоматический цвет серии, основанный на индексе серии и стиле диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined.

**Возвращает:**
java.awt.Color - объект java.awt.Color.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Представляет внутренние точки. Истина, если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Представляет внутренние точки. Истина, если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Представляет выбросы. Истина, если выбросы отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Представляет выбросы. Истина, если выбросы отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Представляет маркеры среднего. Истина, если маркеры среднего отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Представляет маркеры среднего. Истина, если маркеры среднего отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Представляет линию среднего. Истина, если линия среднего отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Представляет линию среднего. Истина, если линия среднего отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Представляет метод квартиля. Применяется только к диаграммам BoxAndWhisker.

**Возвращает:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Представляет метод квартиля. Применяется только к диаграммам BoxAndWhisker.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Представляет линии соединения. Применяется только к диаграммам Waterfall.

**Возвращает:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Представляет линии соединения. Применяется только к диаграммам Waterfall.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Представляет расположение меток родительских категорий. Применяется только к диаграммам Treemap.

**Возвращает:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Представляет расположение меток родительских категорий. Применяется только к диаграммам Treemap.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Определяет, имеет ли линейная или сточная диаграмма вертикальные полосы вверх/вниз. Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.UpDownBars.HasUpDownBars с чтением/записью. Для форматирования вертикальных полос используйте свойство ParentSeriesGroup.UpDownBars. Только чтение boolean.

--------------------

Это проекция свойства ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Возвращает:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Указывает пространство между кластерами столбцов или полос, в процентах от ширины столбца или полосы. Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.GapWidth с чтением/записью. Только чтение int.

--------------------

Это проекция свойства ParentSeriesGroup.GapWidth.

**Возвращает:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Возвращает или задает расстояние, в процентах от ширины маркера, между рядами данных в 3-D диаграмме. Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.GapDepth с чтением/записью. Только чтение int.

--------------------

Это проекция свойства ParentSeriesGroup.GapDepth.

**Возвращает:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Указывает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней точки, от 0 до 360 градусов). Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.FirstSliceAngle с чтением/записью. Только чтение int.

--------------------

Это проекция свойства ParentSeriesGroup.FirstSliceAngle.

**Возвращает:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера области построения). Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.DoughnutHoleSize с чтением/записью. Только чтение byte.

--------------------

Это проекция свойства ParentSeriesGroup.DoughnutHoleSize.

**Возвращает:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Указывает, насколько столбцы и полосы перекрываются в 2-D диаграммах, в процентах (от -100 % до 100 %). Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий. Это проекция соответствующего свойства группы, поэтому свойство только чтение. Для изменения значения используйте свойство ParentSeriesGroup.Overlap с чтением/записью. Только чтение byte.

--------------------

Overlap указывает степень перекрытия или промежутка между столбцами и полосами в процентах от их ширины:
- -100 %: максимальное расстояние (полосы полностью отделены).
- 0 %: полосы размещаются рядом без перекрытия и без промежутка.
- 100 %: максимальное перекрытие (полосы полностью накладываются друг на друга). Это проекция свойства ParentSeriesGroup.Overlap.

**Возвращает:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Указывает размер второго сектора или столбца в диаграмме «pie-of-pie» или «bar-of-pie» в процентах от размера первого сектора (может быть от 5 до 200 процентов). Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.SecondPieSize с чтением/записью. Только чтение int.

--------------------

Это проекция свойства ParentSeriesGroup.SecondPieSize.

**Возвращает:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Определяет, есть ли линии серий для этой серии и связанных серий. Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.HasSeriesLines с чтением/записью. Для форматирования линий серий используйте свойство ParentSeriesGroup.SeriesLinesFormat. Только чтение boolean.

--------------------

Это проекция свойства ParentSeriesGroup.HasSeriesLines.

**Возвращает:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Указывает, как значения размеров пузырьков представлены в пузырьковой диаграмме. Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.BubbleSizeRepresentation с чтением/записью.

--------------------

Это проекция свойства ParentSeriesGroup.BubbleSizeRepresentation.

**Возвращает:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Указывает значение, которое должно использоваться для определения, какие данные находятся во втором сектора или столбце в диаграмме «pie-of-pie» или «bar-of-pie». Используется совместно со свойством PieSplitBy. Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.PieSplitPosition с чтением/записью. Только чтение double.

--------------------

Это проекция свойства ParentSeriesGroup.PieSplitPosition.

**Возвращает:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Указывает, как определять, какие данные находятся во втором сектора или столбце в диаграмме «pie-of-pie» или «bar-of-pie». Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому свойство только чтение. Для доступа к группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.PieSplitBy с чтением/записью. Только чтение [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Это проекция свойства ParentSeriesGroup.PieSplitBy. 2) Если значение свойства равно PieSplitType.Custom, то вы можете задать пользовательскую информацию о разбиении с помощью свойства ParentSeriesGroup.PieSplitCustomPoints.

**Возвращает:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Пользовательская информация о разбиении для диаграммы «pie-of-pie» или «bar-of-pie» с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором секторе или столбце диаграммы «pie-of-pie» или «bar-of-pie». Это свойство относится не только к данной серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Только чтение [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Это проекция свойства ParentSeriesGroup.PieSplitCustomPoints.

**Возвращает:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Указывает, что каждый маркер данных в серии имеет разный цвет. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Для изменения значения используйте свойство ParentSeriesGroup.IsColorVaried с доступом чтение/запись. boolean, только для чтения.

--------------------

Это проекция свойства ParentSeriesGroup.IsColorVaried.

**Возвращаемое значение:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Указывает коэффициент масштабирования для пузырчатой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Для изменения значения используйте свойство ParentSeriesGroup.BubbleSizeScale с доступом чтение/запись.

--------------------

Это проекция свойства ParentSeriesGroup.BubbleSizeScale.

**Возвращаемое значение:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд объекта FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию объекта FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)