---
title: IChartDataPoint
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示系列資料點。
type: docs
url: /zh-hant/com.aspose.slides/ichartdatapoint/
---
**所有實作的介面：**
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
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 表示在自訂值類型情況下的系列誤差棒值。 |
| [getLabel()](#getLabel--) | 表示圖表資料點的標籤。 |
| [isBubble3D()](#isBubble3D--) | 指定氣泡套用了 3-D 效果。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 指定氣泡套用了 3-D 效果。 |
| [getExplosion()](#getExplosion--) | 指定資料點應從餅圖中心移動的量。 |
| [setExplosion(int value)](#setExplosion-int-) | 指定資料點應從餅圖中心移動的量。 |
| [getFormat()](#getFormat--) | 表示格式屬性。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 表示格式屬性。 |
| [getMarker()](#getMarker--) | 指定資料標記。 |
| [remove()](#remove--) | 從圖表系列中移除 DataPoint。 |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性和圖表樣式返回資料點的自動顏色。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 對應圖例項目的屬性，適用於以下圖表類型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。 |
| [getSetAsTotal()](#getSetAsTotal--) | 將資料點設定為總計。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 將資料點設定為總計。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定當值為負時資料點應反轉顏色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定當值為負時資料點應反轉顏色。 |
| [getDataPointLevels()](#getDataPointLevels--) | 返回資料點層級的容器。 |
| [getIndex()](#getIndex--) | 確定此資料點適用於父項子集合中的哪一個。 |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

返回圖表資料點的 x 值。唯讀 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**返回:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

返回圖表資料點的 y 值。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

返回圖表資料點的氣泡大小。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

返回圖表資料點的值。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

返回圖表資料點的大小值。用於 Treemap 和 Sunburst 圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

返回圖表資料點的顏色值。用於 Map 圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

表示在自訂值類型情況下的系列誤差棒值。唯讀 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**返回:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

表示圖表資料點的標籤。唯讀 [IDataLabel](../../com.aspose.slides/idatalabel)。

**返回:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

指定氣泡套用了 3-D 效果。讀寫布林值。

**返回:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

指定氣泡套用了 3-D 效果。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

指定資料點應從餅圖中心移動的量。讀寫整數。

**返回:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

指定資料點應從餅圖中心移動的量。讀寫整數。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

表示格式屬性。讀寫 [IFormat](../../com.aspose.slides/iformat)。

**返回:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

表示格式屬性。讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

指定資料標記。唯讀 [IMarker](../../com.aspose.slides/imarker)。

**返回:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

從圖表系列中移除 DataPoint。

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性和圖表樣式返回資料點的自動顏色。若 FillType 等於 NotDefined，則預設使用此顏色。

**返回:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

對應圖例項目的屬性，適用於以下圖表類型：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

將資料點設定為總計。僅適用於 Waterfall 系列類型。

**返回:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

將資料點設定為總計。僅適用於 Waterfall 系列類型。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

指定當值為負時資料點應反轉顏色。讀寫布林值。

**返回:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

指定當值為負時資料點應反轉顏色。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

返回資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。資料點層級索引從 0 開始。

**返回:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

確定此資料點適用於父項子集合中的哪一個。唯讀 long。

**返回:**
long