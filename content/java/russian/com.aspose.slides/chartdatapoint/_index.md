---
title: ChartDataPoint
second_title: Справочник API Aspose.Slides для Java
description: Представляет точку данных серии.
type: docs
url: /ru/com.aspose.slides/chartdatapoint/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Represents series data point.
## Методы

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Returns the size value of chart data point. |
| [getColorValue()](#getColorValue--) | Returns the color value of chart data point. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Represents series error bars values in case of Custom value type. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Specifies that the bubbles have a 3-D effect applied to them. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifies that the bubbles have a 3-D effect applied to them. |
| [getExplosion()](#getExplosion--) | Specifies the amount the data point shall be moved from the center of the pie. |
| [setExplosion(int value)](#setExplosion-int-) | Specifies the amount the data point shall be moved from the center of the pie. |
| [getFormat()](#getFormat--) | Represents the formatting properties. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the formatting properties. |
| [getMarker()](#getMarker--) | Specifies a data marker. |
| [getSetAsTotal()](#getSetAsTotal--) | Sets data point as total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Sets data point as total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Removes DataPoint from chart series. |
| [getDataPointLevels()](#getDataPointLevels--) | Returns container of data point levels. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the data point shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the data point shall invert its colors if the value is negative. |
| [getCachedValue()](#getCachedValue--) | Gets the cached value of a chart data point. |
| [getCachedXValue()](#getCachedXValue--) | Gets the cached X value of a chart data point. |
| [getCachedYValue()](#getCachedYValue--) | Gets the cached Y value of a chart data point. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Gets the cached bubble size of a chart data point. |
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Только для чтения [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Возвращаемое значение:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Возвращает значение размера точки данных. Используется с диаграммами Treemap и Sunburst. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Возвращает значение цвета точки данных. Используется с картографическими диаграммами. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Представляет значения линий ошибок серии в случае типа значения Custom. Только для чтения [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Возвращаемое значение:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Только для чтения [IDataLabel](../../com.aspose.slides/idatalabel).

**Возвращаемое значение:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Указывает, что пузырьки имеют примененный 3-D эффект. Чтение/запись boolean.

**Returns:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Указывает, что пузырьки имеют примененный 3-D эффект. Чтение/запись boolean.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Указывает величину, на которую точка данных должна быть смещена от центра пирога. Чтение/запись int.

**Возвращаемое значение:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Указывает величину, на которую точка данных должна быть смещена от центра пирога. Чтение/запись int.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Представляет свойства форматирования. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Представляет свойства форматирования. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Указывает маркер данных. Только для чтения [IMarker](../../com.aspose.slides/imarker).

**Возвращаемое значение:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Устанавливает точку данных как итоговую. Применяется только для типа серии Waterfall.

**Возвращаемое значение:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Устанавливает точку данных как итоговую. Применяется только для типа серии Waterfall.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Свойства соответствующей записи легенды в случае типа диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возвращаемое значение:**
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

**Возвращаемое значение:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Возвращаемое значение:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```


Возвращает автоматический цвет точки данных, основанный на индексе серии, индексе точки данных, свойстве ParentSeriesGroup.IsColorVaried и стиле диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined.

**Возвращаемое значение:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись boolean.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```


Получает кэшированное значение точки данных диаграммы. Только для чтения [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Вывести все кэшированные значения серии диаграммы.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```


Получает кэшированное значение X точки данных диаграммы. Только для чтения [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Вывести все кэшированные X-значения серии диаграммы.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```


Получает кэшированное значение Y точки данных диаграммы. Только для чтения [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Вывести все кэшированные Y-значения серии диаграммы.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```


Получает кэшированный размер пузырька точки данных диаграммы. Только для чтения [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Вывести все кэшированные значения размеров пузырьков серии диаграммы.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Указывает фактическое положение по оси X (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Возвращаемое значение:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Возвращаемое значение:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Указывает фактическую ширину элемента диаграммы. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Возвращаемое значение:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Указывает фактическую высоту элемента диаграммы. Call method IChart.ValidateChartLayout() before to get actual values. Read float.

**Возвращаемое значение:**
float