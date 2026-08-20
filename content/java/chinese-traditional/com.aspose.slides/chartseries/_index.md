---
title: ChartSeries
second_title: Aspose.Slides for Java API 參考
description: 表示圖表系列。
type: docs
url: /zh-hant/com.aspose.slides/chartseries/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

代表一個圖表系列。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父圖表。 |
| [getExplosion()](#getExplosion--) | 從圓餅圖中心至打開的餅片的距離以圓餅直徑的百分比表示。 |
| [setExplosion(int value)](#setExplosion-int-) | 從圓餅圖中心至打開的餅片的距離以圓餅直徑的百分比表示。 |
| [getSmooth()](#getSmooth--) | 表示曲線平滑。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 表示曲線平滑。 |
| [getName()](#getName--) | 返回系列名稱。 |
| [getDataPoints()](#getDataPoints--) | 返回此系列的資料點集合。 |
| [getType()](#getType--) | 返回此系列的類型。 |
| [setType(int value)](#setType-int-) | 返回此系列的類型。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此系列是否繪製於次要軸上。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | 指示此系列是否繪製於次要軸上。 |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup。 |
| [getFormat()](#getFormat--) | 返回系列的格式。 |
| [getOrder()](#getOrder--) | 返回系列的順序。 |
| [setOrder(int value)](#setOrder-int-) | 返回系列的順序。 |
| [getLabels()](#getLabels--) | 返回系列的標籤。 |
| [getTrendLines()](#getTrendLines--) | 系列趨勢線的集合。 |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | 表示 X 方向的系列誤差棒。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | 表示 Y 方向的系列誤差棒。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 表示與此系列相關的圖例項目 唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues。 |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues。 |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues。 |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues。 |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues。 |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues。 |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes。 |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes。 |
| [getMarker()](#getMarker--) | Marker。 |
| [getBar3DShape()](#getBar3DShape--) | 指定 3D 柱狀圖系列的形狀。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 指定 3D 柱狀圖系列的形狀。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定如果值為負，柱形、列形或氣泡系列應反轉其顏色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定如果值為負，柱形、列形或氣泡系列應反轉其顏色。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 指定系列的實體顏色反轉。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 根據系列索引和圖表樣式返回系列的自動顏色。 |
| [getShowInnerPoints()](#getShowInnerPoints--) | 表示內部點。 |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 表示內部點。 |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 表示離群點。 |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 表示離群點。 |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 表示平均標記。 |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 表示平均標記。 |
| [getShowMeanLine()](#getShowMeanLine--) | 表示平均線。 |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 表示平均線。 |
| [getQuartileMethod()](#getQuartileMethod--) | 表示四分位方法。 |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 表示四分位方法。 |
| [getShowConnectorLines()](#getShowConnectorLines--) | 表示連接線。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | 表示連接線。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 表示父類別標籤的佈局。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 表示父類別標籤的佈局。 |
| [hasUpDownBars()](#hasUpDownBars--) | 決定折線圖或股票圖是否具有上/下柱狀。 |
| [getGapWidth()](#getGapWidth--) | 指定柱狀或列狀叢集之間的間距，以柱或列寬的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 返回或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 指定第一個圓餅或甜甜圈圖切片的角度，單位為度（順時針從上方，0 到 360 度）。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定甜甜圈圖中孔的大小（可為繪圖區大小的 10% 到 90%）。 |
| [getOverlap()](#getOverlap--) | 指定在 2D 圖表上柱狀與列狀的重疊程度，以百分比表示（從 -100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定餅中餅或餅中柱圖的第二個餅或柱的大小，以第一個餅的大小百分比表示（可在 5% 到 200% 之間）。 |
| [hasSeriesLines()](#hasSeriesLines--) | 決定此系列及相關系列是否有系列線。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖上氣泡大小值的表示方式。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定一個值，用於確定在餅中餅或餅中柱圖中哪些資料點屬於第二個餅或柱。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何確定在餅中餅或餅中柱圖中哪些資料點屬於第二個餅或柱。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 自訂拆分資訊，用於具有自訂拆分的餅中餅或餅中柱圖。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記具有不同的顏色。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的縮放因子（可為預設大小的 0% 到 300%）。 |
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

從圓餅圖中心至打開的餅片的距離以圓餅直徑的百分比表示。可讀寫 int。

**返回:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

從圓餅圖中心至打開的餅片的距離以圓餅直徑的百分比表示。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

表示曲線平滑。若對折線圖或散佈圖的線條啟用曲線平滑則為 true。僅適用於折線圖與由線條連接的散佈圖。可讀寫 boolean。

**返回:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

表示曲線平滑。若對折線圖或散佈圖的線條啟用曲線平滑則為 true。僅適用於折線圖與由線條連接的散佈圖。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

指示此系列是否繪製於次要軸上。可讀寫 boolean。

**返回:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

指示此系列是否繪製於次要軸上。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
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
| 參數 | 類型 | 說明 |
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

系列趨勢線的集合。唯讀 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。

--------------------

趨勢線在未堆疊的 2-D 面積、柱狀、列狀、折線、股票、XY（散佈）和氣泡圖的資料系列中可用（非 null）。在任何堆疊或 3-D 圖表類型中皆不可用。雷達圖、圓餅圖、曲面圖或甜甜圈圖亦不可用。

**返回:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

表示 X 方向的系列誤差棒。唯讀 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

具有 X 方向的誤差棒適用於面積圖、柱狀圖、散佈圖和氣泡圖系列。對於其他圖表類型（包括 3D 圖表）此屬性返回 null。如需自訂值，請使用 DataPoints 集合指定值（使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性）。

**返回:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

表示 Y 方向的系列誤差棒。唯讀 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

具有 Y 方向的誤差棒適用於面積圖、柱狀圖、折線圖、散佈圖和氣泡圖系列。對於其他圖表類型（包括 3D 圖表）此屬性返回 null。如需自訂值，請使用 DataPoints 集合指定值（使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性）。

**返回:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

表示與此系列相關的圖例項目 唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

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
| 參數 | 類型 | 說明 |
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
| 參數 | 類型 | 說明 |
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
| 參數 | 類型 | 說明 |
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
| 參數 | 類型 | 說明 |
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

指定 3D 柱狀圖系列的形狀。變更此屬性的值可能會自動變更系列的類型。可讀寫 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**返回:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

指定 3D 柱狀圖系列的形狀。變更此屬性的值可能會自動變更系列的類型。可讀寫 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

指定如果值為負，柱形、列形或氣泡系列應反轉其顏色。可讀寫 boolean。

**返回:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

指定如果值為負，柱形、列形或氣泡系列應反轉其顏色。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
指定系列的反相實心顏色。若要套用顏色設定，請將系列格式的 FillType 設為 FillType.Solid。讀寫 [ColorFormat](../../com.aspose.slides/colorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

返回根據系列索引和圖表樣式自動產生的系列顏色。若 FillType 等於 NotDefined，則此顏色為預設使用的顏色。

**返回：**
java.awt.Color - java.awt.Color 物件。
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

表示內部點。True 表示在 BoxAndWhisker 圖表上顯示內部點。僅適用於 BoxAndWhisker 圖表。讀寫 boolean。

**返回：**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

表示內部點。True 表示在 BoxAndWhisker 圖表上顯示內部點。僅適用於 BoxAndWhisker 圖表。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

表示離群點。True 表示在 BoxAndWhisker 圖表上顯示離群點。僅適用於 BoxAndWhisker 圖表。讀寫 boolean。

**返回：**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

表示離群點。True 表示在 BoxAndWhisker 圖表上顯示離群點。僅適用於 BoxAndWhisker 圖表。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

表示平均值標記。True 表示在 BoxAndWhisker 圖表上顯示平均值標記。僅適用於 BoxAndWhisker 圖表。讀寫 boolean。

**返回：**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

表示平均值標記。True 表示在 BoxAndWhisker 圖表上顯示平均值標記。僅適用於 BoxAndWhisker 圖表。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

表示平均值線。True 表示在 BoxAndWhisker 圖表上顯示平均值線。僅適用於 BoxAndWhisker 圖表。讀寫 boolean。

**返回：**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

表示平均值線。True 表示在 BoxAndWhisker 圖表上顯示平均值線。僅適用於 BoxAndWhisker 圖表。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

表示四分位方法。僅適用於 BoxAndWhisker 圖表。

**返回：**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

表示四分位方法。僅適用於 BoxAndWhisker 圖表。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

表示連接線。僅適用於 Waterfall 圖表。

**返回：**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

表示連接線。僅適用於 Waterfall 圖表。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

表示父類別標籤的版面配置。僅適用於 Treemap 圖表。

**返回：**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

表示父類別標籤的版面配置。僅適用於 Treemap 圖表。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

判斷 Line 或 Stock 圖表是否具有上下條。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 讀寫屬性以變更值。使用 ParentSeriesGroup.UpDownBars 屬性以設定上下條的格式。唯讀 boolean。

--------------------

這是屬性 ParentSeriesGroup.UpDownBars.HasUpDownBars 的投影。

**返回：**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

指定條形或柱狀群組之間的間距，作為條形或柱狀寬度的百分比。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.GapWidth 讀寫屬性以變更值。唯讀 int。

--------------------

這是屬性 ParentSeriesGroup.GapWidth 的投影。

**返回：**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

返回或設定在 3D 圖表中，資料系列之間的距離（作為標記寬度的百分比）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.GapDepth 讀寫屬性以變更值。唯讀 int。

--------------------

這是屬性 ParentSeriesGroup.GapDepth 的投影。

**返回：**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

指定第一個餅圖或環形圖切片的角度，以度為單位（順時針從正上方，0 到 360 度）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.FirstSliceAngle 讀寫屬性以變更值。唯讀 int。

--------------------

這是屬性 ParentSeriesGroup.FirstSliceAngle 的投影。

**返回：**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

指定環形圖中孔的大小（可介於繪圖區域大小的 10% 到 90% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.DoughnutHoleSize 讀寫屬性以變更值。唯讀 byte。

--------------------

這是屬性 ParentSeriesGroup.DoughnutHoleSize 的投影。

**返回：**
byte
### getOverlap() {#getOverlap--}
```java
public final byte getOverlap()
```

指定 2-D 圖表中條形和柱形的重疊程度，以百分比表示（-100% 到 100%）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列。它是父系列群組中相應屬性的投影，因此此屬性為唯讀。若要變更數值，請使用 ParentSeriesGroup.Overlap 讀寫屬性。唯讀 byte。

--------------------

重疊度以條形和柱形寬度的百分比表示：- -100%：最大間距（條形完全分開）。- 0%：條形並排且不重疊也不間距。- 100%：最大重疊（條形完全覆蓋）。這是屬性 ParentSeriesGroup.Overlap 的投影。

**返回：**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

指定餅圖或餅圖分割圖的第二個餅或柱的大小，作為第一個餅大小的百分比（可介於 5% 到 200% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.SecondPieSize 讀寫屬性以變更值。唯讀 int。

--------------------

這是屬性 ParentSeriesGroup.SecondPieSize 的投影。

**返回：**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

判斷此系列及其相關系列是否有系列線。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.HasSeriesLines 讀寫屬性以變更值。使用 ParentSeriesGroup.SeriesLinesFormat 屬性以設定系列線格式。唯讀 boolean。

--------------------

這是屬性 ParentSeriesGroup.HasSeriesLines 的投影。

**返回：**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

指定氣泡圖上氣泡大小值的表示方式。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.BubbleSizeRepresentation 讀寫屬性以變更值。

--------------------

這是屬性 ParentSeriesGroup.BubbleSizeRepresentation 的投影。

**返回：**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

指定用於決定資料點在餅圖分割圖或柱狀分割圖之第二個餅或柱中的閾值。與 PieSplitBy 屬性一起使用。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.PieSplitPosition 讀寫屬性以變更值。唯讀 double。

--------------------

這是屬性 ParentSeriesGroup.PieSplitPosition 的投影。

**返回：**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

指定如何決定資料點在餅圖分割圖或柱狀分割圖之第二個餅或柱中的分割方式。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.PieSplitBy 讀寫屬性以變更值。唯讀 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) 這是屬性 ParentSeriesGroup.PieSplitBy 的投影。2) 若屬性值為 PieSplitType.Custom，則可使用 ParentSeriesGroup.PieSplitCustomPoints 屬性定義自訂分割資訊。

**返回：**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

自訂分割資訊適用於具有自訂分割的餅圖分割圖或柱狀分割圖。包含應在第二個餅或柱中繪製的資料點。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。唯讀 [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)。

--------------------

這是屬性 ParentSeriesGroup.PieSplitCustomPoints 的投影。

**返回：**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
指定系列中的每個資料標記具有不同的顏色。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——這是對相應群組屬性的投射。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.IsColorVaried 讀/寫屬性來變更值。唯讀 boolean.

--------------------

這是屬性 ParentSeriesGroup.IsColorVaried 的投射。

**返回值:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

指定氣泡圖的比例因子（可在預設大小的 0% 到 300% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——這是對相應群組屬性的投射。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性以存取父系列群組。使用 ParentSeriesGroup.BubbleSizeScale 讀/寫屬性來變更值。

--------------------

這是屬性 ParentSeriesGroup.BubbleSizeScale 的投射。

**返回值:**
int
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