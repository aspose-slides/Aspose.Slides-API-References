---
title: ChartSeriesGroup
second_title: Aspose.Slides for Java API 參考
description: 表示系列的群組。
type: docs
url: /zh-hant/com.aspose.slides/chartseriesgroup/
---
**繼承:**
java.lang.Object

**已實作的介面:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

表示系列的組。

--------------------

1) 請參閱 ChartSeriesGroupCollection 類別和 CombinableSeriesTypesGroup 列舉的摘要與備註。 2) 系列組包含一些對組內每個系列共通的系列屬性（「series group properties」）。「Series group properties」在 ChartSeriesGroup 類別中是可讀寫的。每個「series group properties」可以在 ChartSeries 類別中有唯讀的投影。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 返回此系列組的類型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此組的系列是否繪製在次要座標軸上。 |
| [getSeries()](#getSeries--) | 返回系列的集合。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供對折線或 Stock-chart 的上下條的存取。 |
| [getGapWidth()](#getGapWidth--) | 取得或設定條或欄叢集之間的間距，以條或欄寬的百分比表示。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 取得或設定條或欄叢集之間的間距，以條或欄寬的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 取得或設定三維圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 取得或設定三維圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 取得或設定第一個圓形或甜甜圈圖切片的角度，單位為度（從上方起順時針，0 到 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 取得或設定第一個圓形或甜甜圈圖切片的角度，單位為度（從上方起順時針，0 到 360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定甜甜圈圖中孔的大小（可介於圖表區域大小的 0% 到 90% 之間）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定甜甜圈圖中孔的大小（可介於圖表區域大小的 0% 到 90% 之間）。 |
| [getOverlap()](#getOverlap--) | 指定條與欄在二維圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定條與欄在二維圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定餅中餅或餅中條圖的第二個圓形或條的大小，以第一個圓形的大小百分比表示（可介於 5% 到 200% 之間）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定餅中餅或餅中條圖的第二個圓形或條的大小，以第一個圓形的大小百分比表示（可介於 5% 到 200% 之間）。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖上氣泡大小值的呈現方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定氣泡圖上氣泡大小值的呈現方式。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定一個值，用於決定哪些資料點位於餅中餅或餅中條圖的第二個圓形或條中。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定一個值，用於決定哪些資料點位於餅中餅或餅中條圖的第二個圓形或條中。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何決定哪些資料點位於餅中餅或餅中條圖的第二個圓形或條中。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何決定哪些資料點位於餅中餅或餅中條圖的第二個圓形或條中。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記具有不同的顏色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每個資料標記具有不同的顏色。 |
| [hasSeriesLines()](#hasSeriesLines--) | True if chart has series lines. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True if chart has series lines. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 格式。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的縮放係數（可介於預設大小的 0% 到 300% 之間）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定氣泡圖的縮放係數（可介於預設大小的 0% 到 300% 之間）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 自訂分割資訊，針對具有自訂分割的餅中餅或餅中條圖。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父圖表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |

### getType() {#getType--}
```
public final int getType()
```

返回此系列組的類型。唯讀 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**返回:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

指示此組的系列是否繪製在次要座標軸上。唯讀 boolean。

**返回:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

返回系列的集合。唯讀 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**返回:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

提供對折線或 Stock-chart 的上下條的存取。唯讀 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**返回:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

取得或設定條或欄叢集之間的間距，以條或欄寬的百分比表示。值必須介於 0 到 500。可讀寫 int。

--------------------

此屬性適用於以下類型的系列：Bar 子類型（另請參閱 [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) 方法）、Column 子類型（另請參閱 [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) 方法）、[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)、[ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)、[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)、[ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)、[ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)、[ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)。

**返回:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

取得或設定條或欄叢集之間的間距，以條或欄寬的百分比表示。值必須介於 0 到 500。可讀寫 int。

--------------------

此屬性適用於以下類型的系列：Bar 子類型（另請參閱 [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) 方法）、Column 子類型（另請參閱 [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) 方法）、[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)、[ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)、[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)、[ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)、[ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)、[ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

取得或設定三維圖表中資料系列之間的距離，以標記寬度的百分比表示。值必須介於 0 到 500。可讀寫 int。

--------------------

此屬性適用於以下類型的系列：3D Bar 與 Column 子類型（另請參閱 [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) 方法）、[ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)、[ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)、[ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)、[ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)。

**返回:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

取得或設定三維圖表中資料系列之間的距離，以標記寬度的百分比表示。值必須介於 0 到 500。可讀寫 int。

--------------------

此屬性適用於以下類型的系列：3D Bar 與 Column 子類型（另請參閱 [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) 方法）、[ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)、[ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)、[ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)、[ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

取得或設定第一個圓形或甜甜圈圖切片的角度，單位為度（從上方起順時針，0 到 360 度）。可讀寫 int。

**返回:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

取得或設定第一個圓形或甜甜圈圖切片的角度，單位為度（從上方起順時針，0 到 360 度）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

指定甜甜圈圖中孔的大小（可介於圖表區域大小的 0% 到 90% 之間）。可讀寫 byte。

**返回:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

指定甜甜圈圖中孔的大小（可介於圖表區域大小的 0% 到 90% 之間）。可讀寫 byte。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

指定條與欄在二維圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。-100%：最大間距（條完全分離）。0%：條並排且不重疊亦不間距。100%：最大重疊（條完全重疊）。此屬性為可讀寫 byte。

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

指定條與欄在二維圖表上的重疊程度，以百分比表示（從 -100% 到 100%）。-100%：最大間距（條完全分離）。0%：條並排且不重疊亦不間距。100%：最大重疊（條完全重疊）。此屬性為可讀寫 byte。

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
public final int getSecondPieSize()
```

指定餅中餅或餅中條圖的第二個圓形或條的大小，以第一個圓形的大小百分比表示（可介於 5% 到 200% 之間）。可讀寫 int。

**返回:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

指定餅中餅或餅中條圖的第二個圓形或條的大小，以第一個圓形的大小百分比表示（可介於 5% 到 200% 之間）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

指定氣泡圖上氣泡大小值的呈現方式。可讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**返回:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

指定氣泡圖上氣泡大小值的呈現方式。可讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

指定一個值，用於決定哪些資料點位於餅中餅或餅中條圖的第二個圓形或條中。與 PieSplitBy 屬性一起使用。可讀寫 double。

**返回:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

指定一個值，用於決定哪些資料點位於餅中餅或餅中條圖的第二個圓形或條中。與 PieSplitBy 屬性一起使用。可讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

指定如何決定哪些資料點位於餅中餅或餅中條圖的第二個圓形或條中。可讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**返回:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

指定如何決定哪些資料點位於餅中餅或餅中條圖的第二個圓形或條中。可讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

指定系列中的每個資料標記具有不同的顏色。可讀寫 boolean。

**返回:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

指定系列中的每個資料標記具有不同的顏色。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

True if chart has series lines. Applied to stacked bar and OfPie charts. 可讀寫 boolean。

**返回:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True if chart has series lines. Applied to stacked bar and OfPie charts. 可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

指定 HiLowLines 格式。HiLowLines 應用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 與 VolumeOpenHiLowClose 圖表類型。

**返回:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

指定氣泡圖的縮放係數（可介於預設大小的 0% 到 300% 之間）。可讀寫 int。

**返回:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

指定氣泡圖的縮放係數（可介於預設大小的 0% 到 300% 之間）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

自訂分割資訊，針對具有自訂分割的餅中餅或餅中條圖。包含應繪製在第二個圓形或條中的資料點。唯讀 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

**返回:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**返回:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)