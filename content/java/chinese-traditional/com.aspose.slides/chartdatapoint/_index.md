---
title: ChartDataPoint
second_title: Aspose.Slides for Java API 參考文件
description: 表示系列資料點。
type: docs
url: /zh-hant/com.aspose.slides/chartdatapoint/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

表示系列資料點。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | 返回圖表資料點的大小值。 |
| [getColorValue()](#getColorValue--) | 返回圖表資料點的顏色值。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 表示系列錯誤棒值（Custom 型別）。 |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | 指定氣泡套用 3-D 效果。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 指定氣泡套用 3-D 效果。 |
| [getExplosion()](#getExplosion--) | 指定資料點相對於圓餅中心的移動距離。 |
| [setExplosion(int value)](#setExplosion-int-) | 指定資料點相對於圓餅中心的移動距離。 |
| [getFormat()](#getFormat--) | 表示格式屬性。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示格式屬性。 |
| [getMarker()](#getMarker--) | 指定資料標記。 |
| [getSetAsTotal()](#getSetAsTotal--) | 設定資料點為總計。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 設定資料點為總計。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 對應圖例項目的屬性，適用於以下圖表類型：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | 從圖表系列中移除 DataPoint。 |
| [getDataPointLevels()](#getDataPointLevels--) | 返回資料點層級的容器。 |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 返回根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性與圖表樣式自動決定的資料點顏色。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定如果值為負則反轉資料點的顏色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定如果值為負則反轉資料點的顏色。 |
| [getActualX()](#getActualX--) | 指定圖表元素相對於圖表左上角的實際 X 位置（左）。 |
| [getActualY()](#getActualY--) | 指定圖表元素相對於圖表左上角的實際 Y 位置（上）。 |
| [getActualWidth()](#getActualWidth--) | 指定圖表元素的實際寬度。 |
| [getActualHeight()](#getActualHeight--) | 指定圖表元素的實際高度。 |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. 唯讀 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**返回：**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. 唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. 唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. 唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

返回圖表資料點的大小值。用於 Treemap 和 Sunburst 圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

返回圖表資料點的顏色值。用於 Map 圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

表示系列錯誤棒值（Custom 型別）。唯讀 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**返回：**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. 唯讀 [IDataLabel](../../com.aspose.slides/idatalabel)。

**返回：**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

指定氣泡套用 3-D 效果。可讀寫 boolean。

**返回：**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

指定氣泡套用 3-D 效果。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

指定資料點相對於圓餅中心的移動距離。可讀寫 int。

**返回：**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

指定資料點相對於圓餅中心的移動距離。可讀寫 int。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

表示格式屬性。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

表示格式屬性。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

指定資料標記。唯讀 [IMarker](../../com.aspose.slides/imarker)。

**返回：**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

設定資料點為總計。僅適用於 Waterfall 系列類型。

**返回：**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

設定資料點為總計。僅適用於 Waterfall 系列類型。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

對應圖例項目的屬性，適用於以下圖表類型：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回：**
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

返回資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。資料點層級索引為零基。

**返回：**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**返回：**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

返回根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性與圖表樣式自動決定的資料點顏色。若 FillType 為 NotDefined，則使用此顏色作為預設。

**返回：**
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

指定如果值為負則反轉資料點的顏色。可讀寫 boolean。

**返回：**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

指定如果值為負則反轉資料點的顏色。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定圖表元素相對於圖表左上角的實際 X 位置（左）。在取得實際值前請先呼叫 IChart.ValidateChartLayout()。唯讀 float。

**返回：**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定圖表元素相對於圖表左上角的實際 Y 位置（上）。在取得實際值前請先呼叫 IChart.ValidateChartLayout()。唯讀 float。

**返回：**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定圖表元素的實際寬度。在取得實際值前請先呼叫 IChart.ValidateChartLayout()。唯讀 float。

**返回：**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定圖表元素的實際高度。在取得實際值前請先呼叫 IChart.ValidateChartLayout()。唯讀 float。

**返回：**
float