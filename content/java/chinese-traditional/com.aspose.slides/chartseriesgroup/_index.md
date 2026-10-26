---
title: ChartSeriesGroup
second_title: Aspose.Slides for Java API 參考文件
description: 表示系列的集合。
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

表示系列的集合。

--------------------

1) 請參閱 ChartSeriesGroupCollection 類別和 CombinableSeriesTypesGroup 列舉的摘要與說明。2) 系列的群組包含一些對該群組中每個系列共同的屬性（「系列群組屬性」）。ChartSeriesGroup 類別中的「系列群組屬性」是可讀寫的。每個「系列群組屬性」在 ChartSeries 類別中可以有唯讀的投射。
## Methods

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 傳回此系列群組的類型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指出此群組的系列是否繪製在次坐標軸上。 |
| [getSeries()](#getSeries--) | 傳回系列的集合。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getUpDownBars()](#getUpDownBars--) | 提供對折線圖或股票圖的上下柱狀的存取。 |
| [getGapWidth()](#getGapWidth--) | 指定條形或柱狀叢集之間的間距，以條形或柱狀寬度的百分比表示。 |
| [setGapWidth(int value)](#setGapWidth-int-) | 指定條形或柱狀叢集之間的間距，以條形或柱狀寬度的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 傳回或設定 3D 圖表中資料系列之間的距離，單位為標記寬度的百分比。 |
| [setGapDepth(int value)](#setGapDepth-int-) | 傳回或設定 3D 圖表中資料系列之間的距離，單位為標記寬度的百分比。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 取得或設定第一個圓餅圖或環形圖切片的角度，單位為度（從上方順時針，0 至 360 度）。 |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | 取得或設定第一個圓餅圖或環形圖切片的角度，單位為度（從上方順時針，0 至 360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定環形圖中孔的大小（可以是繪圖區大小的 0% 到 90% 之間）。 |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | 指定環形圖中孔的大小（可以是繪圖區大小的 0% 到 90% 之間）。 |
| [getOverlap()](#getOverlap--) | 指定條形與柱狀在 2-D 圖表上重疊的程度，以百分比表示（-100% 至 100%）。 |
| [setOverlap(byte value)](#setOverlap-byte-) | 指定條形與柱狀在 2-D 圖表上重疊的程度，以百分比表示（-100% 至 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定派對派圖或派對條圖中第二個圓餅或條形的大小，作為第一個圓餅大小的百分比（可在 5% 到 200% 之間）。 |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | 指定派對派圖或派對條圖中第二個圓餅或條形的大小，作為第一個圓餅大小的百分比（可在 5% 到 200% 之間）。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖上氣泡大小值的呈現方式。 |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | 指定氣泡圖上氣泡大小值的呈現方式。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用於決定在派對派圖或派對條圖中哪些資料點屬於第二個圓餅或條形的值。 |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | 指定用於決定在派對派圖或派對條圖中哪些資料點屬於第二個圓餅或條形的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何決定在派對派圖或派對條圖中哪些資料點屬於第二個圓餅或條形。 |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | 指定如何決定在派對派圖或派對條圖中哪些資料點屬於第二個圓餅或條形。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記具有不同的顏色。 |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | 指定系列中的每個資料標記具有不同的顏色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 如果圖表有系列線則為 true。 |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | 如果圖表有系列線則為 true。 |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | 指定 HiLowLines 格式。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的比例因子（可為預設大小的 0% 到 300% 之間）。 |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | 指定氣泡圖的比例因子（可為預設大小的 0% 到 300% 之間）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 自訂分割資訊，用於具有自訂分割的派對派圖或派對條圖。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 傳回父圖表。 |
| [getSlide()](#getSlide--) | 傳回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 FillFormat 的父簡報。 |
### getType() {#getType--}
```
public final int getType()
```

傳回此系列群組的類型。唯讀 [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)。

**返回值:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

指出此群組的系列是否繪製在次坐標軸上。唯讀 boolean。

**返回值:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

傳回系列的集合。唯讀 [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)。

**返回值:**
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

**返回值:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

提供對折線圖或股票圖的上下柱狀的存取。唯讀 [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)。

**返回值:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

指定條形或柱狀叢集之間的間距，以條形或柱狀寬度的百分比表示。可讀寫 int。

**返回值:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

指定條形或柱狀叢集之間的間距，以條形或柱狀寬度的百分比表示。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

傳回或設定 3D 圖表中資料系列之間的距離，單位為標記寬度的百分比。可讀寫 int。

**返回值:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

傳回或設定 3D 圖表中資料系列之間的距離，單位為標記寬度的百分比。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

取得或設定第一個圓餅圖或環形圖切片的角度，單位為度（從上方順時針，0 至 360 度）。可讀寫 int。

**返回值:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

取得或設定第一個圓餅圖或環形圖切片的角度，單位為度（從上方順時針，0 至 360 度）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

指定環形圖中孔的大小（可以是繪圖區大小的 0% 到 90% 之間）。可讀寫 byte。

**返回值:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

指定環形圖中孔的大小（可以是繪圖區大小的 0% 到 90% 之間）。可讀寫 byte。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

指定條形與柱狀在 2-D 圖表上重疊的程度，以百分比表示（-100% 至 100%）。-100%：最大間距（條形完全分開）。-0%：條形並排放置，無重疊亦無間距。100%：最大重疊（條形完全覆蓋彼此）。此屬性為可讀寫 byte。

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


**返回值:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

指定條形與柱狀在 2-D 圖表上重疊的程度，以百分比表示（-100% 至 100%）。-100%：最大間距（條形完全分開）。-0%：條形並排放置，無重疊亦無間距。100%：最大重疊（條形完全覆蓋彼此）。此屬性為可讀寫 byte。

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

指定派對派圖或派對條圖中第二個圓餅或條形的大小，作為第一個圓餅大小的百分比（可在 5% 到 200% 之間）。可讀寫 int。

**返回值:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

指定派對派圖或派對條圖中第二個圓餅或條形的大小，作為第一個圓餅大小的百分比（可在 5% 到 200% 之間）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

指定氣泡圖上氣泡大小值的呈現方式。可讀寫 [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)。

**返回值:**
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

指定用於決定在派對派圖或派對條圖中哪些資料點屬於第二個圓餅或條形的值。與 PieSplitBy 屬性一起使用。可讀寫 double。

**返回值:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

指定用於決定在派對派圖或派對條圖中哪些資料點屬於第二個圓餅或條形的值。與 PieSplitBy 屬性一起使用。可讀寫 double。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

指定如何決定在派對派圖或派對條圖中哪些資料點屬於第二個圓餅或條形。可讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**返回值:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

指定如何決定在派對派圖或派對條圖中哪些資料點屬於第二個圓餅或條形。可讀寫 [PieSplitType](../../com.aspose.slides/piesplittype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

指定系列中的每個資料標記具有不同的顏色。可讀寫 boolean。

**返回值:**
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

如果圖表有系列線則為 true。套用於堆疊條形圖與派對派圖。可讀寫 boolean。

**返回值:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

如果圖表有系列線則為 true。套用於堆疊條形圖與派對派圖。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

指定 HiLowLines 格式。HiLowLines 套用於 HiLowClose、OpenHiLowClose、VolumeHiLowClose 與 VolumeOpenHiLowClose 圖表類型。

**返回值:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

指定氣泡圖的比例因子（可為預設大小的 0% 到 300% 之間）。可讀寫 int。

**返回值:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

指定氣泡圖的比例因子（可為預設大小的 0% 到 300% 之間）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

自訂分割資訊，用於具有自訂分割的派對派圖或派對條圖。包含應在第二個圓餅或條形中繪製的資料點。唯讀 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

**返回值:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回值:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

傳回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**返回值:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值:**
[IPresentation](../../com.aspose.slides/ipresentation)