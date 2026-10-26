---
title: IChartDataPoint
second_title: Aspose.Slides for Java API 參考
description: 代表系列資料點。
type: docs
url: /zh-hant/com.aspose.slides/ichartdatapoint/
---
**所有已實作的介面：**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

表示系列資料點。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getXValue()](#getXValue--) | 返回圖表資料點的 x 值。 |
| [getYValue()](#getYValue--) | 返回圖表資料點的 y 值。 |
| [getBubbleSize()](#getBubbleSize--) | 返回圖表資料點的氣泡大小。 |
| [getValue()](#getValue--) | 返回圖表資料點的值。 |
| [getSizeValue()](#getSizeValue--) | 返回圖表資料點的大小值。 |
| [getColorValue()](#getColorValue--) | 返回圖表資料點的顏色值。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 在自訂值類型的情況下，代表系列誤差棒的值。 |
| [getLabel()](#getLabel--) | 表示圖表資料點的標籤。 |
| [isBubble3D()](#isBubble3D--) | 指定氣泡已套用 3-D 效果。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 指定氣泡已套用 3-D 效果。 |
| [getExplosion()](#getExplosion--) | 指定資料點應從圓餅圖中心移動的距離。 |
| [setExplosion(int value)](#setExplosion-int-) | 指定資料點應從圓餅圖中心移動的距離。 |
| [getFormat()](#getFormat--) | 表示格式屬性。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示格式屬性。 |
| [getMarker()](#getMarker--) | 指定資料標記。 |
| [remove()](#remove--) | 從圖表系列中移除 DataPoint。 |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性以及圖表樣式，返回資料點的自動顏色。此顏色在 FillType 為 NotDefined 時為預設使用。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 在以下圖表類型的情況下，對應圖例項目的屬性：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。 |
| [getSetAsTotal()](#getSetAsTotal--) | 將資料點設為總計。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 將資料點設為總計。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定如果值為負，資料點應反轉其顏色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定如果值為負，資料點應反轉其顏色。 |
| [getDataPointLevels()](#getDataPointLevels--) | 返回資料點層級的容器。 |
| [getIndex()](#getIndex--) | 確定此資料點適用於父項的哪個子集合。 |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

返回圖表資料點的 x 值。唯讀 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**回傳：**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

返回圖表資料點的 y 值。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

返回圖表資料點的氣泡大小。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

返回圖表資料點的值。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

返回圖表資料點的大小值。用於 Treemap 和 Sunburst 圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

返回圖表資料點的顏色值。用於 Map 圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**回傳：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

在自訂值類型的情況下，代表系列誤差棒的值。唯讀 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**回傳：**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

表示圖表資料點的標籤。唯讀 [IDataLabel](../../com.aspose.slides/idatalabel)。

**回傳：**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

指定氣泡已套用 3-D 效果。讀寫 boolean。

**回傳：**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

指定氣泡已套用 3-D 效果。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

指定資料點應從圓餅圖中心移動的距離。讀寫 int。

**回傳：**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

指定資料點應從圓餅圖中心移動的距離。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示格式屬性。讀寫 [IFormat](../../com.aspose.slides/iformat)。

**回傳：**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

表示格式屬性。讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

指定資料標記。唯讀 [IMarker](../../com.aspose.slides/imarker)。

**回傳：**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

從圖表系列中移除 DataPoint。

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性以及圖表樣式，返回資料點的自動顏色。此顏色在 FillType 為 NotDefined 時為預設使用。

**回傳：**
java.awt.Color - Automatic color of data point java.awt.Color

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

在以下圖表類型的情況下，對應圖例項目的屬性：ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**回傳：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

將資料點設為總計。僅適用於 Waterfall 系列類型。

**回傳：**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

將資料點設為總計。僅適用於 Waterfall 系列類型。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

指定如果值為負，資料點應反轉其顏色。讀寫 boolean。

**回傳：**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

指定如果值為負，資料點應反轉其顏色。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

返回資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。資料點層級索引從零開始。

**回傳：**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

確定此資料點適用於父項的哪個子集合。唯讀 long。

**回傳：**
long