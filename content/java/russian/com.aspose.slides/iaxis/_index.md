---
title: IAxis
second_title: Справочник API Aspose.Slides для Java
description: Инкапсулирует объект, представляющий ось диаграммы.
type: docs
url: /ru/com.aspose.slides/iaxis/
---
**Все реализованные интерфейсы:**
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
| [getCrossAt()](#getCrossAt--) | Представляет точку на оси, где перпендикулярная ось её пересекает. |
| [setCrossAt(float value)](#setCrossAt-float-) | Представляет точку на оси, где перпендикулярная ось её пересекает. |
| [getDisplayUnit()](#getDisplayUnit--) | Указывает значение масштабирования единиц отображения для оси значений. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Указывает значение масштабирования единиц отображения для оси значений. |
| [getActualMaxValue()](#getActualMaxValue--) | Указывает фактическое максимальное значение на оси. |
| [getActualMinValue()](#getActualMinValue--) | Указывает фактическое минимальное значение на оси. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Указывает фактическую основную единицу оси. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Указывает фактическую вспомогательную единицу оси. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Указывает фактический масштаб основной единицы оси. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Указывает фактический масштаб вспомогательной единицы оси. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Указывает, назначено ли максимальное значение автоматически. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Указывает, назначено ли максимальное значение автоматически. |
| [getMaxValue()](#getMaxValue--) | Представляет максимальное значение на оси значений. |
| [setMaxValue(double value)](#setMaxValue-double-) | Представляет максимальное значение на оси значений. |
| [getMinorUnit()](#getMinorUnit--) | Представляет вспомогательные единицы для оси даты или значений. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Представляет вспомогательные единицы для оси даты или значений. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Указывает, назначена ли вспомогательная единица оси автоматически. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Указывает, назначена ли вспомогательная единица оси автоматически. |
| [getMajorUnit()](#getMajorUnit--) | Представляет основные единицы для оси даты или значений. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Представляет основные единицы для оси даты или значений. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Указывает, назначена ли основная единица оси автоматически. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Указывает, назначена ли основная единица оси автоматически. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Указывает, назначено ли минимальное значение автоматически. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Указывает, назначено ли минимальное значение автоматически. |
| [getMinValue()](#getMinValue--) | Представляет минимальное значение на оси значений. |
| [setMinValue(double value)](#setMinValue-double-) | Представляет минимальное значение на оси значений. |
| [isLogarithmic()](#isLogarithmic--) | Представляет, является ли тип масштабирования оси значений логарифмическим. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Представляет, является ли тип масштабирования оси значений логарифмическим. |
| [getLogBase()](#getLogBase--) | Представляет основание логарифма. |
| [setLogBase(double value)](#setLogBase-double-) | Представляет основание логарифма. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Представляет, отображает ли MS PowerPoint точки данных от последней к первой. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Представляет, отображает ли MS PowerPoint точки данных от последней к первой. |
| [isVisible()](#isVisible--) | Представляет, видна ли ось. |
| [setVisible(boolean value)](#setVisible-boolean-) | Представляет, видна ли ось. |
| [getMajorTickMark()](#getMajorTickMark--) | Представляет тип основной метки деления для указанной оси. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Представляет тип основной метки деления для указанной оси. |
| [getMinorTickMark()](#getMinorTickMark--) | Представляет тип вспомогательной метки деления для указанной оси. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Представляет тип вспомогательной метки деления для указанной оси. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Представляет положение подписей меток деления на указанной оси. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Представляет положение подписей меток деления на указанной оси. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Представляет масштаб основной единицы для оси даты. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Представляет масштаб основной единицы для оси даты. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Представляет масштаб основной единицы для оси даты. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Представляет масштаб основной единицы для оси даты. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Указывает наименьшую единицу времени, представленную на оси даты. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Указывает наименьшую единицу времени, представленную на оси даты. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Представляет формат вспомогательных линий сетки на оси диаграммы. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Представляет формат основных линий сетки на оси диаграммы. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Представляет, отображаются ли вспомогательные линии сетки. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Представляет, отображаются ли основные линии сетки. |
| [getFormat()](#getFormat--) | Представляет формат оси. |
| [getTitle()](#getTitle--) | Получает заголовок оси. |
| [getCrossType()](#getCrossType--) | Представляет тип пересечения (CrossType) на указанной оси, где она пересекает другую ось. |
| [setCrossType(int value)](#setCrossType-int-) | Представляет тип пересечения (CrossType) на указанной оси, где она пересекает другую ось. |
| [getPosition()](#getPosition--) | Представляет положение оси. |
| [setPosition(int value)](#setPosition-int-) | Представляет положение оси. |
| [hasTitle()](#hasTitle--) | Определяет, имеет ли ось видимый заголовок. |
| [setTitle(boolean value)](#setTitle-boolean-) | Определяет, имеет ли ось видимый заголовок. |
| [getNumberFormat()](#getNumberFormat--) | Представляет строку формата для меток оси. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Представляет строку формата для меток оси. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Указывает, привязан ли формат к исходным данным. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Указывает, привязан ли формат к исходным данным. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Представляет угол поворота меток деления Чтение/запись float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Представляет угол поворота меток деления Чтение/запись float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Указывает, сколько меток деления пропускать между отрисовываемыми метками. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Указывает, сколько меток деления пропускать между отрисовываемыми метками. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Указывает значение автоматического интервала между метками деления. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Указывает значение автоматического интервала между метками деления. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Указывает, сколько делений пропускать перед отрисовкой следующего. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Указывает, сколько делений пропускать перед отрисовкой следующего. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Указывает значение автоматического интервала между делениями. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Указывает значение автоматического интервала между делениями. |
| [getLabelOffset()](#getLabelOffset--) | Указывает расстояние меток от оси. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Указывает расстояние меток от оси. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Указывает тип оси категорий. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Указывает тип оси категорий. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Устанавливает свойство IAxis.CategoryAxisType значением, автоматически определяемым на основе данных оси. |
| [getAggregationType()](#getAggregationType--) | Представляет тип агрегации оси категорий (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Представляет тип агрегации оси категорий (binning). |
| [getBinWidth()](#getBinWidth--) | Указывает ширину бина, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Указывает ширину бина, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Указывает количество бинов, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Указывает количество бинов, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Указывает, применяется ли переполнительный бин. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Указывает, применяется ли переполнительный бин. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Указывает автоматическое значение переполнительного бина. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Указывает автоматическое значение переполнительного бина. |
| [getOverflowBin()](#getOverflowBin--) | Указывает пользовательское значение переполнительного бина. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Указывает пользовательское значение переполнительного бина. |
| [isUnderflowBin()](#isUnderflowBin--) | Указывает, применяется ли бин недоонижения. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Указывает, применяется ли бин недоонижения. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Указывает автоматическое значение бина недоонижения. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Указывает автоматическое значение бина недоонижения. |
| [getUnderflowBin()](#getUnderflowBin--) | Указывает пользовательское значение бина недоонижения. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Указывает пользовательское значение бина недоонижения. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Представляет, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам. Чтение/запись boolean.

**Возвращает:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Представляет, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к 3-D диаграммам. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Представляет точку на оси, где перпендикулярная ось её пересекает. Чтение/запись float.

**Возвращает:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Представляет точку на оси, где перпендикулярная ось её пересекает. Чтение/запись float.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Указывает значение масштабирования единиц отображения для оси значений. Чтение/запись [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Возвращает:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Указывает значение масштабирования единиц отображения для оси значений. Чтение/запись [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Указывает фактическое максимальное значение на оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение.

**Возвращает:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Указывает фактическое минимальное значение на оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение.

**Возвращает:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Указывает фактическую основную единицу оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение.

**Возвращает:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Указывает фактическую вспомогательную единицу оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение.

**Возвращает:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Указывает фактический масштаб основной единицы оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение.

**Возвращает:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Указывает фактический масштаб вспомогательной единицы оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение.

**Возвращает:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Указывает, назначено ли максимальное значение автоматически. Чтение/запись boolean.

**Возвращает:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Указывает, назначено ли максимальное значение автоматически. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Представляет максимальное значение на оси значений. Чтение/запись double.

**Возвращает:**
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

Представляет вспомогательные единицы для оси даты или значений. Чтение/запись double.

**Возвращает:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Представляет вспомогательные единицы для оси даты или значений. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Указывает, назначена ли вспомогательная единица оси автоматически. Чтение/запись boolean.

**Возвращает:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Указывает, назначена ли вспомогательная единица оси автоматически. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Представляет основные единицы для оси даты или значений. Чтение/запись double.

**Возвращает:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Представляет основные единицы для оси даты или значений. Чтение/запись double.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Указывает, назначена ли основная единица оси автоматически. Чтение/запись boolean.

**Возвращает:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Указывает, автоматически ли назначается основной делитель оси. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Указывает, автоматически ли назначается минимальное значение. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Указывает, автоматически ли назначается минимальное значение. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Указывает, является ли тип шкалы оси значений логарифмическим. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Указывает, является ли тип шкалы оси значений логарифмическим. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Указывает, строит ли MS PowerPoint точки данных от последней к первой. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Указывает, строит ли MS PowerPoint точки данных от последней к первой. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Указывает, видна ли ось. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Указывает, видна ли ось. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Представляет положение подписей меток деления на указанной оси. Чтение/запись [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Возвращаемое значение:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Представляет положение подписей меток деления на указанной оси. Чтение/запись [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Параметры:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
public abstract void setMinorUnitScale(int value)
```

Представляет масштаб основной единицы для оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Указывает наименьшую единицу времени, представляемую на оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Возвращаемое значение:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Указывает наименьшую единицу времени, представляемую на оси даты. Чтение/запись [TimeUnitType](../../com.aspose.slides/timeunittype).

**Параметры:**
| Параметр | Тип | Описание |
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
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Представляет формат основных линий сетки на оси диаграммы. Только для чтения [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Возвращаемое значение:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Указывает, отображаются ли вспомогательные линии сетки. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Указывает, отображаются ли основные линии сетки. Только для чтения boolean.

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

Получает заголовок оси. Только для чтения [IChartTitle](../../com.aspose.slides/icharttitle).

**Возвращаемое значение:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Представляет тип пересечения (CrossType) на указанной оси, где пересекается другая ось. Чтение/запись [CrossesType](../../com.aspose.slides/crossestype).

**Возвращаемое значение:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Представляет тип пересечения (CrossType) на указанной оси, где пересекается другая ось. Чтение/запись [CrossesType](../../com.aspose.slides/crossestype).

**Параметры:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Указывает, связан ли формат с исходными данными. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Указывает, связан ли формат с исходными данными. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Указывает, сколько подписей делений пропустить между отрисованными подписями. Чтение/запись long.

**Возвращаемое значение:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Указывает, сколько подписей делений пропустить между отрисованными подписями. Чтение/запись long.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Указывает автоматическое значение интервала подписей делений. Если false: использовать свойство TickLabelSpacing. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Указывает автоматическое значение интервала подписей делений. Если false: использовать свойство TickLabelSpacing. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Указывает, сколько меток деления следует пропустить перед следующей. Применяется к оси категорий или серии. Чтение/запись int.

**Возвращаемое значение:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Указывает, сколько меток деления следует пропустить перед следующей. Применяется к оси категорий или серии. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Указывает автоматическое значение интервала меток деления. Если false: использовать свойство TickMarksSpacing. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Указывает автоматическое значение интервала меток деления. Если false: использовать свойство TickMarksSpacing. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Указывает расстояние меток от оси. Применяется к оси категорий или даты. Значение должно быть от 0% до 1000%. Чтение/запись int.

**Возвращаемое значение:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Указывает расстояние меток от оси. Применяется к оси категорий или даты. Значение должно быть от 0% до 1000%. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Указывает тип оси категорий. Чтение/запись [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Возвращаемое значение:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Указывает тип оси категорий. Чтение/запись [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Устанавливает свойство IAxis.CategoryAxisType со значением, автоматически определяемым на основе данных оси.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Представляет тип агрегации оси категорий (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto.

**Возвращаемое значение:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Представляет тип агрегации оси категорий (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```


Указывает ширину корзины, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с рядами Histogram или HistogramPareto.

**Возвращаемое значение:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```


Указывает ширину корзины, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с рядами Histogram или HistogramPareto.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```


Указывает количество корзин, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с рядами Histogram или HistogramPareto.

**Возвращаемое значение:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```


Указывает количество корзин, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с рядами Histogram или HistogramPareto.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```


Указывает, применяется ли переполненная корзина. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполненной корзины.

**Возвращаемое значение:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```


Указывает, применяется ли переполненная корзина. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполненной корзины.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```


Указывает автоматическое значение переполненной корзины. Если false: используйте свойство OverflowBin.

**Возвращаемое значение:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```


Указывает автоматическое значение переполненной корзины. Если false: используйте свойство OverflowBin.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```


Указывает пользовательское значение переполненной корзины. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true.

**Возвращаемое значение:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```


Указывает пользовательское значение переполненной корзины. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```


Указывает, применяется ли недополученная корзина. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недополученной корзины.

**Возвращаемое значение:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```


Указывает, применяется ли недополученная корзина. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недополученной корзины.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```


Указывает автоматическое значение недополученной корзины. Если false: используйте свойство UnderflowBin.

**Возвращаемое значение:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```


Указывает автоматическое значение недополученной корзины. Если false: используйте свойство UnderflowBin.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```


Указывает пользовательское значение недополученной корзины. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true.

**Возвращаемое значение:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```


Указывает пользовательское значение недополученной корзины. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |