---
title: ChartSeries
second_title: Aspose.Slides for Android via Java API 參考
description: 代表圖表系列。
type: docs
url: /zh-hant/com.aspose.slides/chartseries/
---
**繼承:**  
java.lang.Object  

**全部實作的介面:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

表示圖表系列。  
## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父圖表。 |
| [getExplosion()](#getExplosion--) | 開放的扇形片段與圓餅圖中心的距離，以圓餅直徑的百分比表示。 |
| [setExplosion(int value)](#setExplosion-int-) | 開放的扇形片段與圓餅圖中心的距離，以圓餅直徑的百分比表示。 |
| [getSmooth()](#getSmooth--) | 表示曲線平滑。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 表示曲線平滑。 |
| [getName()](#getName--) | 返回系列名稱。 |
| [getDataPoints()](#getDataPoints--) | 返回此系列的資料點集合。 |
| [getType()](#getType--) | 返回此系列的類型。 |
| [setType(int value)](#setType-int-) | 返回此系列的類型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此系列是否繪製於次坐標軸上。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | 指示此系列是否繪製於次坐標軸上。 |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup。 |
| [getFormat()](#getFormat--) | 返回系列的格式。 |
| [getOrder()](#getOrder--) | 返回系列的順序。 |
| [setOrder(int value)](#setOrder-int-) | 返回系列的順序。 |
| [getLabels()](#getLabels--) | 返回系列的標籤。 |
| [getTrendLines()](#getTrendLines--) | 系列趨勢線集合。 |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | 代表 X 方向的誤差棒。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | 代表 Y 方向的誤差棒。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 代表與此系列相關的圖例項目，唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues。 |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues。 |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues。 |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues。 |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues。 |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues。 |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes。 |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes。 |
| [getMarker()](#getMarker--) | Marker。 |
| [getBar3DShape()](#getBar3DShape--) | 指定 3-D 長條圖系列的形狀。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 指定 3-D 長條圖系列的形狀。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定長條、柱形或氣泡系列在值為負時顏色反轉。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定長條、柱形或氣泡系列在值為負時顏色反轉。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 指定系列的反轉實心顏色。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 返回根據系列索引與圖表樣式自動產生的系列顏色。 |
| [getShowInnerPoints()](#getShowInnerPoints--) | 代表內部點。 |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 代表內部點。 |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 代表異常值點。 |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 代表異常值點。 |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 代表平均標記。 |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 代表平均標記。 |
| [getShowMeanLine()](#getShowMeanLine--) | 代表平均線。 |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 代表平均線。 |
| [getQuartileMethod()](#getQuartileMethod--) | 代表四分位方法。 |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 代表四分位方法。 |
| [getShowConnectorLines()](#getShowConnectorLines--) | 代表連接線。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | 代表連接線。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 代表父類別標籤的版面配置。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 代表父類別標籤的版面配置。 |
| [hasUpDownBars()](#hasUpDownBars--) | 判斷折線圖或股票圖是否具有升降棒。 |
| [getGapWidth()](#getGapWidth--) | 指定長條或柱形叢集之間的間距，以長條或柱形寬度的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 以標記寬度的百分比設定或取得 3D 圖表中資料系列之間的距離。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 以度數指定第一個圓餅或環形圖切片的起始角度（順時針，0-360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定環形圖中心孔的大小（佔繪圖區域大小的 10%-90%）。 |
| [getOverlap()](#getOverlap--) | 指定 2-D 圖表中長條與柱形的重疊比例（-100% 至 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定餅圖中第二個餅或長條的大小，以第一個餅的大小百分比表示（5%-200%）。 |
| [hasSeriesLines()](#hasSeriesLines--) | 判斷此系列及相關系列是否有系列線。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖中氣泡大小值的表示方式。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用於決定哪些資料點屬於餅圖/條圖第二餅或第二條的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何決定哪些資料點屬於餅圖/條圖第二餅或第二條。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 針對具有自訂分割的餅圖/條圖之自訂分割資訊。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記使用不同的顏色。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的比例因子（0-300% 預設大小）。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |

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

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

開放的扇形片段與圓餅圖中心的距離，以圓餅直徑的百分比表示。可讀寫 int。

**返回:**  
int  

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

開放的扇形片段與圓餅圖中心的距離，以圓餅直徑的百分比表示。可讀寫 int。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |  

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

代表曲線平滑。對於折線圖或散佈圖（由線連接）若已開啟曲線平滑則返回 true。僅適用於折線圖與散佈圖。可讀寫 boolean。

**返回:**  
boolean  

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

代表曲線平滑。對於折線圖或散佈圖（由線連接）若已開啟曲線平滑則返回 true。僅適用於折線圖與散佈圖。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |  

### getName() {#getName--}
```
public final IStringChartValue getName()
```

返回系列名稱。唯讀 [IStringChartValue](../../com.aspose.slides/istringchartvalue)。

**返回:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)  

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

返回此系列的資料點集合。唯讀 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)。

**返回:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  

### getType() {#getType--}
```
public final int getType()
```

返回此系列的類型。可讀寫 [ChartType](../../com.aspose.slides/charttype)。

**返回:**  
int  

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

返回此系列的類型。可讀寫 [ChartType](../../com.aspose.slides/charttype)。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |  

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

指示此系列是否繪製於次坐標軸上。可讀寫 boolean。

**返回:**  
boolean  

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

指示此系列是否繪製於次坐標軸上。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |  

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup。唯讀 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)。

**返回:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)  

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

返回系列的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**返回:**  
[IFormat](../../com.aspose.slides/iformat)  

### getOrder() {#getOrder--}
```
public final int getOrder()
```

返回系列的順序。可讀寫 int。

**返回:**  
int  

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

返回系列的順序。可讀寫 int。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |  

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

返回系列的標籤。唯讀 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)。

**返回:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)  

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

系列趨勢線集合。唯讀 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。

--------------------

趨勢線在未堆疊的 2-D 面積、長條、柱形、折線、股票、XY（散佈）以及氣泡圖中皆可使用。堆疊或 3-D 圖表、雷達圖、餅圖、曲面圖或環形圖則不提供趨勢線。

**返回:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)  

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

代表 X 方向的誤差棒。唯讀 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

X 方向的誤差棒適用於面積圖、長條圖、散佈圖與氣泡圖。其他圖表類型（包括 3D 圖表）會回傳 null。若使用自訂值，請透過 DataPoints 集合並搭配 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性指定值。

**返回:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

代表 Y 方向的誤差棒。唯讀 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

Y 方向的誤差棒適用於面積圖、長條圖、折線圖、散佈圖與氣泡圖。其他圖表類型（包括 3D 圖表）會回傳 null。若使用自訂值，請透過 DataPoints 集合並搭配 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性指定值。

**返回:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

代表與此系列相關的圖例項目，唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)  

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues。可讀寫 String。

**返回:**  
java.lang.String  

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues。可讀寫 String。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |  

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues。可讀寫 String。

**返回:**  
java.lang.String  

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues。可讀寫 String。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |  

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues。可讀寫 String。

**返回:**  
java.lang.String  

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues。可讀寫 String。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |  

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes。可讀寫 String。

**返回:**  
java.lang.String  

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes。可讀寫 String。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |  

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker。唯讀 [IMarker](../../com.aspose.slides/imarker)。

**返回:**  
[IMarker](../../com.aspose.slides/imarker)  

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

指定 3-D 長條圖系列的形狀。變更此屬性值可能會自動變更系列的類型。可讀寫 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**返回:**  
int  

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

指定 3-D 長條圖系列的形狀。變更此屬性值可能會自動變更系列的類型。可讀寫 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |  

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

指定長條、柱形或氣泡系列在值為負時顏色反轉。可讀寫 boolean。

**返回:**  
boolean  

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

指定長條、柱形或氣泡系列在值為負時顏色反轉。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |  

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

指定系列的反轉實心顏色。若要套用此顏色設定，請將系列格式的 FillType 設為 FillType.Solid。可讀寫 [ColorFormat](../../com.aspose.slides/colorformat)。

**返回:**  
[IColorFormat](../../com.aspose.slides/icolorformat)  

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

返回根據系列索引與圖表樣式自動產生的系列顏色。若 FillType 為 NotDefined，則預設使用此顏色。

**返回:**  
java.lang.Integer - The java.lang.Integer object.  

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

代表內部點。若在 BoxAndWhisker 圖表上顯示內部點則返回 true。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**返回:**  
boolean  

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

代表內部點。若在 BoxAndWhisker 圖表上顯示內部點則返回 true。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |  

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

代表異常值點。若在 BoxAndWhisker 圖表上顯示異常值點則返回 true。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**返回:**  
boolean  

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

代表異常值點。若在 BoxAndWhisker 圖表上顯示異常值點則返回 true。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |  

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

代表平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則返回 true。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**返回:**  
boolean  

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

代表平均標記。若在 BoxAndWhisker 圖表上顯示平均標記則返回 true。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |  

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

代表平均線。若在 BoxAndWhisker 圖表上顯示平均線則返回 true。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**返回:**  
boolean  

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

代表平均線。若在 BoxAndWhisker 圖表上顯示平均線則返回 true。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |  

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

代表四分位方法。僅適用於 BoxAndWhisker 圖表。

**返回:**  
int  

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

代表四分位方法。僅適用於 BoxAndWhisker 圖表。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |  

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

代表連接線。僅適用於 Waterfall 圖表。

**返回:**  
boolean  

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

代表連接線。僅適用於 Waterfall 圖表。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |  

### getParentLabelLayout() {#getParentLabelLayout--}
```
{
```


代表父類別標籤的版面配置。僅適用於 Treemap 圖表。

**返回:**  
int  

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

代表父類別標籤的版面配置。僅適用於 Treemap 圖表。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |  

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

判斷折線圖或股票圖是否具有升降棒。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射。因此此屬性為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 可讀寫屬性變更值，或使用 ParentSeriesGroup.UpDownBars 屬性設定升降棒格式。唯讀 boolean。

--------------------

此屬性為 ParentSeriesGroup.UpDownBars.HasUpDownBars 的投射。

**返回:**  
boolean  

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

指定長條或柱形叢集之間的間距，以長條或柱形寬度的百分比表示。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射。因此此屬性為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.GapWidth 可讀寫屬性變更值。唯讀 int。

--------------------

此屬性為 ParentSeriesGroup.GapWidth 的投射。

**返回:**  
int  

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

以標記寬度的百分比設定或取得 3D 圖表中資料系列之間的距離。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射。因此此屬性為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.GapDepth 可讀寫屬性變更值。唯讀 int。

--------------------

此屬性為 ParentSeriesGroup.GapDepth 的投射。

**返回:**  
int  

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

指定第一個圓餅或環形圖切片的起始角度，以度數表示（順時針，0-360 度）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射。因此此屬性為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.FirstSliceAngle 可讀寫屬性變更值。唯讀 int。

--------------------

此屬性為 ParentSeriesGroup.FirstSliceAngle 的投射。

**返回:**  
int  

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

指定環形圖中心孔的大小（可介於繪圖區域大小的 10%-90% 之間）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射。因此此屬性為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.DoughnutHoleSize 可讀寫屬性變更值。唯讀 byte。

--------------------

此屬性為 ParentSeriesGroup.DoughnutHoleSize 的投射。

**返回:**  
byte  

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

指定長條與柱形在 2-D 圖表上的重疊比例，以百分比表示（-100% 至 100%）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列，為對應群組屬性的投射，故為唯讀。若需變更值，請使用 ParentSeriesGroup.Overlap 可讀寫屬性。唯讀 byte。

--------------------

Overlap 以百分比表示長條與柱形之間的重疊或間距程度：-100% 為最大間距（完全分離），0% 為並排不重疊亦不留間距，100% 為最大重疊（完全重疊）。此屬性為 ParentSeriesGroup.Overlap 的投射。

**返回:**  
byte  

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

指定餅圖或條形圖的第二餅/第二條的大小，以第一個餅的大小百分比表示（5%-200%）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射。因此此屬性為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.SecondPieSize 可讀寫屬性變更值。唯讀 int。

--------------------

此屬性為 ParentSeriesGroup.SecondPieSize 的投射。

**返回:**  
int  

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

判斷此系列及相關系列是否具有系列線。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射，故為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.HasSeriesLines 可讀寫屬性變更值，或使用 ParentSeriesGroup.SeriesLinesFormat 屬性設定系列線格式。唯讀 boolean。

--------------------

此屬性為 ParentSeriesGroup.HasSeriesLines 的投射。

**返回:**  
boolean  

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

指定氣泡圖上氣泡大小值的表示方式。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射，故為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.BubbleSizeRepresentation 可讀寫屬性變更值。

--------------------

此屬性為 ParentSeriesGroup.BubbleSizeRepresentation 的投射。

**返回:**  
int  

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

指定用於決定哪些資料點屬於餅圖/條圖第二餅或第二條的值，與 PieSplitBy 屬性共同使用。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射，故為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.PieSplitPosition 可讀寫屬性變更值。唯讀 double。

--------------------

此屬性為 ParentSeriesGroup.PieSplitPosition 的投射。

**返回:**  
double  

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

指定如何決定哪些資料點屬於餅圖/條圖第二餅或第二條。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射，故為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.PieSplitBy 可讀寫屬性變更值。唯讀 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) 此屬性為 ParentSeriesGroup.PieSplitBy 的投射。2) 若屬性值為 PieSplitType.Custom，則可透過 ParentSeriesGroup.PieSplitCustomPoints 屬性定義自訂分割資訊。

**返回:**  
int  

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

針對具自訂分割之餅圖/條圖的自訂分割資訊，包含應在第二餅或第二條中呈現的資料點。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射，唯讀 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

--------------------

此屬性為 ParentSeriesGroup.PieSplitCustomPoints 的投射。

**返回:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)  

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

指定系列中的每個資料標記使用不同的顏色。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射，故為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.IsColorVaried 可讀寫屬性變更值。唯讀 boolean。

--------------------

此屬性為 ParentSeriesGroup.IsColorVaried 的投射。

**返回:**  
boolean  

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

指定氣泡圖的比例因子（0-300% 預設大小）。此屬性不僅屬於本系列，亦屬於父系列群組的所有系列——屬於對應群組屬性的投射，故為唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組，並使用 ParentSeriesGroup.BubbleSizeScale 可讀寫屬性變更值。

--------------------

此屬性為 ParentSeriesGroup.BubbleSizeScale 的投射。

**返回:**  
int  

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