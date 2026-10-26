---
title: IChartSeries
second_title: Aspose.Slides for Java API 參考
description: 表示圖表系列。
type: docs
url: /zh-hant/com.aspose.slides/ichartseries/
---
**已實作的介面:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

代表圖表系列。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExplosion()](#getExplosion--) | 開啟的餅圖切片從圓心的距離以餅圖直徑的百分比表示。 |
| [setExplosion(int value)](#setExplosion-int-) | 開啟的餅圖切片從圓心的距離以餅圖直徑的百分比表示。 |
| [getSmooth()](#getSmooth--) | 代表曲線平滑。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 代表曲線平滑。 |
| [getMarker()](#getMarker--) | 返回系列標記。 |
| [getBar3DShape()](#getBar3DShape--) | 指定 3-D 柱狀圖系列的形狀。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 指定 3-D 柱狀圖系列的形狀。 |
| [getName()](#getName--) | 返回系列名稱。 |
| [getDataPoints()](#getDataPoints--) | 返回此系列的資料點集合。 |
| [getType()](#getType--) | 返回此系列的類型。 |
| [setType(int value)](#setType-int-) | 返回此系列的類型。 |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | 返回父系列群組。 |
| [getFormat()](#getFormat--) | 返回系列的格式。 |
| [getOrder()](#getOrder--) | 返回系列的順序。 |
| [setOrder(int value)](#setOrder-int-) | 返回系列的順序。 |
| [getLabels()](#getLabels--) | 返回系列的標籤。 |
| [getTrendLines()](#getTrendLines--) | 系列趨勢線集合 唯讀 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。 |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | 代表方向為 X 的系列誤差棒。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | 代表方向為 Y 的系列誤差棒。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 指示此系列是否繪製於第二值軸上。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | 指示此系列是否繪製於第二值軸上。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | 返回或設定系列值的數字格式。 |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | 返回或設定系列值的數字格式。 |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | 返回或設定系列 X 值的數字格式。 |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | 返回或設定系列 X 值的數字格式。 |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | 返回或設定系列 Y 值的數字格式。 |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | 返回或設定系列 Y 值的數字格式。 |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | 返回或設定系列氣泡大小的數字格式。 |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | 返回或設定系列氣泡大小的數字格式。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定當值為負時，柱形、欄形或氣泡系列應反轉其顏色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定當值為負時，柱形、欄形或氣泡系列應反轉其顏色。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 指定為系列反轉實色填充。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 代表與此系列相關的圖例項目 唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 返回基於系列索引與圖表樣式的自動系列顏色。 |
| [getShowInnerPoints()](#getShowInnerPoints--) | 代表內部點。 |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 代表內部點。 |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 代表離群點。 |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 代表離群點。 |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 代表平均值標記。 |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 代表平均值標記。 |
| [getShowMeanLine()](#getShowMeanLine--) | 代表平均值標記。 |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 代表平均值標記。 |
| [getQuartileMethod()](#getQuartileMethod--) | 代表四分位方法。 |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 代表四分位方法。 |
| [getShowConnectorLines()](#getShowConnectorLines--) | 代表連接線。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | 代表連接線。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 代表父類別標籤的佈局。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 代表父類別標籤的佈局。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的縮放比例（可介於預設大小的 0% 到 300% 之間）。 |
| [hasUpDownBars()](#hasUpDownBars--) | 確定折線圖或股票圖是否具有上/下棒。 |
| [getGapWidth()](#getGapWidth--) | 指定柱形或欄形叢集之間的間距，作為柱形或欄形寬度的百分比。 |
| [getGapDepth()](#getGapDepth--) | 返回或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記具有不同的顏色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 確定此系列及相關系列是否具有系列線。 |
| [getOverlap()](#getOverlap--) | 指定柱形與欄形在 2D 圖表上重疊的比例，百分比（-100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定餅中餅或餅中柱圖中第二個餅或柱的大小，作為第一個餅大小的百分比（可介於 5% 到 200%）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用於決定哪些資料點位於餅中餅或餅中柱圖的第二個餅或柱的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何決定哪些資料點位於餅中餅或餅中柱圖的第二個餅或柱。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定甜甜圈圖中孔洞的大小（可介於繪圖區大小的 10% 到 90%）。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 指定第一個餅或甜甜圈圖切片的角度，單位為度（從上方順時針，0 到 360 度）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 自訂分割資訊，用於具有自訂分割的餅中餅或餅中柱圖。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖中氣泡大小值的呈現方式。 |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

開啟的餅圖切片從圓心的距離以餅圖直徑的百分比表示。 可讀寫 int。

**返回值:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

開啟的餅圖切片從圓心的距離以餅圖直徑的百分比表示。 可讀寫 int。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

代表曲線平滑。如果在折線圖或散佈圖中啟用了曲線平滑，則為 true。僅適用於線條相連的折線圖和散佈圖。可讀寫 boolean。

**返回值:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

代表曲線平滑。如果在折線圖或散佈圖中啟用了曲線平滑，則為 true。僅適用於線條相連的折線圖和散佈圖。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

返回系列標記。唯讀 [IMarker](../../com.aspose.slides/imarker)。

**返回值:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

指定 3-D 柱狀圖系列的形狀。更改此屬性的值可能會自動更改系列的類型。可讀寫 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**返回值:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

指定 3-D 柱狀圖系列的形狀。更改此屬性的值可能會自動更改系列的類型。可讀寫 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

返回系列名稱。唯讀 [IStringChartValue](../../com.aspose.slides/istringchartvalue)。

**返回值:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

返回此系列的資料點集合。唯讀 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)。

**返回值:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

返回此系列的類型。可讀寫 [ChartType](../../com.aspose.slides/charttype)。

**返回值:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

返回此系列的類型。可讀寫 [ChartType](../../com.aspose.slides/charttype)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

返回父系列群組。唯讀 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)。

**返回值:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

返回系列的格式。唯讀 [IFormat](../../com.aspose.slides/iformat)。

**返回值:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

返回系列的順序。可讀寫 int。

**返回值:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

返回系列的順序。可讀寫 int。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

返回系列的標籤。唯讀 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)。

**返回值:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

系列趨勢線集合 唯讀 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。

**返回值:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

代表方向為 X 的系列誤差棒。唯讀 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

方向為 X 的誤差棒適用於類型為 area、bar、scatter 和 bubble 的系列。對於其他類型的圖表（包括 3D 圖表），此屬性返回 null。若使用自訂值，請使用 DataPoints 集合指定值（使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性）。

**返回值:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

代表方向為 Y 的系列誤差棒。唯讀 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

方向為 Y 的誤差棒適用於類型為 area、bar、line、scatter 和 bubble 的系列。對於其他類型的圖表（包括 3D 圖表），此屬性返回 null。若使用自訂值，請使用 DataPoints 集合指定值（使用 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性）。

**返回值:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

指示此系列是否繪製於第二值軸上。可讀寫 boolean。

**返回值:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

指示此系列是否繪製於第二值軸上。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

返回或設定系列值的數字格式。可讀寫 String。

**返回值:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

返回或設定系列值的數字格式。可讀寫 String。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

返回或設定系列 X 值的數字格式。可讀寫 String。

**返回值:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

返回或設定系列 X 值的數字格式。可讀寫 String。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

返回或設定系列 Y 值的數字格式。可讀寫 String。

**返回值:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

返回或設定系列 Y 值的數字格式。可讀寫 String。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

返回或設定系列氣泡大小的數字格式。可讀寫 String。

**返回值:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

返回或設定系列氣泡大小的數字格式。可讀寫 String。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

指定當值為負時，柱形、欄形或氣泡系列應反轉其顏色。可讀寫 boolean。

**返回值:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

指定當值為負時，柱形、欄形或氣泡系列應反轉其顏色。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

指定為系列反轉實心填色。若要套用顏色設定，請將系列格式的 FillType 設為 FillType.Solid。可讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

代表與此系列相關的圖例項目 唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回值:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
根據系列索引和圖表樣式返回系列的自動顏色。如果 FillType 等於 NotDefined，則此顏色是預設使用的。

**返回：**
java.awt.Color - 系列的自動顏色 java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

表示內部點。如果在 BoxAndWhisker 圖表上顯示內部點，則為 True。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**返回：**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

表示內部點。如果在 BoxAndWhisker 圖表上顯示內部點，則為 True。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

表示異常值點。如果在 BoxAndWhisker 圖表上顯示異常值點，則為 True。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**返回：**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

表示異常值點。如果在 BoxAndWhisker 圖表上顯示異常值點，則為 True。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

表示平均值標記。如果在 BoxAndWhisker 圖表上顯示平均值標記，則為 True。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**返回：**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

表示平均值標記。如果在 BoxAndWhisker 圖表上顯示平均值標記，則為 True。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

表示平均線。如果在 BoxAndWhisker 圖表上顯示平均線，則為 True。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**返回：**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

表示平均線。如果在 BoxAndWhisker 圖表上顯示平均線，則為 True。僅適用於 BoxAndWhisker 圖表。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

表示四分位方法。僅適用於 BoxAndWhisker 圖表。

**返回：**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

表示四分位方法。僅適用於 BoxAndWhisker 圖表。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

表示連接線。僅適用於 Waterfall 圖表。

**返回：**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

表示連接線。僅適用於 Waterfall 圖表。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

表示父類別標籤的佈局。僅適用於 Treemap 圖表。

**返回：**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

表示父類別標籤的佈局。僅適用於 Treemap 圖表。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

指定氣泡圖的比例因子（可介於預設大小的 0% 到 300% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.BubbleSizeScale 可讀寫屬性變更值。

--------------------

這是屬性 ParentSeriesGroup.BubbleSizeScale 的投影。

**返回：**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

判斷折線圖或股票圖是否具有上下條。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 可讀寫屬性變更值。使用 ParentSeriesGroup.UpDownBars 屬性格式化上下條。唯讀 boolean。

--------------------

這是屬性 ParentSeriesGroup.UpDownBars.HasUpDownBars 的投影。

**返回：**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

指定條形或柱狀叢集之間的間距，作為條形或柱狀寬度的百分比。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.GapWidth 可讀寫屬性變更值。唯讀 int。

--------------------

這是屬性 ParentSeriesGroup.GapWidth 的投影。

**返回：**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

返回或設定在 3D 圖表中，作為標記寬度百分比的資料系列之間的距離。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.GapDepth 可讀寫屬性變更值。唯讀 int。

--------------------

這是屬性 ParentSeriesGroup.GapDepth 的投影。

**返回：**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

指定系列中的每個資料標記是否具有不同的顏色。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.IsColorVaried 可讀寫屬性變更值。唯讀 boolean。

--------------------

這是屬性 ParentSeriesGroup.IsColorVaried 的投影。

**返回：**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

判斷此系列及相關系列是否具有系列線。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.HasSeriesLines 可讀寫屬性變更值。使用 ParentSeriesGroup.SeriesLinesFormat 屬性格式化系列線。唯讀 boolean。

--------------------

這是屬性 ParentSeriesGroup.HasSeriesLines 的投影。

**返回：**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

指定條形與柱狀在 2-D 圖表上的重疊程度，作為百分比（-100% 至 100%）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列。它是父系列群組中相應屬性的投影，故此屬性為唯讀。若要變更值，請使用 ParentSeriesGroup.Overlap 可讀寫屬性。唯讀 byte 。

--------------------

Overlap 指定條形與柱狀之間的重疊或間距程度，作為其寬度的百分比：-100%：最大間距（條形完全分離）。0%：條形並排放置，無重疊或間距。100%：最大重疊（條形完全重疊）。這是屬性 ParentSeriesGroup.Overlap 的投影。

**返回：**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

指定第二個餅圖或餅圖條的大小，作為第一個餅圖大小的百分比（可介於 5% 到 200% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.SecondPieSize 可讀寫屬性變更值。唯讀 int。

--------------------

這是屬性 ParentSeriesGroup.SecondPieSize 的投影。

**返回：**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

指定用於決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖表第二個餅圖或條的值。與 PieSplitBy 屬性一起使用。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.PieSplitPosition 可讀寫屬性變更值。唯讀 double。

--------------------

這是屬性 ParentSeriesGroup.PieSplitPosition 的投影。

**返回：**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

指定如何決定哪些資料點位於 pie-of-pie 或 bar-of-pie 圖表的第二個餅圖或條。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.PieSplitBy 可讀寫屬性變更值。唯讀 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) 這是屬性 ParentSeriesGroup.PieSplitBy 的投影。 2) 若屬性值為 PieSplitType.Custom，則可使用 ParentSeriesGroup.PieSplitCustomPoints 屬性定義自訂分割資訊。

**返回：**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

指定環形圖中心孔的大小（可介於繪圖區域大小的 10% 到 90% 之間）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.DoughnutHoleSize 可讀寫屬性變更值。唯讀 byte。

--------------------

這是屬性 ParentSeriesGroup.DoughnutHoleSize 的投影。

**返回：**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

指定第一個餅圖或環形圖切片的角度（以度為單位，順時針從正上方，0 至 360 度）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性的投影。因此此屬性為唯讀。使用 ParentSeriesGroup 屬性存取父系列群組。使用 ParentSeriesGroup.FirstSliceAngle 可讀寫屬性變更值。唯讀 int。

--------------------

這是屬性 ParentSeriesGroup.FirstSliceAngle 的投影。

**返回：**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

自訂分割資訊，用於具有自訂分割的 pie-of-pie 或 bar-of-pie 圖表。包含應繪製於第二個餅圖或條中的資料點。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——屬於相應群組屬性 唯讀 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

--------------------

這是屬性 ParentSeriesGroup.PieSplitCustomPoints 的投影。

**返回：**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
指定在氣泡圖上如何呈現氣泡大小值。此屬性不僅屬於此系列，也屬於父系列群組的所有系列——這是相應群組屬性的投影。因此此屬性為只讀。使用 ParentSeriesGroup 屬性來存取父系列群組。使用 ParentSeriesGroup.BubbleSizeRepresentation 可讀寫屬性來變更值。

--------------------

這是屬性 ParentSeriesGroup.BubbleSizeRepresentation 的投影。

**返回:**  
int