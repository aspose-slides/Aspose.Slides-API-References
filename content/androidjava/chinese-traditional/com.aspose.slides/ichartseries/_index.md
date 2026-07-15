---
title: IChartSeries
second_title: Aspose.Slides for Android via Java API 參考
description: 代表圖表系列。
type: docs
url: /zh-hant/com.aspose.slides/ichartseries/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

表示圖表系列。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getExplosion()](#getExplosion--) | 開放的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。 |
| [setExplosion(int value)](#setExplosion-int-) | 開放的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。 |
| [getSmooth()](#getSmooth--) | 表示曲線平滑。 |
| [setSmooth(boolean value)](#setSmooth-boolean-) | 表示曲線平滑。 |
| [getMarker()](#getMarker--) | 返回系列標記。 |
| [getBar3DShape()](#getBar3DShape--) | 指定 3-D 長條圖系列的形狀。 |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 指定 3-D 長條圖系列的形狀。 |
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
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | 代表 X 方向的系列誤差線。 |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | 代表 Y 方向的系列誤差線。 |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | 表示此系列是否繪製於第二值軸上。 |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | 表示此系列是否繪製於第二值軸上。 |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | 取得或設定系列值的數字格式。 |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | 取得或設定系列值的數字格式。 |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | 取得或設定系列 X 值的數字格式。 |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | 取得或設定系列 X 值的數字格式。 |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | 取得或設定系列 Y 值的數字格式。 |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | 取得或設定系列 Y 值的數字格式。 |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | 取得或設定系列氣泡大小的數字格式。 |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | 取得或設定系列氣泡大小的數字格式。 |
| [getInvertIfNegative()](#getInvertIfNegative--) | 指定如果值為負，長條、柱形或氣泡系列應反轉其顏色。 |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 指定如果值為負，長條、柱形或氣泡系列應反轉其顏色。 |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | 指定系列的反轉實心顏色。 |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 代表與此系列相關的圖例項目 唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。 |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | 根據系列索引和圖表樣式返回系列的自動顏色。 |
| [getShowInnerPoints()](#getShowInnerPoints--) | 代表內部點。 |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | 代表內部點。 |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | 代表異常值點。 |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | 代表異常值點。 |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | 代表平均標記。 |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | 代表平均標記。 |
| [getShowMeanLine()](#getShowMeanLine--) | 代表平均標記。 |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | 代表平均標記。 |
| [getQuartileMethod()](#getQuartileMethod--) | 代表四分位方法。 |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | 代表四分位方法。 |
| [getShowConnectorLines()](#getShowConnectorLines--) | 代表連接線。 |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | 代表連接線。 |
| [getParentLabelLayout()](#getParentLabelLayout--) | 代表父類別標籤的佈局。 |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | 代表父類別標籤的佈局。 |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | 指定氣泡圖的比例因子（可為預設大小的 0% 到 300%）。 |
| [hasUpDownBars()](#hasUpDownBars--) | 判斷折線圖或股票圖是否具有上下柱條。 |
| [getGapWidth()](#getGapWidth--) | 指定長條或柱形群組之間的間距，以長條或柱形寬度的百分比表示。 |
| [getGapDepth()](#getGapDepth--) | 取得或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。 |
| [isColorVaried()](#isColorVaried--) | 指定系列中的每個資料標記具有不同的顏色。 |
| [hasSeriesLines()](#hasSeriesLines--) | 判斷此系列及其相關系列是否具有系列線。 |
| [getOverlap()](#getOverlap--) | 指定 2-D 圖表中長條和柱形的重疊程度，百分比（從 -100% 到 100%）。 |
| [getSecondPieSize()](#getSecondPieSize--) | 指定餅中餅或條中條圖的第二個餅或長條的大小，以第一個餅的大小百分比表示（可為 5% 到 200%）。 |
| [getPieSplitPosition()](#getPieSplitPosition--) | 指定用於決定哪些資料點位於餅中餅或條中條圖第二個餅或長條的值。 |
| [getPieSplitBy()](#getPieSplitBy--) | 指定如何決定哪些資料點位於餅中餅或條中條圖第二個餅或長條。 |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | 指定環形圖中孔的大小（可為繪圖區大小的 10% 到 90%）。 |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | 指定第一個餅或環形圖切片的角度（以度為單位，從上方順時針，0 到 360 度）。 |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | 具有自訂切分的餅中餅或條中條圖的自訂切分資訊。 |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | 指定氣泡圖中氣泡大小值的呈現方式。 |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

開放的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。 讀寫 int。

**返回:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

開放的餅圖切片與餅圖中心的距離以餅圖直徑的百分比表示。 讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

表示曲線平滑。 若線圖或散佈圖啟用曲線平滑則為 true。 僅適用於由線條連接的線圖和散佈圖。 讀寫 boolean。

**返回:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

表示曲線平滑。 若線圖或散佈圖啟用曲線平滑則為 true。 僅適用於由線條連接的線圖和散佈圖。 讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

返回系列標記。 唯讀 [IMarker](../../com.aspose.slides/imarker)。

**返回:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

指定 3-D 長條圖系列的形狀。 更改此屬性的值可能會自動變更系列類型。 讀寫 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**返回:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

指定 3-D 長條圖系列的形狀。 更改此屬性的值可能會自動變更系列類型。 讀寫 [ChartShapeType](../../com.aspose.slides/chartshapetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

返回系列名稱。 唯讀 [IStringChartValue](../../com.aspose.slides/istringchartvalue)。

**返回:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

返回此系列的資料點集合。 唯讀 [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)。

**返回:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

返回此系列的類型。 讀寫 [ChartType](../../com.aspose.slides/charttype)。

**返回:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

返回此系列的類型。 讀寫 [ChartType](../../com.aspose.slides/charttype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

返回父系列群組。 唯讀 [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)。

**返回:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

返回系列的格式。 唯讀 [IFormat](../../com.aspose.slides/iformat)。

**返回:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

返回系列的順序。 讀寫 int。

**返回:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

返回系列的順序。 讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

返回系列的標籤。 唯讀 [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)。

**返回:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

系列趨勢線集合 唯讀 [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)。

**返回:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

代表 X 方向的系列誤差線。 唯讀 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

X 方向的誤差線適用於 area、bar、scatter 和 bubble 類型的系列。其他圖表類型（包括 3D 圖表）此屬性返回 null。若使用自訂值，請使用 DataPoints 集合指定值（帶 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性）。

**返回:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

代表 Y 方向的系列誤差線。 唯讀 [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)。

--------------------

Y 方向的誤差線適用於 area、bar、line、scatter 和 bubble 類型的系列。其他圖表類型（包括 3D 圖表）此屬性返回 null。若使用自訂值，請使用 DataPoints 集合指定值（帶 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 屬性）。

**返回:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

表示此系列是否繪製於第二值軸上。 讀寫 boolean。

**返回:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

表示此系列是否繪製於第二值軸上。 讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

取得或設定系列值的數字格式。 讀寫 String。

**返回:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

取得或設定系列值的數字格式。 讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

取得或設定系列 X 值的數字格式。 讀寫 String。

**返回:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

取得或設定系列 X 值的數字格式。 讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

取得或設定系列 Y 值的數字格式。 讀寫 String。

**返回:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

取得或設定系列 Y 值的數字格式。 讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

取得或設定系列氣泡大小的數字格式。 讀寫 String。

**返回:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

取得或設定系列氣泡大小的數字格式。 讀寫 String。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

指定如果值為負，長條、柱形或氣泡系列應反轉其顏色。 讀寫 boolean。

**返回:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

指定如果值為負，長條、柱形或氣泡系列應反轉其顏色。 讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

指定系列的反轉實心顏色。 若要套用顏色設定，請將系列格式的 FillType 設為 FillType.Solid。 讀寫 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

代表與此系列相關的圖例項目 唯讀 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)。

**返回:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

返回根據系列索引和圖表樣式自動產生的系列顏色。 若 FillType 為 NotDefined，預設使用此顏色。

**返回:**
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

代表內部點。 若在 BoxAndWhisker 圖上顯示內部點則為 true。 僅適用於 BoxAndWhisker 圖表。 讀寫 boolean。

**返回:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

代表內部點。 若在 BoxAndWhisker 圖上顯示內部點則為 true。 僅適用於 BoxAndWhisker 圖表。 讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

代表異常值點。 若在 BoxAndWhisker 圖上顯示異常值點則為 true。 僅適用於 BoxAndWhisker 圖表。 讀寫 boolean。

**返回:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

代表異常值點。 若在 BoxAndWhisker 圖上顯示異常值點則為 true。 僅適用於 BoxAndWhisker 圖表。 讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

代表平均標記。 若在 BoxAndWhisker 圖上顯示平均標記則為 true。 僅適用於 BoxAndWhisker 圖表。 讀寫 boolean。

**返回:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

代表平均標記。 若在 BoxAndWhisker 圖上顯示平均標記則為 true。 僅適用於 BoxAndWhisker 圖表。 讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

代表平均線。 若在 BoxAndWhisker 圖上顯示平均線則為 true。 僅適用於 BoxAndWhisker 圖表。 讀寫 boolean。

**返回:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

代表平均線。 若在 BoxAndWhisker 圖上顯示平均線則為 true。 僅適用於 BoxAndWhisker 圖表。 讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

代表四分位方法。 僅適用於 BoxAndWhisker 圖表。

**返回:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

代表四分位方法。 僅適用於 BoxAndWhisker 圖表。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

代表連接線。 僅適用於瀑布圖。

**返回:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

代表連接線。 僅適用於瀑布圖。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

代表父類別標籤的佈局。 僅適用於樹圖。

**返回:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

代表父類別標籤的佈局。 僅適用於樹圖。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

指定氣泡圖的比例因子（可為預設大小的 0% 到 300%）。 此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.BubbleSizeScale 讀寫屬性。

--------------------

此為屬性 ParentSeriesGroup.BubbleSizeScale 的投影。

**返回:**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

判斷折線圖或股票圖是否具有上下柱條。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 讀寫屬性。使用 ParentSeriesGroup.UpDownBars 屬性設定上下柱條格式。唯讀 boolean。

--------------------

此為屬性 ParentSeriesGroup.UpDownBars.HasUpDownBars 的投影。

**返回:**
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

指定長條或柱形群組之間的間距，以長條或柱形寬度的百分比表示。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.GapWidth 讀寫屬性。唯讀 int。

--------------------

此為屬性 ParentSeriesGroup.GapWidth 的投影。

**返回:**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

取得或設定 3D 圖表中資料系列之間的距離，以標記寬度的百分比表示。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.GapDepth 讀寫屬性。唯讀 int。

--------------------

此為屬性 ParentSeriesGroup.GapDepth 的投影。

**返回:**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

指定系列中的每個資料標記是否具有不同的顏色。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.IsColorVaried 讀寫屬性。唯讀 boolean。

--------------------

此為屬性 ParentSeriesGroup.IsColorVaried 的投影。

**返回:**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

判斷此系列及相關系列是否具有系列線。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.HasSeriesLines 讀寫屬性。使用 ParentSeriesGroup.SeriesLinesFormat 屬性設定系列線格式。唯讀 boolean。

--------------------

此為屬性 ParentSeriesGroup.HasSeriesLines 的投影。

**返回:**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

指定 2-D 圖表中長條和柱形的重疊程度，百分比（從 -100% 到 100%）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列，為相應群組屬性的投影，故為唯讀。若要變更值，請使用 ParentSeriesGroup.Overlap 讀寫屬性。唯讀 byte 。

--------------------

Overlap 表示長條和柱形之間的重疊或間距程度，以其寬度的百分比表示：-100%：最大間距（長條完全分離）。0%：長條並排無重疊或間距。100%：最大重疊（長條完全重疊）。此為屬性 ParentSeriesGroup.Overlap 的投影。

**返回:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

指定餅中餅或條中條圖第二個餅或長條的大小，以第一個餅的大小百分比表示（可為 5% 到 200%）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.SecondPieSize 讀寫屬性。唯讀 int。

--------------------

此為屬性 ParentSeriesGroup.SecondPieSize 的投影。

**返回:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

指定用於決定哪些資料點位於餅中餅或條中條圖第二個餅或長條的值。與 PieSplitBy 屬性一起使用。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.PieSplitPosition 讀寫屬性。唯讀 double。

--------------------

此為屬性 ParentSeriesGroup.PieSplitPosition 的投影。

**返回:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

指定如何決定哪些資料點位於餅中餅或條中條圖第二個餅或長條。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.PieSplitBy 讀寫屬性。唯讀 [PieSplitType](../../com.aspose.slides/piesplittype)。

--------------------

1) 此為屬性 ParentSeriesGroup.PieSplitBy 的投影。2) 若屬性值為 PieSplitType.Custom，則可使用 ParentSeriesGroup.PieSplitCustomPoints 屬性定義自訂切分資訊。

**返回:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

指定環形圖中孔的大小（可為繪圖區大小的 10% 到 90%）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.DoughnutHoleSize 讀寫屬性。唯讀 byte。

--------------------

此為屬性 ParentSeriesGroup.DoughnutHoleSize 的投影。

**返回:**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

指定第一個餅或環形圖切片的角度，以度為單位（從上方順時針，0 到 360 度）。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.FirstSliceAngle 讀寫屬性。唯讀 int。

--------------------

此為屬性 ParentSeriesGroup.FirstSliceAngle 的投影。

**返回:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

具有自訂切分的餅中餅或條中條圖的自訂切分資訊。包含應在第二個餅或長條中繪製的資料點。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性唯讀 [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)。

--------------------

此為屬性 ParentSeriesGroup.PieSplitCustomPoints 的投影。

**返回:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

指定氣泡圖上氣泡大小值的呈現方式。此屬性不僅屬於此系列，亦屬於父系列群組的所有系列——此屬性為相應群組屬性的投影。因此此屬性唯讀。請使用 ParentSeriesGroup 屬性存取父系列群組。若要變更值，請使用 ParentSeriesGroup.BubbleSizeRepresentation 讀寫屬性。

--------------------

此為屬性 ParentSeriesGroup.BubbleSizeRepresentation 的投影。

**返回:**
int