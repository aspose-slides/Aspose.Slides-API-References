---
title: Axis
second_title: Справочник API Aspose.Slides для Java
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
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Представляет, пересекает ли ось значений ось категорий между категориями. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Представляет, пересекает ли ось значений ось категорий между категориями. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Указывает тип оси категорий. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Указывает тип оси категорий. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Устанавливает свойство IAxis.CategoryAxisType значением, автоматически определяемым на основе данных оси. |
| [getCrossAt()](#getCrossAt--) | Представляет точку на оси, где перпендикулярная ось её пересекает. |
| [setCrossAt(float value)](#setCrossAt-float-) | Представляет точку на оси, где перпендикулярная ось её пересекает. |
| [getDisplayUnit()](#getDisplayUnit--) | Указывает масштабное значение отображаемых единиц для оси значений. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Указывает масштабное значение отображаемых единиц для оси значений. |
| [getActualMaxValue()](#getActualMaxValue--) | Указывает фактическое максимальное значение на оси. |
| [getActualMinValue()](#getActualMinValue--) | Указывает фактическое минимальное значение на оси. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Указывает фактическую основную единицу оси. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Указывает фактическую вспомогательную единицу оси. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Указывает фактический масштаб основной единицы оси. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Указывает фактический масштаб вспомогательной единицы оси. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Указывает, автоматически ли назначается максимальное значение. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Указывает, автоматически ли назначается максимальное значение. |
| [getMaxValue()](#getMaxValue--) | Представляет максимальное значение на оси значений. |
| [setMaxValue(double value)](#setMaxValue-double-) | Представляет максимальное значение на оси значений. |
| [getMinorUnit()](#getMinorUnit--) | Представляет вспомогательные единицы для оси даты или значения. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Представляет вспомогательные единицы для оси даты или значения. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Указывает, автоматически ли назначается вспомогательная единица оси. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Указывает, автоматически ли назначается вспомогательная единица оси. |
| [getMajorUnit()](#getMajorUnit--) | Представляет основные единицы для оси даты или значения. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Представляет основные единицы для оси даты или значения. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Указывает, автоматически ли назначается основная единица оси. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Указывает, автоматически ли назначается основная единица оси. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Указывает, автоматически ли назначается минимальное значение. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Указывает, автоматически ли назначается минимальное значение. |
| [getMinValue()](#getMinValue--) | Представляет минимальное значение на оси значений. |
| [setMinValue(double value)](#setMinValue-double-) | Представляет минимальное значение на оси значений. |
| [isLogarithmic()](#isLogarithmic--) | Представляет, является ли тип шкалы оси логарифмическим. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Представляет, является ли тип шкалы оси логарифмическим. |
| [getLogBase()](#getLogBase--) | Представляет логарифмическую основу. |
| [setLogBase(double value)](#setLogBase-double-) | Представляет логарифмическую основу. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Представляет, отображает ли MS PowerPoint точки данных от последней к первой. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Представляет, отображает ли MS PowerPoint точки данных от последней к первой. |
| [isVisible()](#isVisible--) | Представляет, видима ли ось. |
| [setVisible(boolean value)](#setVisible-boolean-) | Представляет, видима ли ось. |
| [getMajorTickMark()](#getMajorTickMark--) | Представляет тип основной отметки шкалы для указанной оси. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Представляет тип основной отметки шкалы для указанной оси. |
| [getMinorTickMark()](#getMinorTickMark--) | Представляет тип вспомогательной отметки шкалы для указанной оси. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Представляет тип вспомогательной отметки шкалы для указанной оси. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Представляет расположение подписей отметок на указанной оси. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Представляет расположение подписей отметок на указанной оси. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Представляет масштаб основной единицы для оси даты. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Представляет масштаб основной единицы для оси даты. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Представляет масштаб основной единицы для оси даты. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Представляет масштаб основной единицы для оси даты. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Указывает наименьшую временную единицу, отображаемую на оси даты. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Указывает наименьшую временную единицу, отображаемую на оси даты. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Представляет формат вспомогательных линий сетки на оси диаграммы. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Представляет формат основных линий сетки на оси диаграммы. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Чтобы скрыть вспомогательную линию сетки, задайте MinorGridLinesFormat.Line.FillFormat.FillType = FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Чтобы скрыть основную линию сетки, задайте MajorGridLinesFormat.Line.FillFormat.FillType = FillType.NoFill. |
| [getFormat()](#getFormat--) | Представляет формат оси. |
| [getTextFormat()](#getTextFormat--) | Представляет формат текста. |
| [getTitle()](#getTitle--) | Получает заголовок оси. |
| [getCrossType()](#getCrossType--) | Представляет тип пересечения (CrossType) на указанной оси, где пересекает другая ось. |
| [setCrossType(int value)](#setCrossType-int-) | Представляет тип пересечения (CrossType) на указанной оси, где пересекает другая ось. |
| [getPosition()](#getPosition--) | Представляет положение оси. |
| [setPosition(int value)](#setPosition-int-) | Представляет положение оси. |
| [hasTitle()](#hasTitle--) | Определяет, имеет ли ось видимый заголовок. |
| [setTitle(boolean value)](#setTitle-boolean-) | Определяет, имеет ли ось видимый заголовок. |
| [getNumberFormat()](#getNumberFormat--) | Представляет строку формата для подписей оси. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Представляет строку формата для подписей оси. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Указывает, привязан ли формат к исходным данным. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Указывает, привязан ли формат к исходным данным. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Представляет угол поворота подписей отметок. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Представляет угол поворота подписей отметок. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Указывает, сколько подписей отметок пропускать между отрисованными. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Указывает, сколько подписей отметок пропускать между отрисованными. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Указывает автоматическое значение интервала подписи отметок. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Указывает автоматическое значение интервала подписи отметок. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Указывает, сколько отметок следует пропустить перед следующей. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Указывает, сколько отметок следует пропустить перед следующей. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Указывает автоматическое значение интервала отметок. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Указывает автоматическое значение интервала отметок. |
| [getLabelOffset()](#getLabelOffset--) | Указывает расстояние подписей от оси. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Указывает расстояние подписей от оси. |
| [getAggregationType()](#getAggregationType--) | Представляет тип агрегации оси категорий (биннинг). |
| [setAggregationType(int value)](#setAggregationType-int-) | Представляет тип агрегации оси категорий (биннинг). |
| [getBinWidth()](#getBinWidth--) | Указывает ширину бина, когда свойство AggregationType установлено в AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Указывает ширину бина, когда свойство AggregationType установлено в AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Указывает количество бин, когда свойство AggregationType установлено в AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Указывает количество бин, когда свойство AggregationType установлено в AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Указывает, применяется ли бин переполнения. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Указывает, применяется ли бин переполнения. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Указывает автоматическое значение бина переполнения. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Указывает автоматическое значение бина переполнения. |
| [getOverflowBin()](#getOverflowBin--) | Указывает пользовательское значение бина переполнения. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Указывает пользовательское значение бина переполнения. |
| [isUnderflowBin()](#isUnderflowBin--) | Указывает, применяется ли бин недополнения. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Указывает, применяется ли бин недополнения. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Указывает автоматическое значение бина недополнения. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Указывает автоматическое значение бина недополнения. |
| [getUnderflowBin()](#getUnderflowBin--) | Указывает пользовательское значение бина недополнения. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Указывает пользовательское значение бина недополнения. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию FillFormat. |

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

Представляет, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам. Чтение/запись boolean.

**Возвращает:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Представляет, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам. Чтение/запись boolean.

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Указывает тип оси категорий. Чтение/запись [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Возвращает:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Указывает тип оси категорий. Чтение/запись [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Устанавливает свойство IAxis.CategoryAxisType значением, автоматически определяемым на основе данных оси.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Представляет точку на оси, где перпендикулярная ось её пересекает. Чтение/запись float.

**Возвращает:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Представляет точку на оси, где перпендикулярная ось её пересекает. Чтение/запись float.

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Указывает масштабное значение отображаемых единиц для оси значений. Чтение/запись [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Возвращает:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Указывает масштабное значение отображаемых единиц для оси значений. Чтение/запись [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Указывает фактическое максимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращает:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Указывает фактическое минимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращает:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Указывает фактическую основную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращает:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Указывает фактическую вспомогательную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращает:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Указывает фактический масштаб основной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращает:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Указывает фактический масштаб вспомогательной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout() для получения фактического значения.

**Возвращает:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Указывает, автоматически ли назначается максимальное значение. Чтение/запись boolean.

**Возвращает:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Указывает, автоматически ли назначается максимальное значение. Чтение/запись boolean.

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Представляет максимальное значение на оси значений. Чтение/запись double.

**Возвращает:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Представляет максимальное значение на оси значений. Чтение/запись double.

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Представляет вспомогательные единицы для оси даты или значения. Чтение/запись double.

**Возвращает:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Представляет вспомогательные единицы для оси даты или значения. Чтение/запись double.

**Параметры:**  
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Указывает, автоматически ли назначается мелкая единица оси. Чтение/запись, boolean.

**Возвращает:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Указывает, автоматически ли назначается мелкая единица оси. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Представляет основные единицы для оси даты или значения. Чтение/запись, double.

**Возвращает:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Представляет основные единицы для оси даты или значения. Чтение/запись, double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Указывает, автоматически ли назначается основная единица оси. Чтение/запись, boolean.

**Возвращает:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Указывает, автоматически ли назначается основная единица оси. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Указывает, автоматически ли назначается минимальное значение. Чтение/запись, boolean.

**Возвращает:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Указывает, автоматически ли назначается минимальное значение. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Представляет минимальное значение на оси значений. Чтение/запись, double.

**Возвращает:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Представляет минимальное значение на оси значений. Чтение/запись, double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Представляет, является ли тип шкалы оси значений логарифмическим. Чтение/запись, boolean.

**Возвращает:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Представляет, является ли тип шкалы оси значений логарифмическим. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Представляет логарифмическую основу. Значение по умолчанию – 10. Чтение/запись, double.

**Возвращает:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Представляет логарифмическую основу. Значение по умолчанию – 10. Чтение/запись, double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Представляет, отрисовывает ли MS PowerPoint точки данных от последней к первой. Чтение/запись, boolean.

**Возвращает:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Представляет, отрисовывает ли MS PowerPoint точки данных от последней к первой. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Представляет, видима ли ось. Чтение/запись, boolean.

**Возвращает:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Представляет, видима ли ось. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Представляет тип основной метки деления для указанной оси. Чтение/запись [TickMarkType](../../com.aspose.slides/tickmarktype).

**Возвращает:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Представляет тип основной метки деления для указанной оси. Чтение/запись [TickMarkType](../../com.aspose.slides/tickmarktype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Представляет тип вспомогательной метки деления для указанной оси. Чтение/запись [TickMarkType](../../com.aspose.slides/tickmarktype).

**Возвращает:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Представляет тип вспомогательной метки деления для указанной оси. Чтение/запись [TickMarkType](../../com.aspose.slides/tickmarktype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Представляет позицию меток деления на указанной оси. Чтение/запись [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Возвращает:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Представляет позицию меток деления на указанной оси. Чтение/запись [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращает:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращает:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Указывает наименьшую единицу времени, представленную на оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращает:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Указывает наименьшую единицу времени, представленную на оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Представляет формат вспомогательных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Возвращает:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Представляет формат основных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Возвращает:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


Чтобы скрыть вспомогательную линию сетки, установите MinorGridLinesFormat.Line.FillFormat.FillType в FillType.NoFill. Только для чтения, boolean.

**Возвращает:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


Чтобы скрыть основную линию сетки, установите MajorGridLinesFormat.Line.FillFormat.FillType в FillType.NoFill. Только для чтения, boolean.

**Возвращает:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Представляет формат оси. Только для чтения [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Возвращает:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Представляет формат текста. Только для чтения [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возвращает:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Получает заголовок оси. Только для чтения [IChartTitle](../../com.aspose.slides/icharttitle).

**Возвращает:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Представляет тип пересечения на указанной оси, где другая ось пересекает её. Чтение/запись [CrossesType](../../com.aspose.slides/crossestype).

**Возвращает:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Представляет тип пересечения на указанной оси, где другая ось пересекает её. Чтение/запись [CrossesType](../../com.aspose.slides/crossestype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Представляет позицию оси. Чтение/запись [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Возвращает:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Представляет позицию оси. Чтение/запись [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Определяет, имеет ли ось видимый заголовок. Чтение/запись, boolean.

**Возвращает:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Определяет, имеет ли ось видимый заголовок. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Представляет строку формата для меток оси. Чтение/запись String.

**Возвращает:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Представляет строку формата для меток оси. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Указывает, связан ли формат с исходными данными. Чтение/запись, boolean.

**Возвращает:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Указывает, связан ли формат с исходными данными. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Представляет угол поворота меток деления. Чтение/запись float.

**Возвращает:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Представляет угол поворота меток деления. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Указывает, сколько меток деления пропускать между выводимыми метками. Применяется к оси категорий или серии. Чтение/запись long.

**Возвращает:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Указывает, сколько меток деления пропускать между выводимыми метками. Применяется к оси категорий или серии. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Указывает автоматическое значение интервала меток деления. Если false: используется свойство TickLabelSpacing. Чтение/запись, boolean.

**Возвращает:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Указывает автоматическое значение интервала меток деления. Если false: используется свойство TickLabelSpacing. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Указывает, сколько делений пропускать перед тем, как отрисовать следующее. Применяется к оси категорий или серии. Чтение/запись int.

**Возвращает:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Указывает, сколько делений пропускать перед тем, как отрисовать следующее. Применяется к оси категорий или серии. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Указывает автоматическое значение интервала делений. Если false: используется свойство TickMarksSpacing. Чтение/запись, boolean.

**Возвращает:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Указывает автоматическое значение интервала делений. Если false: используется свойство TickMarksSpacing. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Указывает расстояние меток от оси. Применяется к оси категорий или даты. Значение должно быть от 0 % до 1000 %. Чтение/запись int.

**Возвращает:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Указывает расстояние меток от оси. Применяется к оси категорий или даты. Значение должно быть от 0 % до 1000 %. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Представляет тип агрегации оси категорий (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto.

**Возвращаемое значение:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Представляет тип агрегации оси категорий (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Указывает ширину бина, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto.

**Возвращаемое значение:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Указывает ширину бина, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Указывает количество бин, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto.

**Возвращаемое значение:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Указывает количество бин, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Указывает, применяется ли бин переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения бина переполнения.

**Возвращаемое значение:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Указывает, применяется ли бин переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения бина переполнения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Указывает значение автоматического бина переполнения. Если false: используйте свойство OverflowBin.

**Возвращаемое значение:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Указывает значение автоматического бина переполнения. Если false: используйте свойство OverflowBin.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Указывает пользовательское значение бина переполнения. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true.

**Возвращаемое значение:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Указывает пользовательское значение бина переполнения. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Указывает, применяется ли бин недополнения. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения бина недополнения.

**Возвращаемое значение:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Указывает, применяется ли бин недополнения. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения бина недополнения.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Указывает значение автоматического бина недополнения. Если false: используйте свойство UnderflowBin.

**Возвращаемое значение:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Указывает значение автоматического бина недополнения. Если false: используйте свойство UnderflowBin.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Указывает пользовательское значение бина недополнения. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true.

**Возвращаемое значение:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Указывает пользовательское значение бина недополнения. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

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