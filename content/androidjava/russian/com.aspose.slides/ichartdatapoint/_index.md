---
title: IChartDataPoint
second_title: Aspose.Slides для Android через Java API
description: Представляет точку данных серии.
type: docs
url: /ru/com.aspose.slides/ichartdatapoint/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Представляет точку данных серии.
## Методы

| Метод | Описание |
| --- | --- |
| [getXValue()](#getXValue--) | Возвращает значение x точки данных диаграммы. |
| [getYValue()](#getYValue--) | Возвращает значение y точки данных диаграммы. |
| [getBubbleSize()](#getBubbleSize--) | Возвращает размер пузыря точки данных диаграммы. |
| [getValue()](#getValue--) | Возвращает значение точки данных диаграммы. |
| [getSizeValue()](#getSizeValue--) | Возвращает размерное значение точки данных диаграммы. |
| [getColorValue()](#getColorValue--) | Возвращает значение цвета точки данных диаграммы. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Предоставляет значения линий ошибок серии в случае пользовательского типа значения. |
| [getLabel()](#getLabel--) | Предоставляет подпись точки данных диаграммы. |
| [isBubble3D()](#isBubble3D--) | Указывает, что пузыри имеют примененный 3-D эффект. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Указывает, что пузыри имеют примененный 3-D эффект. |
| [getExplosion()](#getExplosion--) | Указывает величину, на которую точка данных должна быть смещена от центра пирога. |
| [setExplosion(int value)](#setExplosion-int-) | Указывает величину, на которую точка данных должна быть смещена от центра пирога. |
| [getFormat()](#getFormat--) | Представляет свойства форматирования. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Представляет свойства форматирования. |
| [getMarker()](#getMarker--) | Указывает маркер данных. |
| [remove()](#remove--) | Удаляет DataPoint из серии диаграммы. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля диаграммы. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Свойства соответствующей записи легенды в случае типа диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Устанавливает точку данных как общую. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Устанавливает точку данных как общую. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. |
| [getDataPointLevels()](#getDataPointLevels--) | Возвращает контейнер уровней точек данных. |
| [getIndex()](#getIndex--) | Определяет, к какой из коллекций дочерних элементов родителя относится данная точка данных. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Возвращает значение x точки данных диаграммы. Только для чтения [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Возвращаемое значение:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Возвращает значение y точки данных диаграммы. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Возвращает размер пузыря точки данных диаграммы. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Возвращает значение точки данных диаграммы. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Возвращает размерное значение точки данных диаграммы. Используется с диаграммами Treemap и Sunburst. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Возвращает значение цвета точки данных диаграммы. Используется с картографическими диаграммами. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Представляет значения линий ошибок серии в случае пользовательского типа значения. Только для чтения [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Возвращаемое значение:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Представляет подпись точки данных диаграммы. Только для чтения [IDataLabel](../../com.aspose.slides/idatalabel).

**Возвращаемое значение:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Указывает, что пузыри имеют примененный 3-D эффект. Чтение/запись, boolean.

**Возвращаемое значение:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Указывает, что пузыри имеют примененный 3-D эффект. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Указывает величину, на которую точка данных должна быть смещена от центра пирога. Чтение/запись, int.

**Возвращаемое значение:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Указывает величину, на которую точка данных должна быть смещена от центра пирога. Чтение/запись, int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Представляет свойства форматирования. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Представляет свойства форматирования. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Указывает маркер данных. Только для чтения [IMarker](../../com.aspose.slides/imarker).

**Возвращаемое значение:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Удаляет DataPoint из серии диаграммы.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined.

**Возвращаемое значение:**
java.lang.Integer - Автоматический цвет точки данных java.lang.Integer

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Свойства соответствующей записи легенды в случае типа диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возвращаемое значение:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Устанавливает точку данных как общую. Применяется только для типа серии Waterfall.

**Возвращаемое значение:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Устанавливает точку данных как общую. Применяется только для типа серии Waterfall.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись, boolean.

**Возвращаемое значение:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля.

**Возвращаемое значение:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Определяет, к какой из коллекций дочерних элементов родителя относится данная точка данных. Чтение, long.

**Возвращаемое значение:**
long