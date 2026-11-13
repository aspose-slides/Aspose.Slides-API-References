---
title: IChartSeriesGroup
second_title: Aspose.Slides for Java API 參考
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

1) 請參閱 ChartSeriesGroupCollection 類別和 CombinableSeriesTypesGroup 列舉的摘要與說明。2) 系列群組包含一些對群組中每個系列共通的系列屬性（"series group properties"）。"Series group properties" 在 ChartSeriesGroup 類別中是可讀寫的。每個 "series group properties" 可在 ChartSeries 類別中有唯讀的投影。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 傳回此系列群組的類型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此群組的系列是否繪製在次坐標軸上。 |
| [getSeries()](#getSeries--) | 傳回圖表系列的唯讀集合。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供對折線圖或股票圖的上/下棒的存取。 |
| [getGapWidth()](#getGapWidth--) | 取得或設定條形或柱狀群集之間的間距，以條形或柱狀寬度的百分比表示。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 取得或設定條形或柱狀群集之間的間距，以條形或柱狀寬度的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 取得或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 取得或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 取得或設定第一個圓餅圖或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 取得或設定第一個圓餅圖或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記具有不同的顏色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每個資料標記具有不同的顏色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 若圖表有系列線則為 true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 若圖表有系列線則為 true。 |
| [getOverlap()](#getOverlap--) | 指定條形和柱狀在 2-D 圖表上的重疊程度，以百分比表示（-100% 到 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定條形和柱狀在 2-D 圖表上的重疊程度，以百分比表示（-100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定餅中餅或條中條圖之第二個圓餅或條的大小，以第一個圓餅大小的百分比表示（可介於 5% 到 200% 之間）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定餅中餅或條中條圖之第二個圓餅或條的大小，以第一個圓餅大小的百分比表示（可介於 5% 到 200% 之間）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用於決定哪些資料點位於餅中餅或條中條圖之第二個圓餅或條的值。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定用於決定哪些資料點位於餅中餅或條中條圖之第二個圓餅或條的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何決定哪些資料點位於餅中餅或條中條圖之第二個圓餅或條。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何決定哪些資料點位於餅中餅或條中條圖之第二個圓餅或條。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 餅中餅或條中條圖的自訂分割資訊（使用自訂分割時）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定環形圖中孔的大小（可介於繪圖區大小的 10% 到 90% 之間）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定環形圖中孔的大小（可介於繪圖區大小的 10% 到 90% 之間）。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 格式。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖上氣泡大小值的呈現方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定氣泡圖上氣泡大小值的呈現方式。 |

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

指示此群組的系列是否繪製在次坐標軸上。唯讀布林值。

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

提供對折線圖或股票圖的上/下棒的存取。唯讀 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**傳回：**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

取得或設定條形或柱狀群集之間的間距，以條形或柱狀寬度的百分比表示。值必須介於 0 到 500。可讀寫 int。

--------------------

此屬性適用於以下類型的系列：所有條形和柱狀子類型，[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)，[ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)，[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)，[ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)，[ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)，[ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)。

**傳回：**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

取得或設定條形或柱狀群集之間的間距，以條形或柱狀寬度的百分比表示。值必須介於 0 到 500。可讀寫 int。

--------------------

此屬性適用於以下類型的系列：所有條形和柱狀子類型，[ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie)，[ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie)，[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)，[ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)，[ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)，[ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

取得或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。值必須介於 0 到 500。可讀寫 int。

--------------------

此屬性適用於以下類型的系列：3D 條形和柱狀子類型，[ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)，[ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)，[ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)，[ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)。

**傳回：**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

取得或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。值必須介於 0 到 500。可讀寫 int。

--------------------

此屬性適用於以下類型的系列：3D 條形和柱狀子類型，[ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D)，[ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D)，[ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D)，[ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

取得或設定第一個圓餅圖或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。可讀寫 int。

**傳回：**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

取得或設定第一個圓餅圖或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

指定系列中的每個資料標記具有不同的顏色。可讀寫布林值。

**傳回：**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

指定系列中的每個資料標記具有不同的顏色。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

若圖表有系列線則為 true。適用於堆疊條形和 OfPie 圖表。可讀寫布林值。

**傳回：**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

若圖表有系列線則為 true。適用於堆疊條形和 OfPie 圖表。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

指定條形和柱狀在 2-D 圖表上的重疊程度，以百分比表示（-100% 到 100%）。- -100%：最大間距（條形完全分離）。- 0%：條形並排且無重疊或間距。- 100%：最大重疊（條形完全重疊）。此屬性為可讀寫 byte。

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

指定條形和柱狀在 2-D 圖表上的重疊程度，以百分比表示（-100% 到 100%）。- -100%：最大間距（條形完全分離）。- 0%：條形並排且無重疊或間距。- 100%：最大重疊（條形完全重疊）。此屬性為可讀寫 byte。

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

指定餅中餅或條中條圖之第二個圓餅或條的大小，以第一個圓餅大小的百分比表示（可介於 5% 到 200% 之間）。可讀寫 int。

**傳回：**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

指定餅中餅或條中條圖之第二個圓餅或條的大小，以第一個圓餅大小的百分比表示（可介於 5% 到 200% 之間）。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

指定用於決定哪些資料點位於餅中餅或條中條圖之第二個圓餅或條的值。與 PieSplitBy 屬性一起使用。可讀寫 double。

**傳回：**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

指定用於決定哪些資料點位於餅中餅或條中條圖之第二個圓餅或條的值。與 PieSplitBy 屬性一起使用。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

指定如何判斷哪些資料點位於餅中餅或條中條圖之第二個圓餅或條。可讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**傳回：**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

指定如何判斷哪些資料點位於餅中餅或條中條圖之第二個圓餅或條。可讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

餅中餅或條中條圖的自訂分割資訊（使用自訂分割時）。包含應在第二個圓餅或條中繪製的資料點。唯讀 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

**傳回：**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

指定環形圖中孔的大小（可介於繪圖區大小的 10% 到 90% 之間）。可讀寫 byte。

**傳回：**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

指定環形圖中孔的大小（可介於繪圖區大小的 10% 到 90% 之間）。可讀寫 byte。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。可讀寫 int。

**傳回：**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。可讀寫 int。

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

指定氣泡圖上氣泡大小值的呈現方式。可讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**傳回：**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

指定氣泡圖上氣泡大小值的呈現方式。可讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |