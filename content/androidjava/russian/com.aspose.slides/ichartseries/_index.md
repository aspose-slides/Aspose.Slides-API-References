---
title: IChartSeries
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет серию диаграммы.
type: docs
url: /ru/com.aspose.slides/ichartseries/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Представляет серию диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getExplosion()](#getExplosion--) | Расстояние открытого сектора пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. |
| [setExplosion(int value)](#setExplosion-int-) | Расстояние открытого сектора пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. |
| [getSmooth()](#getSmooth--) | Представляет сглаживание кривой. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Представляет сглаживание кривой. |
| [getMarker()](#getMarker--) | Возвращает маркер серии. |
| [getBar3DShape()](#getBar3DShape--) | Указывает форму серии 3-D столбчатой диаграммы. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Указывает форму серии 3-D столбчатой диаграммы. |
| [getName()](#getName--) | Возвращает имя серии. |
| [getDataPoints()](#getDataPoints--) | Возвращает коллекцию точек данных этой серии. |
| [getType()](#getType--) | Возвращает тип этой серии. |
| [setType(int value)](#setType-int-) | Возвращает тип этой серии. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Возвращает родительскую группу серий. |
| [getFormat()](#getFormat--) | Возвращает формат серии. |
| [getOrder()](#getOrder--) | Возвращает порядок серии. |
| [setOrder(int value)](#setOrder-int-) | Возвращает порядок серии. |
| [getLabels()](#getLabels--) | Возвращает метки серии. |
| [getTrendLines()](#getTrendLines--) | Коллекция линий тренда серии. Только для чтения [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Представляет ErrorBars серии с направлением X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Представляет ErrorBars серии с направлением Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Указывает, отображается ли эта серия на второй оси значений. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Указывает, отображается ли эта серия на второй оси значений. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Возвращает или задает числовой формат значений серии. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Возвращает или задает числовой формат значений серии. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Возвращает или задает числовой формат значений X серии. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Возвращает или задает числовой формат значений X серии. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Возвращает или задает числовой формат значений Y серии. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Возвращает или задает числовой формат значений Y серии. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Возвращает или задает числовой формат размеров пузырей серии. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Возвращает или задает числовой формат размеров пузырей серии. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Указывает, должна ли серия столбцов, колонок или пузырей инвертировать цвета при отрицательном значении. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Указывает, должна ли серия столбцов, колонок или пузырей инвертировать цвета при отрицательном значении. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Указывает инвертированный сплошной цвет для серии. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Представляет запись легенды, связанную с этой серией. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Возвращает автоматический цвет серии, основанный на индексе серии и стиле диаграммы. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Представляет внутренние точки. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Представляет внутренние точки. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Представляет выбросные точки. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Представляет выбросные точки. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Представляет маркеры среднего. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Представляет маркеры среднего. |
| [getShowMeanLine()](#getShowMeanLine--) | Представляет маркеры среднего. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Представляет маркеры среднего. |
| [getQuartileMethod()](#getQuartileMethod--) | Представляет метод квартилей. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Представляет метод квартилей. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Представляет соединительные линии. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Представляет соединительные линии. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Представляет расположение меток родительских категорий. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Представляет расположение меток родительских категорий. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Указывает коэффициент масштаба для пузырьковой диаграммы (может быть от 0 до 300 % от размера по умолчанию). |
| [hasUpDownBars()](#hasUpDownBars--) | Определяет, имеет ли линейная или стохастическая диаграмма полосы вверх/вниз. |
| [getGapWidth()](#getGapWidth--) | Указывает расстояние между кластерами столбцов или колонок в процентах от их ширины. |
| [getGapDepth()](#getGapDepth--) | Возвращает или задает расстояние, в процентах от ширины маркера, между сериями данных в 3D-диаграмме. |
| [isColorVaried()](#isColorVaried--) | Указывает, что каждый маркер данных в серии имеет разный цвет. |
| [hasSeriesLines()](#hasSeriesLines--) | Определяет, есть ли линии серии для этой серии и родственных серий. |
| [getOverlap()](#getOverlap--) | Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100 % до 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Указывает размер второго пирога или столбца в диаграмме «пирог-в-пироге»/«столбец-в-пироге», в процентах от размера первого пирога (может быть от 5 % до 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Указывает значение, которое используется для определения, какие точки данных находятся во втором пироге или столбце. |
| [getPieSplitBy()](#getPieSplitBy--) | Указывает, как определять, какие точки данных находятся во втором пироге или столбце. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Указывает угол первого сектора пирога или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360 °). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Пользовательская информация о разбиении для диаграммы «пирог-в-пироге»/«столбец-в-пироге» с пользовательским разбиением. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Расстояние открытого сектора пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. Чтение/запись int.

**Возвращает:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Расстояние открытого сектора пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Представляет сглаживание кривой. true, если сглаживание включено для линейной или точечной диаграммы, соединённой линиями. Применяется только к линейным и точечным диаграммам, соединённым линиями. Чтение/запись boolean.

**Возвращает:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Представляет сглаживание кривой. true, если сглаживание включено для линейной или точечной диаграммы, соединённой линиями. Применяется только к линейным и точечным диаграммам, соединённым линиями. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Возвращает маркер серии. Только для чтения [IMarker](../../com.aspose.slides/imarker).

**Возвращает:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Указывает форму серии 3-D столбчатой диаграммы. Изменение значения этого свойства может автоматически изменить тип серии. Чтение/запись [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Возвращает:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Указывает форму серии 3-D столбчатой диаграммы. Изменение значения этого свойства может автоматически изменить тип серии. Чтение/запись [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Возвращает имя серии. Только для чтения [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Возвращает:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Возвращает коллекцию точек данных этой серии. Только для чтения [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Возвращает:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

Возвращает тип этой серии. Чтение/запись [ChartType](../../com.aspose.slides/charttype).

**Возвращает:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Возвращает тип этой серии. Чтение/запись [ChartType](../../com.aspose.slides/charttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Возвращает родительскую группу серий. Только для чтения [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Возвращает:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Возвращает формат серии. Только для чтения [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Возвращает порядок серии. Чтение/запись int.

**Возвращает:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Возвращает порядок серии. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Возвращает метки серии. Только для чтения [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Возвращает:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Коллекция линий тренда серии. Только для чтения [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Возвращает:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Представляет ErrorBars серии с направлением X. Только для чтения [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars с направлением X доступны для серий типов area, bar, scatter и bubble. Для остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). При использовании пользовательских значений используйте коллекцию DataPoints для указания значения (со свойством ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Возвращает:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Представляет ErrorBars серии с направлением Y. Только для чтения [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars с направлением Y доступны для серий типов area, bar, line, scatter и bubble. Для остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). При использовании пользовательских значений используйте коллекцию DataPoints для указания значения (со свойством ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Возвращает:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Указывает, отображается ли эта серия на второй оси значений. Чтение/запись boolean.

**Возвращает:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Указывает, отображается ли эта серия на второй оси значений. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Возвращает или задает числовой формат значений серии. Чтение/запись String.

**Возвращает:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Возвращает или задает числовой формат значений серии. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Возвращает или задает числовой формат значений X серии. Чтение/запись String.

**Возвращает:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Возвращает или задает числовой формат значений X серии. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Возвращает или задает числовой формат значений Y серии. Чтение/запись String.

**Возвращает:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Возвращает или задает числовой формат значений Y серии. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Возвращает или задает числовой формат размеров пузырей серии. Чтение/запись String.

**Возвращает:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Возвращает или задает числовой формат размеров пузырей серии. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Указывает, должна ли серия столбцов, колонок или пузырей инвертировать цвета при отрицательном значении. Чтение/запись boolean.

**Возвращает:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Указывает, должна ли серия столбцов, колонок или пузырей инвертировать цвета при отрицательном значении. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Указывает инвертированный сплошной цвет для серии. Чтобы применить цвет, установите FillType серии в FillType.Solid. Чтение/запись [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращает:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Представляет запись легенды, связанную с этой серией. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возвращает:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Возвращает автоматический цвет серии, основанный на индексе серии и стиле диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined.

**Возвращает:**
java.lang.Integer - Автоматический цвет серии java.lang.Integer
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Представляет внутренние точки. true, если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Представляет внутренние точки. true, если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Представляет выбросные точки. true, если выбросные точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Представляет выбросные точки. true, если выбросные точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Представляет маркеры среднего. true, если маркеры среднего отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Представляет маркеры среднего. true, если маркеры среднего отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Представляет маркеры среднего. true, если средняя линия отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Возвращает:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Представляет маркеры среднего. true, если средняя линия отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Представляет метод квартилей. Применяется только к диаграммам BoxAndWhisker.

**Возвращает:**
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

**Возвращает:**
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

**Возвращает:**
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

Указывает коэффициент масштаба для пузырьковой диаграммы (может быть от 0 до 300 % от размера по умолчанию). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы серий — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.BubbleSizeScale (чтение/запись).

--------------------

Это проекция свойства ParentSeriesGroup.BubbleSizeScale.

**Возвращает:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Определяет, имеет ли линейная или стохастическая диаграмма полосы вверх/вниз. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы серий — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.UpDownBars.HasUpDownBars (чтение/запись). Для формата полос используйте свойство ParentSeriesGroup.UpDownBars. Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Возвращает:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Указывает расстояние между кластерами столбцов или колонок в процентах от их ширины. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы серий — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.GapWidth (чтение/запись). Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.GapWidth.

**Возвращает:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Возвращает или задает расстояние, в процентах от ширины маркера, между сериями данных в 3D-диаграмме. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы серий — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.GapDepth (чтение/запись). Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.GapDepth.

**Возвращает:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Указывает, что каждый маркер данных в серии имеет разный цвет. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы серий — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.IsColorVaried (чтение/запись). Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.IsColorVaried.

**Возвращает:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Определяет, есть ли линии серии для этой серии и родственных серий. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы серий — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.HasSeriesLines (чтение/запись). Для формата линий серии используйте свойство ParentSeriesGroup.SeriesLinesFormat. Только для чтения boolean.

--------------------

Это проекция свойства ParentSeriesGroup.HasSeriesLines.

**Возвращает:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100 % до 100 %). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы. Это проекция соответствующего свойства группы, поэтому свойство только для чтения. Для изменения значения используйте свойство ParentSeriesGroup.Overlap (чтение/запись). Только для чтения byte.

--------------------

Overlap задаёт степень перекрытия или расстояния между столбцами и колонками в процентах от их ширины:
- -100 %: максимальное расстояние (столбцы полностью разделены).
- 0 %: столбцы размещаются рядом без перекрытия и без расстояния.
- 100 %: максимальное перекрытие (столбцы полностью накладываются друг на друга). Это проекция свойства ParentSeriesGroup.Overlap.

**Возвращает:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Указывает размер второго пирога или столбца в диаграмме «пирог-в-пироге»/«столбец-в-пироге», в процентах от размера первого пирога (может быть от 5 % до 200 %). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.SecondPieSize (чтение/запись). Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.SecondPieSize.

**Возвращает:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Указывает значение, которое используется для определения, какие точки данных находятся во втором пироге или столбце в диаграмме «пирог-в-пироге»/«столбец-в-пироге». Используется вместе со свойством PieSplitBy. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.PieSplitPosition (чтение/запись). Только для чтения double.

--------------------

Это проекция свойства ParentSeriesGroup.PieSplitPosition.

**Возвращает:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Указывает, как определять, какие точки данных находятся во втором пироге или столбце в диаграмме «пирог-в-пироге»/«столбец-в-пироге». Это свойство относится не только к этой серии, но и ко всем сериям родительской группы — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.PieSplitBy (чтение/запись). Только для чтения [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Это проекция свойства ParentSeriesGroup.PieSplitBy. 2) Если значение свойства равно PieSplitType.Custom, можно задать пользовательскую информацию о разбиении с помощью свойства ParentSeriesGroup.PieSplitCustomPoints.

**Возвращает:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.DoughnutHoleSize (чтение/запись). Только для чтения byte.

--------------------

Это проекция свойства ParentSeriesGroup.DoughnutHoleSize.

**Возвращает:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Указывает угол первого сектора пирога или кольцевой диаграммы в градусах (по часовой стрелке от верха, от 0 до 360 °). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.FirstSliceAngle (чтение/запись). Только для чтения int.

--------------------

Это проекция свойства ParentSeriesGroup.FirstSliceAngle.

**Возвращает:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Пользовательская информация о разбиении для диаграммы «пирог-в-пироге»/«столбец-в-пироге» с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором пироге или столбце. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы — это проекция соответствующего свойства группы. Только для чтения [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Это проекция свойства ParentSeriesGroup.PieSplitCustomPoints.

**Возвращает:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Для доступа к родительской группе используйте свойство ParentSeriesGroup. Для изменения значения используйте свойство ParentSeriesGroup.BubbleSizeRepresentation (чтение/запись).

--------------------

Это проекция свойства ParentSeriesGroup.BubbleSizeRepresentation.

**Возвращает:**
int