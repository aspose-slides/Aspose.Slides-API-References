---
title: IAxis
second_title: Aspose.Slides для Android через Java API Справка
description: Инкапсулирует объект, представляющий ось диаграммы.
type: docs
url: /ru/com.aspose.slides/iaxis/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Инкапсулирует объект, представляющий ось диаграммы.
## Методы

| Method | Description |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Представляет, пересекает ли ось значений ось категорий между категориями. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Представляет, пересекает ли ось значений ось категорий между категориями. |
| [getCrossAt()](#getCrossAt--) | Представляет точку на оси, где перпендикулярная ось пересекает её. |
| [setCrossAt(float value)](#setCrossAt-float-) | Представляет точку на оси, где перпендикулярная ось пересекает её. |
| [getDisplayUnit()](#getDisplayUnit--) | Указывает масштабное значение отображаемых единиц для оси значений. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Указывает масштабное значение отображаемых единиц для оси значений. |
| [getActualMaxValue()](#getActualMaxValue--) | Указывает фактическое максимальное значение на оси. |
| [getActualMinValue()](#getActualMinValue--) | Указывает фактическое минимальное значение на оси. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Указывает фактическую основную единицу оси. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Указывает фактическую вспомогательную единицу оси. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Указывает фактический масштаб основной единицы оси. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Указывает фактический масштаб вспомогательной единицы оси. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Указывает, назначено ли автоматически максимальное значение. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Указывает, назначено ли автоматически максимальное значение. |
| [getMaxValue()](#getMaxValue--) | Представляет максимальное значение на оси значений. |
| [setMaxValue(double value)](#setMaxValue-double-) | Представляет максимальное значение на оси значений. |
| [getMinorUnit()](#getMinorUnit--) | Представляет вспомогательные единицы для оси даты или значения. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Представляет вспомогательные единицы для оси даты или значения. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Указывает, назначена ли автоматически вспомогательная единица оси. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Указывает, назначена ли автоматически вспомогательная единица оси. |
| [getMajorUnit()](#getMajorUnit--) | Представляет основные единицы для оси даты или значения. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Представляет основные единицы для оси даты или значения. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Указывает, назначена ли автоматически основная единица оси. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Указывает, назначена ли автоматически основная единица оси. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Указывает, назначено ли автоматически минимальное значение. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Указывает, назначено ли автоматически минимальное значение. |
| [getMinValue()](#getMinValue--) | Представляет минимальное значение на оси значений. |
| [setMinValue(double value)](#setMinValue-double-) | Представляет минимальное значение на оси значений. |
| [isLogarithmic()](#isLogarithmic--) | Представляет, является ли тип шкалы оси значений логарифмическим. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Представляет, является ли тип шкалы оси значений логарифмическим. |
| [getLogBase()](#getLogBase--) | Представляет логарифмическую основу. |
| [setLogBase(double value)](#setLogBase-double-) | Представляет логарифмическую основу. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Представляет, отображает ли MS PowerPoint точки данных от последней к первой. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Представляет, отображает ли MS PowerPoint точки данных от последней к первой. |
| [isVisible()](#isVisible--) | Представляет, видима ли ось. |
| [setVisible(boolean value)](#setVisible-boolean-) | Представляет, видима ли ось. |
| [getMajorTickMark()](#getMajorTickMark--) | Представляет тип основной метки деления для указанной оси. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Представляет тип основной метки деления для указанной оси. |
| [getMinorTickMark()](#getMinorTickMark--) | Представляет тип вспомогательной метки деления для указанной оси. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Представляет тип вспомогательной метки деления для указанной оси. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Представляет положение подписей делений на указанной оси. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Представляет положение подписей делений на указанной оси. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Представляет масштаб основной единицы для оси даты. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Представляет масштаб основной единицы для оси даты. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Представляет масштаб основной единицы для оси даты. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Представляет масштаб основной единицы для оси даты. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Указывает наименьшую единицу времени, отображаемую на оси даты. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Указывает наименьшую единицу времени, отображаемую на оси даты. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Представляет формат вспомогательных линий сетки на оси диаграммы. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Представляет формат основных линий сетки на оси диаграммы. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Представляет, отображаются ли вспомогательные линии сетки. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Представляет, отображаются ли основные линии сетки. |
| [getFormat()](#getFormat--) | Представляет формат оси. |
| [getTitle()](#getTitle--) | Получает название оси. |
| [getCrossType()](#getCrossType--) | Представляет тип пересечения (CrossType) на указанной оси, где другая ось её пересекает. |
| [setCrossType(int value)](#setCrossType-int-) | Представляет тип пересечения (CrossType) на указанной оси, где другая ось её пересекает. |
| [getPosition()](#getPosition--) | Представляет положение оси. |
| [setPosition(int value)](#setPosition-int-) | Представляет положение оси. |
| [hasTitle()](#hasTitle--) | Определяет, имеет ли ось видимый заголовок. |
| [setTitle(boolean value)](#setTitle-boolean-) | Определяет, имеет ли ось видимый заголовок. |
| [getNumberFormat()](#getNumberFormat--) | Представляет строку формата для подписей оси. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Представляет строку формата для подписей оси. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Указывает, связана ли форматировка с исходными данными. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Указывает, связана ли форматировка с исходными данными. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Представляет угол поворота подписей делений. Чтение/запись float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Представляет угол поворота подписей делений. Чтение/запись float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Указывает, сколько подписей делений пропустить между отображаемыми. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Указывает, сколько подписей делений пропустить между отображаемыми. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Указывает значение автоматического интервала подписей делений. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Указывает значение автоматического интервала подписей делений. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Указывает, сколько делений пропустить перед следующей рисуемой. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Указывает, сколько делений пропустить перед следующей рисуемой. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Указывает значение автоматического интервала делений. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Указывает значение автоматического интервала делений. |
| [getLabelOffset()](#getLabelOffset--) | Указывает расстояние подписей от оси. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Указывает расстояние подписей от оси. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Указывает тип категориальной оси. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Указывает тип категориальной оси. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Устанавливает свойство IAxis.CategoryAxisType автоматически на основе данных оси. |
| [getAggregationType()](#getAggregationType--) | Представляет тип агрегации категориальной оси (биннинг). |
| [setAggregationType(int value)](#setAggregationType-int-) | Представляет тип агрегации категориальной оси (биннинг). |
| [getBinWidth()](#getBinWidth--) | Указывает ширину бина, когда свойство AggregationType равно AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Указывает ширину бина, когда свойство AggregationType равно AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Указывает количество бин, когда свойство AggregationType равно AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Указывает количество бин, когда свойство AggregationType равно AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Указывает, применяется ли переполненный бин. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Указывает, применяется ли переполненный бин. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Указывает автоматическое значение переполненного бина. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Указывает автоматическое значение переполненного бина. |
| [getOverflowBin()](#getOverflowBin--) | Указывает пользовательское значение переполненного бина. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Указывает пользовательское значение переполненного бина. |
| [isUnderflowBin()](#isUnderflowBin--) | Указывает, применяется ли недостающее (underflow) значение. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Указывает, применяется ли недостающее (underflow) значение. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Указывает автоматическое значение недостающего бина. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Указывает автоматическое значение недостающего бина. |
| [getUnderflowBin()](#getUnderflowBin--) | Указывает пользовательское значение недостающего бина. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Указывает пользовательское значение недостающего бина. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Представляет, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к категориальным осям и не применяется к 3-D диаграммам. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Представляет, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к категориальным осям и не применяется к 3-D диаграммам. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Представляет точку на оси, где перпендикулярная ось пересекает её. Чтение/запись float.

**Возвращаемое значение:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Представляет точку на оси, где перпендикулярная ось пересекает её. Чтение/запись float.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Указывает масштабное значение отображаемых единиц для оси значений. Чтение/запись [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Возвращаемое значение:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Указывает масштабное значение отображаемых единиц для оси значений. Чтение/запись [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Указывает фактическое максимальное значение на оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращаемое значение:**
double
### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Указывает фактическое минимальное значение на оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращаемое значение:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Указывает фактическую основную единицу оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращаемое значение:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Указывает фактическую вспомогательную единицу оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращаемое значение:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Указывает фактический масштаб основной единицы оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращаемое значение:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Указывает фактический масштаб вспомогательной единицы оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращаемое значение:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Указывает, назначено ли автоматически максимальное значение. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Указывает, назначено ли автоматически максимальное значение. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Представляет максимальное значение на оси значений. Чтение/запись double.

**Возвращаемое значение:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Представляет максимальное значение на оси значений. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Представляет вспомогательные единицы для оси даты или значения. Чтение/запись double.

**Возвращаемое значение:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Представляет вспомогательные единицы для оси даты или значения. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Указывает, назначена ли автоматически вспомогательная единица оси. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Указывает, назначена ли автоматически вспомогательная единица оси. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Представляет основные единицы для оси даты или значения. Чтение/запись double.

**Возвращаемое значение:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Представляет основные единицы для оси даты или значения. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Указывает, назначена ли автоматически основная единица оси. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Указывает, назначена ли автоматически основная единица оси. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Указывает, назначено ли автоматически минимальное значение. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Указывает, назначено ли автоматически минимальное значение. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Представляет минимальное значение на оси значений. Чтение/запись double.

**Возвращаемое значение:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Представляет минимальное значение на оси значений. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Представляет, является ли тип шкалы оси значений логарифмическим. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Представляет, является ли тип шкалы оси значений логарифмическим. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Представляет логарифмическую основу. Значение по умолчанию — 10. Чтение/запись double.

**Возвращаемое значение:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Представляет логарифмическую основу. Значение по умолчанию — 10. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Представляет, отображает ли MS PowerPoint точки данных от последней к первой. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Представляет, отображает ли MS PowerPoint точки данных от последней к первой. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Представляет, видима ли ось. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Представляет, видима ли ось. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Представляет тип основной метки деления для указанной оси. Чтение/запись [TickMarkType](../../com.aspose.slides/tickmarktype).

**Возвращаемое значение:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Представляет тип основной метки деления для указанной оси. Чтение/запись [TickMarkType](../../com.aspose.slides/tickmarktype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Представляет тип вспомогательной метки деления для указанной оси. Чтение/запись [TickMarkType](../../com.aspose.slides/tickmarktype).

**Возвращаемое значение:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Представляет тип вспомогательной метки деления для указанной оси. Чтение/запись [TickMarkType](../../com.aspose.slides/tickmarktype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Представляет положение подписей делений на указанной оси. Чтение/запись [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Возвращаемое значение:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Представляет положение подписей делений на указанной оси. Чтение/запись [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращаемое значение:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращаемое значение:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract int getMinorUnitScale()
```

Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Указывает наименьшую единицу времени, отображаемую на оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращаемое значение:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Указывает наименьшую единицу времени, отображаемую на оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Представляет формат вспомогательных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Возвращаемое значение:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Представляет формат основных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Возвращаемое значение:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Представляет, отображаются ли вспомогательные линии сетки. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Представляет, отображаются ли основные линии сетки. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Представляет формат оси. Только для чтения [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Возвращаемое значение:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Получает название оси. Только для чтения [IChartTitle](../../com.aspose.slides/icharttitle).

**Возвращаемое значение:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Представляет тип пересечения (CrossType) на указанной оси, где другая ось её пересекает. Чтение/запись [CrossesType](../../com.aspose.slides/crossestype).

**Возвращаемое значение:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Представляет тип пересечения (CrossType) на указанной оси, где другая ось её пересекает. Чтение/запись [CrossesType](../../com.aspose.slides/crossestype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Представляет положение оси. Чтение/запись [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Возвращаемое значение:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Представляет положение оси. Чтение/запись [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Определяет, имеет ли ось видимый заголовок. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Определяет, имеет ли ось видимый заголовок. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Представляет строку формата для подписей оси. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Представляет строку формата для подписей оси. Чтение/запись String.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Указывает, связана ли форматировка с исходными данными. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Указывает, связана ли форматировка с исходными данными. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Представляет угол поворота подписей делений. Чтение/запись float.

**Возвращаемое значение:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Представляет угол поворота подписей делений. Чтение/запись float.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Указывает, сколько подписей делений пропустить между отображаемыми. Чтение/запись long.

**Возвращаемое значение:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Указывает, сколько подписей делений пропустить между отображаемыми. Чтение/запись long.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Указывает значение автоматического интервала подписей делений. Если false: используется свойство TickLabelSpacing. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Указывает значение автоматического интервала подписей делений. Если false: используется свойство TickLabelSpacing. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Указывает, сколько делений пропустить перед следующей рисуемой. Применяется к категориальной или серии оси. Чтение/запись int.

**Возвращаемое значение:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Указывает, сколько делений пропустить перед следующей рисуемой. Применяется к категориальной или серии оси. Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Указывает значение автоматического интервала делений. Если false: используется свойство TickMarksSpacing. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Указывает значение автоматического интервала делений. Если false: используется свойство TickMarksSpacing. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Указывает расстояние подписей от оси. Применяется к категориальной или датовой оси. Значение должно быть от 0 % до 1000 %. Чтение/запись int.

**Возвращаемое значение:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Указывает расстояние подписей от оси. Применяется к категориальной или датовой оси. Значение должно быть от 0 % до 1000 %. Чтение/запись int.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Указывает тип категориальной оси. Чтение/запись [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Возвращаемое значение:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Указывает тип категориальной оси. Чтение/запись [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Устанавливает свойство IAxis.CategoryAxisType автоматически на основе данных оси.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Представляет тип агрегации категориальной оси (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto.

**Возвращаемое значение:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Представляет тип агрегации категориальной оси (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Указывает ширину бина, когда свойство AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto.

**Возвращаемое значение:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Указывает ширину бина, когда свойство AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Указывает количество бин, когда свойство AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto.

**Возвращаемое значение:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Указывает количество бин, когда свойство AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Указывает, применяется ли переполненный бин. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполненного бина.

**Возвращаемое значение:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Указывает, применяется ли переполненный бин. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполненного бина.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Указывает автоматическое значение переполненного бина. Если false: используется свойство OverflowBin.

**Возвращаемое значение:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Указывает автоматическое значение переполненного бина. Если false: используется свойство OverflowBin.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Указывает пользовательское значение переполненного бина. Применяется, когда IsAutomaticOverflowBin = false и IsOverflowBin = true.

**Возвращаемое значение:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Указывает пользовательское значение переполненного бина. Применяется, когда IsAutomaticOverflowBin = false и IsOverflowBin = true.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Указывает, применяется ли недостающий (underflow) бин. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недостающего бина.

**Возвращаемое значение:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Указывает, применяется ли недостающий (underflow) бин. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недостающего бина.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Указывает автоматическое значение недостающего бина. Если false: используется свойство UnderflowBin.

**Возвращаемое значение:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Указывает автоматическое значение недостающего бина. Если false: используется свойство UnderflowBin.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Указывает пользовательское значение недостающего бина. Применяется, когда IsAutomaticUnderflowBin = false и IsUnderflowBin = true.

**Возвращаемое значение:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Указывает пользовательское значение недостающего бина. Применяется, когда IsAutomaticUnderflowBin = false и IsUnderflowBin = true.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |