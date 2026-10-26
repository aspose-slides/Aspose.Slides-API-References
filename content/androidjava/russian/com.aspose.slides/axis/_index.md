---
title: Axis
second_title: Aspose.Slides для Android через Java API Reference
description: Инкапсулирует объект, представляющий ось диаграммы.
type: docs
url: /ru/com.aspose.slides/axis/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Инкапсулирует объект, представляющий ось диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getChart()](#getChart--) | Returns the parent chart. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Represents if the value axis crosses the category axis between categories. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Represents if the value axis crosses the category axis between categories. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Specifies the type of the category axis. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Specifies the type of the category axis. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data. |
| [getCrossAt()](#getCrossAt--) | Represents the point on the axis where the perpendicular axis crosses it. |
| [setCrossAt(float value)](#setCrossAt-float-) | Represents the point on the axis where the perpendicular axis crosses it. |
| [getDisplayUnit()](#getDisplayUnit--) | Specifies the scaling value of the display units for the value axis. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Specifies the scaling value of the display units for the value axis. |
| [getActualMaxValue()](#getActualMaxValue--) | Specifies actual maximum value on the axis. |
| [getActualMinValue()](#getActualMinValue--) | Specifies actual minimum value on the axis. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Specifies actual major unit of the axis. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Specifies actual minor unit of the axis. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Specifies actual major unit scale of the axis. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Specifies actual minor unit scale of the axis. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indicates whether the max value is automatically assigned. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indicates whether the max value is automatically assigned. |
| [getMaxValue()](#getMaxValue--) | Represents the maximum value on the value axis. |
| [setMaxValue(double value)](#setMaxValue-double-) | Represents the maximum value on the value axis. |
| [getMinorUnit()](#getMinorUnit--) | Represents the minor units for the date or value axis. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Represents the minor units for the date or value axis. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indicates whether the minor unit of the axis is automatically assigned. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indicates whether the minor unit of the axis is automatically assigned. |
| [getMajorUnit()](#getMajorUnit--) | Represents the major units for the date or value axis. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Represents the major units for the date or value axis. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indicates whether the major unit of the axis is automatically assigned. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indicates whether the major unit of the axis is automatically assigned. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indicates whether the min value is automatically assigned. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indicates whether the min value is automatically assigned. |
| [getMinValue()](#getMinValue--) | Represents the minimum value on the value axis. |
| [setMinValue(double value)](#setMinValue-double-) | Represents the minimum value on the value axis. |
| [isLogarithmic()](#isLogarithmic--) | Represents if the value axis scale type is logarithmic or not. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Represents if the value axis scale type is logarithmic or not. |
| [getLogBase()](#getLogBase--) | Represents the logarithmic base. |
| [setLogBase(double value)](#setLogBase-double-) | Represents the logarithmic base. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Represents if MS PowerPoint plots data points from last to first. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Represents if MS PowerPoint plots data points from last to first. |
| [isVisible()](#isVisible--) | Represents if the axis is visible. |
| [setVisible(boolean value)](#setVisible-boolean-) | Represents if the axis is visible. |
| [getMajorTickMark()](#getMajorTickMark--) | Represents the type of major tick mark for the specified axis. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Represents the type of major tick mark for the specified axis. |
| [getMinorTickMark()](#getMinorTickMark--) | Represents the type of minor tick mark for the specified axis. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Represents the type of minor tick mark for the specified axis. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Represents the position of tick-mark labels on the specified axis. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Represents the position of tick-mark labels on the specified axis. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Represents the major unit scale for the date axis. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Represents the major unit scale for the date axis. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Represents the major unit scale for the date axis. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Represents the major unit scale for the date axis. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Specifies the smallest time unit that is represented on the date axis. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Specifies the smallest time unit that is represented on the date axis. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Represents minor gridlines format on a chart axis. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Represents major gridlines format on a chart axis. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. |
| [getFormat()](#getFormat--) | Represents format of axis. |
| [getTextFormat()](#getTextFormat--) | Represents format of text. |
| [getTitle()](#getTitle--) | Gets the axis' title. |
| [getCrossType()](#getCrossType--) | Represents the CrossType on the specified axis where the other axis crosses. |
| [setCrossType(int value)](#setCrossType-int-) | Represents the CrossType on the specified axis where the other axis crosses. |
| [getPosition()](#getPosition--) | Represents position of axis. |
| [setPosition(int value)](#setPosition-int-) | Represents position of axis. |
| [hasTitle()](#hasTitle--) | Determines whether a axis has a visible title. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determines whether a axis has a visible title. |
| [getNumberFormat()](#getNumberFormat--) | Represents the format string for the Axis Labels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Represents the format string for the Axis Labels. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indicates whether the format is linked source data. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indicates whether the format is linked source data. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Represents the rotation angle of tick labels. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Represents the rotation angle of tick labels. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Specifies how many tick labels to skip between label that is drawn. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Specifies how many tick labels to skip between label that is drawn. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Specifies automatic tick label spacing value. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Specifies automatic tick label spacing value. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Specifies how many tick marks shall be skipped before the next one shall be drawn. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Specifies how many tick marks shall be skipped before the next one shall be drawn. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Specifies automatic tick marks spacing value. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Specifies automatic tick marks spacing value. |
| [getLabelOffset()](#getLabelOffset--) | Specifies the distance of labels from the axis. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Specifies the distance of labels from the axis. |
| [getAggregationType()](#getAggregationType--) | Represents aggregation type of category axis (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Represents aggregation type of category axis (binning). |
| [getBinWidth()](#getBinWidth--) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Specifies if overflow bin applied. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Specifies if overflow bin applied. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Specifies automatic overflow bin value. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Specifies automatic overflow bin value. |
| [getOverflowBin()](#getOverflowBin--) | Specifies overflow bin custom value. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Specifies overflow bin custom value. |
| [isUnderflowBin()](#isUnderflowBin--) | Specifies if underflow bin applied. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Specifies if underflow bin applied. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Specifies automatic underflow bin value. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Specifies automatic underflow bin value. |
| [getUnderflowBin()](#getUnderflowBin--) | Specifies underflow bin custom value. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Specifies underflow bin custom value. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам. Чтение/запись boolean.

**Возвращает:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Specifies the type of the category axis. Read/write [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Возвращает:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Specifies the type of the category axis. Read/write [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Sets IAxis.CategoryAxisType property with a value that is automatically determined based on axis data.
### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Represents the point on the axis where the perpendicular axis crosses it. Read/write float.

**Возвращает:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Represents the point on the axis where the perpendicular axis crosses it. Read/write float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Specifies the scaling value of the display units for the value axis. Read/write [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Возвращает:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Specifies the scaling value of the display units for the value axis. Read/write [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Specifies actual maximum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Возвращает:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Specifies actual minimum value on the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Возвращает:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Specifies actual major unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Возвращает:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Specifies actual minor unit of the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Возвращает:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Specifies actual major unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Возвращает:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Specifies actual minor unit scale of the axis. Call method IChart.ValidateChartLayout() previously to get actual value.

**Возвращает:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Indicates whether the max value is automatically assigned. Read/write boolean.

**Возвращает:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Indicates whether the max value is automatically assigned. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Represents the maximum value on the value axis. Read/write double.

**Возвращает:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Represents the maximum value on the value axis. Read/write double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Represents the minor units for the date or value axis. Read/write double.

**Возвращает:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Represents the minor units for the date or value axis. Read/write double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean.

**Возвращает:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Indicates whether the minor unit of the axis is automatically assigned. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Represents the major units for the date or value axis. Read/write double.

**Возвращает:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Represents the major units for the date or value axis. Read/write double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Indicates whether the major unit of the axis is automatically assigned. Read/write boolean.

**Возвращает:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Indicates whether the major unit of the axis is automatically assigned. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Indicates whether the min value is automatically assigned. Read/write boolean.

**Возвращает:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Indicates whether the min value is automatically assigned. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Represents the minimum value on the value axis. Read/write double.

**Возвращает:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Represents the minimum value on the value axis. Read/write double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Represents if the value axis scale type is logarithmic or not. Read/write boolean.

**Возвращает:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Represents if the value axis scale type is logarithmic or not. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Represents the logarithmic base. Default value is 10. Read/write double.

**Возвращает:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Represents the logarithmic base. Default value is 10. Read/write double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Represents if MS PowerPoint plots data points from last to first. Read/write boolean.

**Возвращает:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Represents if MS PowerPoint plots data points from last to first. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Represents if the axis is visible. Read/write boolean.

**Возвращает:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Represents if the axis is visible. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Represents the type of major tick mark for the specified axis. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Возвращает:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Represents the type of major tick mark for the specified axis. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Represents the type of minor tick mark for the specified axis. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Возвращает:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Represents the type of minor tick mark for the specified axis. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Represents the position of tick-mark labels on the specified axis. Read/write [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Возвращает:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Represents the position of tick-mark labels on the specified axis. Read/write [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Represents the major unit scale for the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращает:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Represents the major unit scale for the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Represents the major unit scale for the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращает:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Represents the major unit scale for the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Specifies the smallest time unit that is represented on the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращает:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Specifies the smallest time unit that is represented on the date axis. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Represents minor gridlines format on a chart axis. Read-only [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Возвращает:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Represents major gridlines format on a chart axis. Read-only [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Возвращает:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean.

**Возвращает:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Read-only boolean.

**Возвращает:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Represents format of axis. Read-only [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Возвращает:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Represents format of text. Read-only [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возвращает:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Gets the axis' title. Read-only [IChartTitle](../../com.aspose.slides/icharttitle).

**Возвращает:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Represents the CrossType on the specified axis where the other axis crosses. Read/write [CrossesType](../../com.aspose.slides/crossestype).

**Возвращает:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Represents the CrossType on the specified axis where the other axis crosses. Read/write [CrossesType](../../com.aspose.slides/crossestype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Represents position of axis. Read/write [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Возвращает:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Represents position of axis. Read/write [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Determines whether a axis has a visible title. Read/write boolean.

**Возвращает:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Determines whether a axis has a visible title. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Represents the format string for the Axis Labels. Read/write String.

**Возвращает:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Represents the format string for the Axis Labels. Read/write String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Indicates whether the format is linked source data. Read/write boolean.

**Возвращает:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Indicates whether the format is linked source data. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Represents the rotation angle of tick labels. Read/write float.

**Возвращает:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Represents the rotation angle of tick labels. Read/write float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |
### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long.

**Возвращает:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Read/write long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean.

**Возвращает:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int.

**Возвращает:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Read/write int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean.

**Возвращает:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int.

**Возвращает:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Read/write int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only.

**Возвращает:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Represents aggregation type of category axis (binning). Applied to category. Used with Histogram or HistogramPareto series only.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Возвращает:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Specifies bin width when AggregationType property value setted to AxisAggregationType.ByBinWidth. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Возвращает:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Specifies number of bins when AggregationType property value setted to AxisAggregationType.ByNumberOfBins. Applied to category axes. Used with Histogram or HistogramPareto series only.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value.

**Возвращает:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Specifies if overflow bin applied. Use IsAutomaticOverflowBin and OverflowBin to adjust overflow bin value.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Specifies automatic overflow bin value. If false: use OverflowBin property.

**Возвращает:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Specifies automatic overflow bin value. If false: use OverflowBin property.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true.

**Возвращает:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Specifies overflow bin custom value. Applied when IsAutomaticOverflowBin property setted to false and IsOverflowBin property equals true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value.

**Возвращает:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Specifies if underflow bin applied. Use IsAutomaticUnderflowBin and UnderflowBin to adjust underflow bin value.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Specifies automatic underflow bin value. If false: use UnderflowBin property.

**Возвращает:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Specifies automatic underflow bin value. If false: use UnderflowBin property.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true.

**Возвращает:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Specifies underflow bin custom value. Applied when IsAutomaticUnderflowBin property setted to false and IsUnderflowBin property equals true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
[IPresentation](../../com.aspose.slides/ipresentation)