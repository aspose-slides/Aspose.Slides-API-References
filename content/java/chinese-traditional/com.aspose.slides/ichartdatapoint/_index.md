---
title: IChartDataPoint
second_title: Aspose.Slides for Java API 參考
description: 代表系列資料點。
type: docs
url: /zh-hant/com.aspose.slides/ichartdatapoint/
---
**已實作的介面：**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

代表系列資料點。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getXValue()](#getXValue--) | 取得圖表資料點的 x 值。 |
| [getYValue()](#getYValue--) | 取得圖表資料點的 y 值。 |
| [getBubbleSize()](#getBubbleSize--) | 取得圖表資料點的氣泡大小。 |
| [getValue()](#getValue--) | 取得圖表資料點的值。 |
| [getCachedXValue()](#getCachedXValue--) | 取得圖表資料點的快取 X 值。 |
| [getCachedYValue()](#getCachedYValue--) | 取得圖表資料點的快取 Y 值。 |
| [getCachedValue()](#getCachedValue--) | 取得圖表資料點的快取值。 |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | 取得圖表資料點的快取氣泡大小。 |
| [getSizeValue()](#getSizeValue--) | 取得圖表資料點的大小值。 |
| [getColorValue()](#getColorValue--) | 取得圖表資料點的顏色值。 |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 代表自訂值類型的系列誤差棒值。 |
| [getLabel()](#getLabel--) | 代表圖表資料點的標籤。 |
| [isBubble3D()](#isBubble3D--) | 指定氣泡套用 3D 效果。 |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 指定氣泡套用 3D 效果。 |
| [getExplosion()](#getExplosion--) | 指定資料點從圓餅圖中心移動的距離。 |
| [setExplosion(int value)](#setExplosion-int-) | 指定資料點從圓餅圖中心移動的距離。 |
| [getFormat()](#getFormat--) | 代表格式屬性。 |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 代表格式屬性。 |
| [getMarker()](#getMarker--) | 指定資料標記。 |
| [remove()](#remove--) | 從圖表系列中移除資料點。 |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性與圖表樣式，返回資料點的自動顏色。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 對於以下圖表類型之相應圖例項目的屬性：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。 |
| [getSetAsTotal()](#getSetAsTotal--) | 將資料點設定為總計。 |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 將資料點設定為總計。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定當值為負時，資料點應反轉其顏色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定當值為負時，資料點應反轉其顏色。 |
| [getDataPointLevels()](#getDataPointLevels--) | 返回資料點層級的容器。 |
| [getIndex()](#getIndex--) | 確定此資料點適用於父項子集合中的哪一個。 |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


取得圖表資料點的 x 值。唯讀 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)。

**返回值：**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


取得圖表資料點的 y 值。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


取得圖表資料點的氣泡大小。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


取得圖表資料點的值。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
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

**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
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

**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
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

**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
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

**返回值：**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


取得圖表資料點的大小值。用於 Treemap 和 Sunburst 圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


取得圖表資料點的顏色值。用於地圖圖表。唯讀 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)。

**返回值：**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


代表自訂值類型的系列誤差棒值。唯讀 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)。

**返回值：**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


代表圖表資料點的標籤。唯讀 [IDataLabel](../../com.aspose.slides/idatalabel)。

**返回值：**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


指定氣泡套用 3D 效果。可讀寫布林值。

**返回值：**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


指定氣泡套用 3D 效果。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


指定資料點從圓餅圖中心移動的距離。可讀寫 int。

**返回值：**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


指定資料點從圓餅圖中心移動的距離。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


代表格式屬性。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**返回值：**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


代表格式屬性。可讀寫 [IFormat](../../com.aspose.slides/iformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


指定資料標記。唯讀 [IMarker](../../com.aspose.slides/imarker)。

**返回值：**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


從圖表系列中移除資料點。

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


根據系列索引、資料點索引、ParentSeriesGroup.IsColorVaried 屬性與圖表樣式，返回資料點的自動顏色。如果 FillType 為 NotDefined，則預設使用此顏色。

**返回值：**
java.awt.Color - 資料點的自動顏色 java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


對於以下圖表類型之相應圖例項目的屬性：ChartType.BarOfPie、ChartType.ExplodedPie、ChartType.ExplodedPie3D、ChartType.Pie、ChartType.Pie3D、ChartType.PieOfPie。唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回值：**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


將資料點設定為總計。僅適用於 Waterfall 系列類型。

**返回值：**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


將資料點設定為總計。僅適用於 Waterfall 系列類型。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


指定當值為負時，資料點應反轉其顏色。可讀寫布林值。

**返回值：**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


指定當值為負時，資料點應反轉其顏色。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


返回資料點層級的容器。適用於 Treeamp 和 Sunburst 系列。資料點層級索引從零開始。

**返回值：**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


確定此資料點適用於父項子集合中的哪一個。唯讀 long。

**返回值：**
long