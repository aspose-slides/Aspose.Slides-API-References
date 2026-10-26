---
title: IChartSeriesGroup
second_title: Aspose.Slides for Java API 參考
description: 代表系列群組。
type: docs
url: /zh-hant/com.aspose.slides/ichartseriesgroup/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

代表系列群組。

--------------------

1) 請參閱 ChartSeriesGroupCollection 類別和 CombinableSeriesTypesGroup 列舉的摘要和備註。2) 系列群組包含一些對群組中每個系列通用的系列屬性（「系列群組屬性」）。ChartSeriesGroup 類別中的「系列群組屬性」是可讀寫的。每個「系列群組屬性」在 ChartSeries 類別中可以有唯讀的投影。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 傳回此系列群組的類型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此群組的系列是否繪製在次要座標軸上。 |
| [getSeries()](#getSeries--) | 傳回圖表系列的唯讀集合。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供對折線圖或股票圖之升/降棒的存取。 |
| [getGapWidth()](#getGapWidth--) | 指定條形或柱形叢集之間的間距，作為條形或柱形寬度的百分比。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 指定條形或柱形叢集之間的間距，作為條形或柱形寬度的百分比。 |
| [getGapDepth()](#getGapDepth--) | 傳回或設定 3D 圖表中資料系列之間的距離，作為標記寬度的百分比。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 傳回或設定 3D 圖表中資料系列之間的距離，作為標記寬度的百分比。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 取得或設定第一個圓餅或環形圖切片的角度（以度為單位，順時針從上方起算，範圍 0 到 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 取得或設定第一個圓餅或環形圖切片的角度（以度為單位，順時針從上方起算，範圍 0 到 360 度）。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記具有不同的顏色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每個資料標記具有不同的顏色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 如果圖表具有系列線則為 true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 如果圖表具有系列線則為 true。 |
| [getOverlap()](#getOverlap--) | 指定條形和柱形在二維圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定條形和柱形在二維圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定餅中餅或條形圖的第二個餅或條的大小，作為第一個餅大小的百分比（可在 5% 到 200% 之間）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定餅中餅或條形圖的第二個餅或條的大小，作為第一個餅大小的百分比（可在 5% 到 200% 之間）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定一個值，用於決定在餅中餅或條形圖中哪些資料點屬於第二個餅或條。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定一個值，用於決定在餅中餅或條形圖中哪些資料點屬於第二個餅或條。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何決定在餅中餅或條形圖中哪些資料點屬於第二個餅或條。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何決定在餅中餅或條形圖中哪些資料點屬於第二個餅或條。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 具有自訂切分的餅中餅或條形圖的自訂切分資訊。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定環形圖中孔的大小（可為繪圖區大小的 10% 到 90%）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定環形圖中孔的大小（可為繪圖區大小的 10% 到 90%）。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定泡泡圖的比例係數（可為預設大小的 0% 到 300%）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定泡泡圖的比例係數（可為預設大小的 0% 到 300%）。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 格式。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定在泡泡圖上如何表示泡泡大小值。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定在泡泡圖上如何表示泡泡大小值。 |

### getType() {#getType--}
```
public abstract int getType()
```

傳回此系列群組的類型。唯讀 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**傳回值:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

指示此群組的系列是否繪製在次要座標軸上。唯讀 boolean。

**傳回值:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

傳回圖表系列的唯讀集合。唯讀 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**傳回值:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

提供對折線圖或股票圖之升/降棒的存取。唯讀 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**傳回值:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

指定條形或柱形叢集之間的間距，作為條形或柱形寬度的百分比。可讀寫 int。

**傳回值:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

指定條形或柱形叢集之間的間距，作為條形或柱形寬度的百分比。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

傳回或設定 3D 圖表中資料系列之間的距離，作為標記寬度的百分比。可讀寫 int。

**傳回值:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

傳回或設定 3D 圖表中資料系列之間的距離，作為標記寬度的百分比。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

取得或設定第一個圓餅或環形圖切片的角度（以度為單位，順時針從上方起算，範圍 0 到 360 度）。可讀寫 int。

**傳回值:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

取得或設定第一個圓餅或環形圖切片的角度（以度為單位，順時針從上方起算，範圍 0 到 360 度）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

指定系列中的每個資料標記具有不同的顏色。可讀寫 boolean。

**傳回值:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

指定系列中的每個資料標記具有不同的顏色。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

如果圖表具有系列線則為 true。適用於堆疊條形圖和 OfPie 圖表。可讀寫 boolean。

**傳回值:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

如果圖表具有系列線則為 true。適用於堆疊條形圖和 OfPie 圖表。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

指定條形與柱形在二維圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。- -100%：最大間距（條形完全分離）。- 0%：條形並排放置，無重疊或間距。- 100%：最大重疊（條形彼此完全重疊）。此屬性為可讀寫 byte。

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


**傳回值:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

指定條形與柱形在二維圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。- -100%：最大間距（條形完全分離）。- 0%：條形並排放置，無重疊或間距。- 100%：最大重疊（條形彼此完全重疊）。此屬性為可讀寫 byte。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

指定餅中餅或條形圖的第二個餅或條的大小，作為第一個餅大小的百分比（可在 5% 到 200% 之間）。可讀寫 int。

**傳回值:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

指定餅中餅或條形圖的第二個餅或條的大小，作為第一個餅大小的百分比（可在 5% 到 200% 之間）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

指定一個值，用於決定在餅中餅或條形圖中哪些資料點屬於第二個餅或條。與 PieSplitBy 屬性一起使用。可讀寫 double。

**傳回值:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

指定一個值，用於決定在餅中餅或條形圖中哪些資料點屬於第二個餅或條。與 PieSplitBy 屬性一起使用。可讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

指定如何決定在餅中餅或條形圖中哪些資料點屬於第二個餅或條。可讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**傳回值:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

指定如何決定在餅中餅或條形圖中哪些資料點屬於第二個餅或條。可讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

具有自訂切分的餅中餅或條形圖的自訂切分資訊。包含應在第二個餅或條中繪製的資料點。唯讀 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

**傳回值:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

指定環形圖中孔的大小（可為繪圖區大小的 10% 到 90%）。可讀寫 byte。

**傳回值:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

指定環形圖中孔的大小（可為繪圖區大小的 10% 到 90%）。可讀寫 byte。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

指定泡泡圖的比例係數（可為預設大小的 0% 到 300%）。可讀寫 int。

**傳回值:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

指定泡泡圖的比例係數（可為預設大小的 0% 到 300%）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

指定 HiLowLines 格式。HiLowLines 會套用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 與 VolumeOpenHiLowClose 圖表類型。

**傳回值:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

指定在泡泡圖上如何表示泡泡大小值。可讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**傳回值:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

指定在泡泡圖上如何表示泡泡大小值。可讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |