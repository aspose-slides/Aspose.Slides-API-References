---
title: ChartDataPoint
second_title: Aspose.Slides для Android через Java API
description: Представляет точку данных серии.
type: docs
url: /ru/com.aspose.slides/chartdatapoint/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Представляет точку данных серии.
## Методы

| Метод | Описание |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Возвращает значение размера точки данных диаграммы. |
| [getColorValue()](#getColorValue--) | Возвращает значение цвета точки данных диаграммы. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Представляет значения столбцов ошибок серии в случае типа значения Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Указывает, что у пузырей применяется 3-D эффект. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Указывает, что у пузырей применяется 3-D эффект. |
| [getExplosion()](#getExplosion--) | Указывает величину, на которую точка данных должна быть смещена от центра пирога. |
| [setExplosion(int value)](#setExplosion-int-) | Указывает величину, на которую точка данных должна быть смещена от центра пирога. |
| [getFormat()](#getFormat--) | Представляет свойства форматирования. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Представляет свойства форматирования. |
| [getMarker()](#getMarker--) | Указывает маркер данных. |
| [getSetAsTotal()](#getSetAsTotal--) | Устанавливает точку данных как общую. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Устанавливает точку данных как общую. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Свойства соответствующей записи легенды в случае типа диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Удаляет DataPoint из серии диаграммы. |
| [getDataPointLevels()](#getDataPointLevels--) | Возвращает контейнер уровней точек данных. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля диаграммы. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. |
| [getActualX()](#getActualX--) | Указывает фактическое расположение по оси X (слева) элемента диаграммы относительно левого верхнего угла диаграммы. |
| [getActualY()](#getActualY--) | Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. |
| [getActualWidth()](#getActualWidth--) | Указывает фактическую ширину элемента диаграммы. |
| [getActualHeight()](#getActualHeight--) | Указывает фактическую высоту элемента диаграммы. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Только для чтения [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Возвращает:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Возвращает значение размера точки данных диаграммы. Используется в диаграммах Treemap и Sunburst. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Возвращает значение цвета точки данных диаграммы. Используется в картографических диаграммах. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Представляет значения столбцов ошибок серии в случае типа значения Custom. Только для чтения [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Возвращает:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Только для чтения [IDataLabel](../../com.aspose.slides/idatalabel).

**Возвращает:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Указывает, что у пузырей применяется 3-D эффект. Чтение/запись boolean.

**Возвращает:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Указывает, что у пузырей применяется 3-D эффект. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Указывает величину, на которую точка данных должна быть смещена от центра пирога. Чтение/запись int.

**Возвращает:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Указывает величину, на которую точка данных должна быть смещена от центра пирога. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Представляет свойства форматирования. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Представляет свойства форматирования. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Указывает маркер данных. Только для чтения [IMarker](../../com.aspose.slides/imarker).

**Возвращает:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Устанавливает точку данных как общую. Применяется только для серии типа Waterfall.

**Возвращает:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Устанавливает точку данных как общую. Применяется только для серии типа Waterfall.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Свойства соответствующей записи легенды в случае типа диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возвращает:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


Удаляет DataPoint из серии диаграммы.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля.

**Возвращает:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Возвращает:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```


Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined.

**Возвращает:**
java.lang.Integer
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись boolean.

**Возвращает:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```


Указывает фактическое расположение по оси X (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Чтение float.

**Возвращает:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Чтение float.

**Возвращает:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Чтение float.

**Возвращает:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Чтение float.

**Возвращает:**
float