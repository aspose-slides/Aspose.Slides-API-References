---
title: ChartSeriesGroup
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示系列的群組。
type: docs
url: /zh-hant/com.aspose.slides/chartseriesgroup/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject  
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

表示系列的群組。

--------------------

1) 請參閱 ChartSeriesGroupCollection 類別和 CombinableSeriesTypesGroup 列舉的摘要與備註。  
2) 系列群組包含一些對群組中每個系列共通的系列屬性（「series group properties」）。ChartSeriesGroup 類別中的「Series group properties」為讀寫。每個「series group properties」在 ChartSeries 類別中可以有唯讀的投影。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回此系列群組的類型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此群組的系列是否繪製於次要軸上。 |
| [getSeries()](#getSeries--) | 返回系列的集合。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供對折線圖或股票圖的上/下棒的存取。 |
| [getGapWidth()](#getGapWidth--) | 指定條形或柱形叢集之間的間距，以條形或柱形寬度的百分比表示。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 指定條形或柱形叢集之間的間距，以條形或柱形寬度的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 返回或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 返回或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 取得或設定第一個圓形或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 取得或設定第一個圓形或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定環形圖中孔的大小（可介於繪圖區大小的 0% 到 90% 之間）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定環形圖中孔的大小（可介於繪圖區大小的 0% 到 90% 之間）。 |
| [getOverlap()](#getOverlap--) | 指定條形與柱形在 2D 圖表上的重疊程度，以百分比表示（-100% 到 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定條形與柱形在 2D 圖表上的重疊程度，以百分比表示（-100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定餅餅圖或條餅圖中第二個圓形或條形的大小，以第一個圓形大小的百分比表示（可介於 5% 到 200% 之間）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定餅餅圖或條餅圖中第二個圓形或條形的大小，以第一個圓形大小的百分比表示（可介於 5% 到 200% 之間）。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖上氣泡大小值的表示方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定氣泡圖上氣泡大小值的表示方式。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用於判斷哪些資料點屬於餅餅圖或條餅圖中第二個圓形或條形的值。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定用於判斷哪些資料點屬於餅餅圖或條餅圖中第二個圓形或條形的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何判斷哪些資料點屬於餅餅圖或條餅圖中第二個圓形或條形。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何判斷哪些資料點屬於餅餅圖或條餅圖中第二個圓形或條形。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中每個資料標記具有不同的顏色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中每個資料標記具有不同的顏色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 若圖表有系列線則返回 true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 若圖表有系列線則返回 true。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 格式。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 具有自訂切割的餅餅圖或條餅圖的自訂切割資訊。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父圖表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |

### getType() {#getType--}
```
public final int getType()
```

返回此系列群組的類型。唯讀 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**返回：**  
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

指示此群組的系列是否繪製於次要軸上。唯讀 boolean。

**返回：**  
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

返回系列的集合。唯讀 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**返回：**  
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

取得指定索引處的元素。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

提供對折線圖或股票圖的上/下棒的存取。唯讀 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**返回：**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

指定條形或柱形叢集之間的間距，以條形或柱形寬度的百分比表示。讀寫 int。

**返回：**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

指定條形或柱形叢集之間的間距，以條形或柱形寬度的百分比表示。讀寫 int。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

返回或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。讀寫 int。

**返回：**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

返回或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。讀寫 int。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

取得或設定第一個圓形或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。讀寫 int。

**返回：**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

取得或設定第一個圓形或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。讀寫 int。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

指定環形圖中孔的大小（可介於繪圖區大小的 0% 到 90% 之間）。讀寫 byte。

**返回：**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

指定環形圖中孔的大小（可介於繪圖區大小的 0% 到 90% 之間）。讀寫 byte。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

指定條形與柱形在 2-D 圖表上的重疊程度，以百分比表示（-100% 到 100%）。- -100%：最大間距（條形完全分離）。- 0%：條形並排放置，無重疊或間距。- 100%：最大重疊（條形完全重疊）。此屬性為讀寫 byte。

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


**返回：**  
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

指定條形與柱形在 2-D 圖表上的重疊程度，以百分比表示（-100% 到 100%）。- -100%：最大間距（條形完全分離）。- 0%：條形並排放置，無重疊或間距。- 100%：最大重疊（條形完全重疊）。此屬性為讀寫 byte。

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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

指定餅餅圖或條餅圖中第二個圓形或條形的大小，以第一個圓形大小的百分比表示（可介於 5% 到 200% 之間）。讀寫 int。

**返回：**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

指定餅餅圖或條餅圖中第二個圓形或條形的大小，以第一個圓形大小的百分比表示（可介於 5% 到 200% 之間）。讀寫 int。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

指定氣泡圖上氣泡大小值的表示方式。讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**返回：**  
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

指定氣泡圖上氣泡大小值的表示方式。讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

指定用於判斷哪些資料點屬於餅餅圖或條餅圖中第二個圓形或條形的值。與 PieSplitBy 屬性一起使用。讀寫 double。

**返回：**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

指定用於判斷哪些資料點屬於餅餅圖或條餅圖中第二個圓形或條形的值。與 PieSplitBy 屬性一起使用。讀寫 double。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

指定如何判斷哪些資料點屬於餅餅圖或條餅圖中第二個圓形或條形。讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**返回：**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

指定如何判斷哪些資料點屬於餅餅圖或條餅圖中第二個圓形或條形。讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

指定系列中每個資料標記具有不同的顏色。讀寫 boolean。

**返回：**  
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

指定系列中每個資料標記具有不同的顏色。讀寫 boolean。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

若圖表具有系列線則返回 true。適用於堆疊條形圖和 OfPie 圖。讀寫 boolean。

**返回：**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

若圖表具有系列線則返回 true。適用於堆疊條形圖和 OfPie 圖。讀寫 boolean。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

指定 HiLowLines 格式。HiLowLines 於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 與 VolumeOpenHiLowClose 圖表類型中使用。

**返回：**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。讀寫 int。

**返回：**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。讀寫 int。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

具有自訂切割的餅餅圖或條餅圖的自訂切割資訊。包含應在餅餅圖或條餅圖第二個圓形或條形中繪製的資料點。唯讀 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

**返回：**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**返回：**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回：**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**  
[IPresentation](../../com.aspose.slides/ipresentation)