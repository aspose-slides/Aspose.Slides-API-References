---
title: ChartDataPoint
second_title: Aspose.Slides for Java API 參考
description: 表示系列資料點。
type: docs
url: /zh-hant/com.aspose.slides/chartdatapoint/
---
**繼承:**  
java.lang.Object

**全部已實作的介面:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

表示系列資料點。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | 返回圖表資料點的大小值。 |
| [getColorValue()](#getColorValue--) | 返回圖表資料點的顏色值。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 在自訂值類型情況下，表示系列誤差棒的值。 |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | 指定氣泡套用 3D 效果。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 指定氣泡套用 3D 效果。 |
| [getExplosion()](#getExplosion--) | 指定資料點應從圓餅圖中心移動的距離。 |
| [setExplosion(int value)](#setExplosion-int-) | 指定資料點應從圓餅圖中心移動的距離。 |
| [getFormat()](#getFormat--) | 表示格式設定屬性。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示格式設定屬性。 |
| [getMarker()](#getMarker--) | 指定資料標記。 |
| [getSetAsTotal()](#getSetAsTotal--) | 將資料點設定為總計。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 將資料點設定為總計。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 對應圖例項目的屬性，適用於以下圖表類型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。 |
| [remove()](#remove--) | 從圖表系列中移除 DataPoint。 |
| [getDataPointLevels()](#getDataPointLevels--) | 返回資料點層級的容器。 |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 返回資料點的自動顏色，基於系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性和圖表樣式。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定資料點在值為負時應反轉其顏色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定資料點在值為負時應反轉其顏色。 |
| [getCachedValue()](#getCachedValue--) | 取得圖表資料點的快取值。 |
| [getCachedXValue()](#getCachedXValue--) | 取得圖表資料點的快取 X 值。 |
| [getCachedYValue()](#getCachedYValue--) | 取得圖表資料點的快取 Y 值。 |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | 取得圖表資料點的快取氣泡大小。 |
| [getActualX()](#getActualX--) | 指定圖表元素相對於圖表左上角的實際 X 位置（左）。 |
| [getActualY()](#getActualY--) | 指定圖表元素相對於圖表左上角的實際上方位置。 |
| [getActualWidth()](#getActualWidth--) | 指定圖表元素的實際寬度。 |
| [getActualHeight()](#getActualHeight--) | 指定圖表元素的實際高度。 |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue。唯讀 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**返回值:**  
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

返回圖表資料點的大小值。用於 Treemap 和 Sunburst 圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

返回圖表資料點的顏色值。用於地圖圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

在自訂值類型情況下，表示系列誤差棒的值。唯讀 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**返回值:**  
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label。唯讀 [IDataLabel](../../com.aspose.slides/idatalabel)。

**返回值:**  
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

指定氣泡套用 3D 效果。可讀寫 boolean。

**返回值:**  
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

指定氣泡套用 3D 效果。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

指定資料點應從圓餅圖中心移動的距離。可讀寫 int。

**返回值:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

指定資料點應從圓餅圖中心移動的距離。可讀寫 int。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示格式設定屬性。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**返回值:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示格式設定屬性。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

指定資料標記。唯讀 [IMarker](../../com.aspose.slides/imarker)。

**返回值:**  
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

將資料點設定為總計。僅適用於 Waterfall 系列類型。

**返回值:**  
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

將資料點設定為總計。僅適用於 Waterfall 系列類型。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

對應圖例項目的屬性，適用於以下圖表類型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回值:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

從圖表系列中移除 DataPoint。

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

返回資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。資料點層級索引從零開始。

**返回值:**  
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**返回值:**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回值:**  
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

返回資料點的自動顏色，基於系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性和圖表樣式。若 FillType 等於 NotDefined，則預設使用此顏色。

**返回值:**  
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

指定資料點在值為負時應反轉其顏色。可讀寫 boolean。

**返回值:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

指定資料點在值為負時應反轉其顏色。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

取得圖表資料點的快取值。唯讀 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 列印圖表系列的所有快取值。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

取得圖表資料點的快取 X 值。唯讀 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 列印圖表系列的所有快取 X 值。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

取得圖表資料點的快取 Y 值。唯讀 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 列印圖表系列的所有快取 Y 值。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

取得圖表資料點的快取氣泡大小。唯讀 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 列印圖表系列的所有快取氣泡大小值。
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定圖表元素相對於圖表左上角的實際 X 位置（左）。在取得實際值前請先呼叫 IChart.ValidateChartLayout()。唯讀 float。

**返回值:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定圖表元素相對於圖表左上角的實際上方位置。在取得實際值前請先呼叫 IChart.ValidateChartLayout()。唯讀 float。

**返回值:**  
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定圖表元素的實際寬度。在取得實際值前請先呼叫 IChart.ValidateChartLayout()。唯讀 float。

**返回值:**  
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定圖表元素的實際高度。在取得實際值前請先呼叫 IChart.ValidateChartLayout()。唯讀 float。

**返回值:**  
float