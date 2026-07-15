---
title: IChartSeriesGroup
second_title: Aspose.Slides for Android via Java API 參考
description: 表示系列的群組。
type: docs
url: /zh-hant/com.aspose.slides/ichartseriesgroup/
---
**所有已實作的介面：**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

表示系列的群組。

--------------------

1) 請參閱 ChartSeriesGroupCollection 類別與 CombinableSeriesTypesGroup 列舉的摘要與說明。2) 系列群組包含一些對群組中每個系列共通的系列屬性（「series group properties」）。ChartSeriesGroup 類別中的「Series group properties」為讀/寫。每個「series group properties」在 ChartSeries 類別中可有唯讀投影。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 傳回此系列群組的類型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此群組的系列是否繪製於次要座標軸上。 |
| [getSeries()](#getSeries--) | 傳回圖表系列的唯讀集合。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供對 Line- 或 Stock-圖之上/下棒的存取。 |
| [getGapWidth()](#getGapWidth--) | 指定柱或欄叢之間的間距，以柱或欄寬度的百分比表示。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 指定柱或欄叢之間的間距，以柱或欄寬度的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 傳回或設定在 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 傳回或設定在 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 取得或設定第一個圓餅或環形圖切片的角度，單位為度（順時針方向，從上方開始，範圍 0 至 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 取得或設定第一個圓餅或環形圖切片的角度，單位為度（順時針方向，從上方開始，範圍 0 至 360 度）。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記都有不同的顏色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每個資料標記都有不同的顏色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 如果圖表具有系列線則為 True。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 如果圖表具有系列線則為 True。 |
| [getOverlap()](#getOverlap--) | 指定在 2-D 圖表上柱與欄的重疊程度，以百分比表示（-100% 到 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定在 2-D 圖表上柱與欄的重疊程度，以百分比表示（-100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定在 pie-of-pie 圖或 bar-of-pie 圖中第二個圓餅或柱的大小，以第一個圓餅大小的百分比表示（可在 5% 至 200% 之間）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定在 pie-of-pie 圖或 bar-of-pie 圖中第二個圓餅或柱的大小，以第一個圓餅大小的百分比表示（可在 5% 至 200% 之間）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用於決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖中第二個圓餅或柱的值。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定用於決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖中第二個圓餅或柱的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖中第二個圓餅或柱。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖中第二個圓餅或柱。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 具有自訂分割的 pie-of-pie 或 bar-of-pie 圖的自訂分割資訊。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定環形圖中洞的大小（可在繪圖區大小的 10% 至 90% 之間）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定環形圖中洞的大小（可在繪圖區大小的 10% 至 90% 之間）。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的比例係數（可在預設大小的 0% 至 300% 之間）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定氣泡圖的比例係數（可在預設大小的 0% 至 300% 之間）。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 格式。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖上氣泡大小值的表示方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定氣泡圖上氣泡大小值的表示方式。 |

### getType() {#getType--}
```
public abstract int getType()
```

傳回此系列群組的類型。唯讀 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**傳回：**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

指示此群組的系列是否繪製於次要座標軸上。唯讀 boolean。

**傳回：**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

傳回圖表系列的唯讀集合。唯讀 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**傳回：**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

取得指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回：**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

提供對 Line- 或 Stock-圖之上/下棒的存取。唯讀 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**傳回：**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

指定柱或欄叢之間的間距，以柱或欄寬度的百分比表示。讀/寫 int。

**傳回：**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

指定柱或欄叢之間的間距，以柱或欄寬度的百分比表示。讀/寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

傳回或設定在 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。讀/寫 int。

**傳回：**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

傳回或設定在 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。讀/寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

取得或設定第一個圓餅或環形圖切片的角度，單位為度（順時針方向，從上方開始，範圍 0 至 360 度）。讀/寫 int。

**傳回：**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

取得或設定第一個圓餅或環形圖切片的角度，單位為度（順時針方向，從上方開始，範圍 0 至 360 度）。讀/寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

指定系列中的每個資料標記都有不同的顏色。讀/寫 boolean。

**傳回：**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

指定系列中的每個資料標記都有不同的顏色。讀/寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

如果圖表具有系列線則為 True。套用於堆疊柱與 OfPie 圖表。讀/寫 boolean。

**傳回：**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

如果圖表具有系列線則為 True。套用於堆疊柱與 OfPie 圖表。讀/寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

指定在 2-D 圖表上柱與欄的重疊程度，以百分比表示（-100% 至 100%）。- -100%：最大間距（柱完全分離）。- 0%：柱並排放置，無重疊或間距。- 100%：最大重疊（柱完全重疊）。此屬性為讀/寫 byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 設定重疊為 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

指定在 2-D 圖表上柱與欄的重疊程度，以百分比表示（-100% 至 100%）。- -100%：最大間距（柱完全分離）。- 0%：柱並排放置，無重疊或間距。- 100%：最大重疊（柱完全重疊）。此屬性為讀/寫 byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // 設定重疊為 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

指定在 pie-of-pie 圖或 bar-of-pie 圖中第二個圓餅或柱的大小，以第一個圓餅大小的百分比表示（可在 5% 至 200% 之間）。讀/寫 int。

**傳回：**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

指定在 pie-of-pie 圖或 bar-of-pie 圖中第二個圓餅或柱的大小，以第一個圓餅大小的百分比表示（可在 5% 至 200% 之間）。讀/寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

指定用於決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖中第二個圓餅或柱的值。此屬性與 PieSplitBy 屬性一起使用。讀/寫 double。

**傳回：**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

指定用於決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖中第二個圓餅或柱的值。此屬性與 PieSplitBy 屬性一起使用。讀/寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

指定如何決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖中第二個圓餅或柱。讀/寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**傳回：**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

指定如何決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖中第二個圓餅或柱。讀/寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

具有自訂分割的 pie-of-pie 或 bar-of-pie 圖的自訂分割資訊。包含應在第二個圓餅或柱中繪製的資料點。唯讀 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

**傳回：**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

指定環形圖中洞的大小（可在繪圖區大小的 10% 至 90% 之間）。讀/寫 byte。

**傳回：**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

指定環形圖中洞的大小（可在繪圖區大小的 10% 至 90% 之間）。讀/寫 byte。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

指定氣泡圖的比例係數（可在預設大小的 0% 至 300% 之間）。讀/寫 int。

**傳回：**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

指定氣泡圖的比例係數（可在預設大小的 0% 至 300% 之間）。讀/寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

指定 HiLowLines 格式。HiLowLines 套用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 與 VolumeOpenHiLowClose 圖表類型。

**傳回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

指定氣泡圖上氣泡大小值的表示方式。讀/寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**傳回：**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

指定氣泡圖上氣泡大小值的表示方式。讀/寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |