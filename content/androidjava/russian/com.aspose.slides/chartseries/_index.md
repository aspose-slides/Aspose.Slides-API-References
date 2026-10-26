---
title: ChartSeries
second_title: Aspose.Slides для Android через Java API Reference
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

| Method | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [getExplosion()](#getExplosion--) | Расстояние открытого сегмента круговой диаграммы от центра круговой диаграммы выражается в процентах от диаметра круга. |
| [setExplosion(int value)](#setExplosion-int-) | Расстояние открытого сегмента круговой диаграммы от центра круговой диаграммы выражается в процентах от диаметра круга. |
| [getSmooth()](#getSmooth--) | Представляет сглаживание кривой. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Представляет сглаживание кривой. |
| [getName()](#getName--) | Возвращает имя серии. |
| [getDataPoints()](#getDataPoints--) | Возвращает коллекцию точек данных этой серии. |
| [getType()](#getType--) | Возвращает тип этой серии. |
| [setType(int value)](#setType-int-) | Возвращает тип этой серии. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, построена ли эта серия на вторичной оси. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Указывает, построена ли эта серия на вторичной оси. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Возвращает формат серии. |
| [getOrder()](#getOrder--) | Возвращает порядок серии. |
| [setOrder(int value)](#setOrder-int-) | Возвращает порядок серии. |
| [getLabels()](#getLabels--) | Возвращает метки серии. |
| [getTrendLines()](#getTrendLines--) | Коллекция линий тренда серии. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Представляет ErrorBars серии с направлением X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Представляет ErrorBars серии с направлением Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Представляет запись легенды, связанную с этой серией. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Указывает форму серии 3-D bar chart. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Указывает форму серии 3-D bar chart. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Указывает, что серия столбцов, колонок или пузыри должна инвертировать свои цвета, если значение отрицательное. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Указывает, что серия столбцов, колонок или пузыри должна инвертировать свои цвета, если значение отрицательное. |
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
| [getQuartileMethod()](#getQuartileMethod--) | Представляет метод квартиля. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Представляет метод квартиля. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Представляет соединительные линии. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Представляет соединительные линии. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Представляет расположение меток родительской категории. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Представляет расположение меток родительской категории. |
| [hasUpDownBars()](#hasUpDownBars--) | Определяет, имеет ли линейная или биржевая диаграмма бары вверх/вниз. |
| [getGapWidth()](#getGapWidth--) | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. |
| [getGapDepth()](#getGapDepth--) | Возвращает или задает расстояние, в процентах от ширины маркера, между сериями данных в 3D диаграмме. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Указывает угол первого сегмента круговой или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360 градусов). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера области построения). |
| [getOverlap()](#getOverlap--) | Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Указывает размер второго сегмента или столбца диаграммы «pie-of-pie» или «bar-of-pie», в процентах от размера первого сегмента (может быть от 5 до 200 процентов). |
| [hasSeriesLines()](#hasSeriesLines--) | Определяет, есть ли линии серии для этой серии и родственных серий. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором сегменте или столбце диаграммы «pie-of-pie» или «bar-of-pie». |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определить, какие точки данных находятся во втором сегменте или столбце диаграммы «pie-of-pie» или «bar-of-pie». |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Пользовательская информация о разделении для диаграммы «pie-of-pie» или «bar-of-pie» с пользовательским разделением. |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). |
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

Расстояние открытого сегмента круговой диаграммы от центра круговой диаграммы выражается в процентах от диаметра круга. Чтение/запись int.

**Возвращаемое значение:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Расстояние открытого сегмента круговой диаграммы от центра круговой диаграммы выражается в процентах от диаметра круга. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Представляет сглаживание кривой. True если сглаживание включено для линейной или точечной диаграммы, соединённых линиями. Применяется только к линейным и точечным диаграммам, соединённым линиями. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Представляет сглаживание кривой. True если сглаживание включено для линейной или точечной диаграммы, соединённых линиями. Применяется только к линейным и точечным диаграммам, соединённым линиями. Чтение/запись boolean.

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

Указывает, построена ли эта серия на вторичной оси. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Указывает, построена ли эта серия на вторичной оси. Чтение/запись boolean.

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

Линии тренда доступны (не null) для серий данных в неслоенных 2-D областных, столбцовых, колонновых, линейных, биржевых, xy (scatter) и пузырьковых диаграммах. Линии тренда недоступны для серий в любых типах диаграмм, которые являются слоенными или 3-D. Линии тренда также недоступны для радиальных, круговых, поверхностных или кольцевых диаграмм.

**Возвращаемое значение:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Представляет ErrorBars серии с направлением X. Только для чтения [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars с направлением X доступны для серий типов area, bar, scatter и bubble. Для любых других типов диаграмм это свойство возвращает null (включая 3D диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с свойством ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Возвращаемое значение:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Представляет ErrorBars серии с направлением Y. Только для чтения [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars с направлением Y доступны для серий типов area, bar, line, scatter и bubble. Для любых других типов диаграмм это свойство возвращает null (включая 3D диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с свойством ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Возвращаемое значение:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Представляет запись легенды, связанную с этой серией. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Указывает форму серии 3-D bar chart. Изменение значения может вызвать автоматическое изменение типа серии. Чтение/запись [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Возвращаемое значение:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Указывает форму серии 3-D bar chart. Изменение значения может вызвать автоматическое изменение типа серии. Чтение/запись [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Указывает, что серия столбцов, колонок или пузыри должна инвертировать свои цвета, если значение отрицательное. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Указывает, что серия столбцов, колонок или пузыри должна инвертировать свои цвета, если значение отрицательное. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Указывает инвертировать сплошной цвет для серии. Чтобы применить настройку цвета, установите FillType серии в FillType.Solid. Чтение/запись [ColorFormat](../../com.aspose.slides/colorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Возвращает автоматический цвет серии на основе индекса серии и стиля диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined.

**Возвращаемое значение:**
java.lang.Integer - объект java.lang.Integer.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Представляет внутренние точки. True если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Представляет внутренние точки. True если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Представляет выбросы. True если выбросы отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Представляет выбросы. True если выбросы отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Представляет маркеры среднего. True если маркеры среднего отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Представляет маркеры среднего. True если маркеры среднего отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Представляет линию среднего. True если линия среднего отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Представляет линию среднего. True если линия среднего отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Представляет метод квартиля. Применяется только к диаграммам BoxAndWhisker.

**Возвращаемое значение:**
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

Представляет соединительные линии. Применяется только к диаграммам Waterfall.

**Возвращаемое значение:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Представляет соединительные линии. Применяется только к диаграммам Waterfall.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Представляет расположение меток родительской категории. Применяется только к диаграммам Treemap.

**Возвращаемое значение:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public void

```

Представляет расположение меток родительской категории. Применяется только к диаграммам Treemap.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Определяет, имеет ли линейная или биржевая диаграмма бары вверх/вниз. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.UpDownBars.HasUpDownBars. Для формата используйте свойство ParentSeriesGroup.UpDownBars. Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Возвращаемое значение:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.GapWidth. Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.GapWidth.

**Возвращаемое значение:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Возвращает или задает расстояние, в процентах от ширины маркера, между сериями данных в 3D диаграмме. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.GapDepth. Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.GapDepth.

**Возвращаемое значение:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Указывает угол первого сегмента круговой или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360 градусов). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.FirstSliceAngle. Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.FirstSliceAngle.

**Возвращаемое значение:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера области построения). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.DoughnutHoleSize. Только для чтения byte.

--------------------

Это проекция свойства ParentSeriesGroup.DoughnutHoleSize.

**Возвращаемое значение:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий. Это проекция соответствующего свойства в группе, поэтому это свойство только для чтения. Для изменения значения используйте свойство ParentSeriesGroup.Overlap. Только для чтения byte.

--------------------

Overlap указывает степень перекрытия или расстояния между столбцами и колонками в процентах от их ширины: -100% — максимальное расставление (столбцы полностью разделены). 0% — столбцы размещены рядом без перекрытия и без расстояния. 100% — максимальное перекрытие (столбцы полностью перекрывают друг друга). Это проекция свойства ParentSeriesGroup.Overlap.

**Возвращаемое значение:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Указывает размер второго сегмента или столбца диаграммы «pie-of-pie» или «bar-of-pie», в процентах от размера первого сегмента (может быть от 5 до 200 процентов). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.SecondPieSize. Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.SecondPieSize.

**Возвращаемое значение:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Определяет, есть ли линии серии для этой серии и родственных серий. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.HasSeriesLines. Для формата используйте свойство ParentSeriesGroup.SeriesLinesFormat. Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.HasSeriesLines.

**Возвращаемое значение:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.BubbleSizeRepresentation.

--------------------

Это проекция свойства ParentSeriesGroup.BubbleSizeRepresentation.

**Возвращаемое значение:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором сегменте или столбце диаграммы «pie-of-pie» или «bar-of-pie». Используется вместе со свойством PieSplitBy. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.PieSplitPosition. Только для чтения double.

--------------------

Это проекция свойства ParentSeriesGroup.PieSplitPosition.

**Возвращаемое значение:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Указывает, как определить, какие точки данных находятся во втором сегменте или столбце диаграммы «pie-of-pie» или «bar-of-pie». Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.PieSplitBy. Только для чтения [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Это проекция свойства ParentSeriesGroup.PieSplitBy. 2) Если значение свойства — PieSplitType.Custom, можно определить пользовательскую информацию о разделении с помощью свойства ParentSeriesGroup.PieSplitCustomPoints.

**Возвращаемое значение:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Пользовательская информация о разделении для диаграммы «pie-of-pie» или «bar-of-pie» с пользовательским разделением. Содержит точки данных, которые должны быть нарисованы во втором сегменте или столбце. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Только для чтения [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Это проекция свойства ParentSeriesGroup.PieSplitCustomPoints.

**Возвращаемое значение:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Указывает, что каждый маркер данных в серии имеет разный цвет. Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.IsColorVaried. Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.IsColorVaried.

**Возвращаемое значение:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). Это свойство относится не только к этой серии, но и ко всем сериям группы родительских серий — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительских серий. Для изменения значения используйте свойство ParentSeriesGroup.BubbleSizeScale.

--------------------

Это проекция свойства ParentSeriesGroup.BubbleSizeScale.

**Возвращаемое значение:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)