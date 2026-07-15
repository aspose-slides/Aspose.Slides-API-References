---
title: Axis
second_title: Aspose.Slides for Android via Java API 參考
description: 封裝表示圖表軸的物件。
type: docs
url: /zh-hant/com.aspose.slides/axis/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

封裝表示圖表軸的物件。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getChart()](#getChart--) | 返回父圖表。 |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 代表數值軸是否在類別之間交叉類別軸。 |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 代表數值軸是否在類別之間交叉類別軸。 |
| [getCategoryAxisType()](#getCategoryAxisType--) | 指定類別軸的類型。 |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | 指定類別軸的類型。 |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 設定 IAxis.CategoryAxisType 屬性，其值會根據軸資料自動決定。 |
| [getCrossAt()](#getCrossAt--) | 代表垂直軸與此軸相交的點。 |
| [setCrossAt(float value)](#setCrossAt-float-) | 代表垂直軸與此軸相交的點。 |
| [getDisplayUnit()](#getDisplayUnit--) | 指定數值軸顯示單位的縮放值。 |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 指定數值軸顯示單位的縮放值。 |
| [getActualMaxValue()](#getActualMaxValue--) | 指定軸上的實際最大值。 |
| [getActualMinValue()](#getActualMinValue--) | 指定軸上的實際最小值。 |
| [getActualMajorUnit()](#getActualMajorUnit--) | 指定軸的實際主要單位。 |
| [getActualMinorUnit()](#getActualMinorUnit--) | 指定軸的實際次要單位。 |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 指定軸的實際主要單位比例。 |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 指定軸的實際次要單位比例。 |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 指示最大值是否自動指派。 |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 指示最大值是否自動指派。 |
| [getMaxValue()](#getMaxValue--) | 代表數值軸的最大值。 |
| [setMaxValue(double value)](#setMaxValue-double-) | 代表數值軸的最大值。 |
| [getMinorUnit()](#getMinorUnit--) | 代表日期或數值軸的次要單位。 |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 代表日期或數值軸的次要單位。 |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 指示軸的次要單位是否自動指派。 |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 指示軸的次要單位是否自動指派。 |
| [getMajorUnit()](#getMajorUnit--) | 代表日期或數值軸的主要單位。 |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 代表日期或數值軸的主要單位。 |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 指示軸的主要單位是否自動指派。 |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 指示軸的主要單位是否自動指派。 |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 指示最小值是否自動指派。 |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 指示最小值是否自動指派。 |
| [getMinValue()](#getMinValue--) | 代表數值軸的最小值。 |
| [setMinValue(double value)](#setMinValue-double-) | 代表數值軸的最小值。 |
| [isLogarithmic()](#isLogarithmic--) | 代表數值軸的比例類型是否為對數。 |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 代表數值軸的比例類型是否為對數。 |
| [getLogBase()](#getLogBase--) | 代表對數底數。 |
| [setLogBase(double value)](#setLogBase-double-) | 代表對數底數。 |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | 代表 MS PowerPoint 是否將資料點從最後繪製到第一。 |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | 代表 MS PowerPoint 是否將資料點從最後繪製到第一。 |
| [isVisible()](#isVisible--) | 代表軸是否可見。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 代表軸是否可見。 |
| [getMajorTickMark()](#getMajorTickMark--) | 代表指定軸的主要刻度標記類型。 |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 代表指定軸的主要刻度標記類型。 |
| [getMinorTickMark()](#getMinorTickMark--) | 代表指定軸的次要刻度標記類型。 |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 代表指定軸的次要刻度標記類型。 |
| [getTickLabelPosition()](#getTickLabelPosition--) | 代表指定軸上刻度標籤的位置。 |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 代表指定軸上刻度標籤的位置。 |
| [getMajorUnitScale()](#getMajorUnitScale--) | 代表日期軸的主要單位比例。 |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 代表日期軸的主要單位比例。 |
| [getMinorUnitScale()](#getMinorUnitScale--) | 代表日期軸的主要單位比例。 |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 代表日期軸的主要單位比例。 |
| [getBaseUnitScale()](#getBaseUnitScale--) | 指定日期軸上所表示的最小時間單位。 |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 指定日期軸上所表示的最小時間單位。 |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | 代表圖表軸的次要格線格式。 |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | 代表圖表軸的主要格線格式。 |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 若要隱藏次要格線，將 MinorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。 |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 若要隱藏主要格線，將 MajorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。 |
| [getFormat()](#getFormat--) | 代表軸的格式。 |
| [getTextFormat()](#getTextFormat--) | 代表文字的格式。 |
| [getTitle()](#getTitle--) | 取得軸的標題。 |
| [getCrossType()](#getCrossType--) | 代表指定軸上另一軸交叉的 CrossType。 |
| [setCrossType(int value)](#setCrossType-int-) | 代表指定軸上另一軸交叉的 CrossType。 |
| [getPosition()](#getPosition--) | 代表軸的位置。 |
| [setPosition(int value)](#setPosition-int-) | 代表軸的位置。 |
| [hasTitle()](#hasTitle--) | 判斷軸是否具有可見的標題。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 判斷軸是否具有可見的標題。 |
| [getNumberFormat()](#getNumberFormat--) | 代表軸標籤的格式字串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 代表軸標籤的格式字串。 |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 指示該格式是否連結至來源資料。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 指示該格式是否連結至來源資料。 |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 代表刻度標籤的旋轉角度。 |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 代表刻度標籤的旋轉角度。 |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 指定在已繪製的標籤之間要跳過多少個刻度標籤。 |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 指定在已繪製的標籤之間要跳過多少個刻度標籤。 |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 指定自動刻度標籤間距值。 |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 指定自動刻度標籤間距值。 |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 指定在繪製下一個刻度標記前要跳過多少個刻度標記。 |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 指定在繪製下一個刻度標記前要跳過多少個刻度標記。 |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 指定自動刻度標記間距值。 |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 指定自動刻度標記間距值。 |
| [getLabelOffset()](#getLabelOffset--) | 指定標籤與軸的距離。 |
| [setLabelOffset(int value)](#setLabelOffset-int-) | 指定標籤與軸的距離。 |
| [getAggregationType()](#getAggregationType--) | 代表類別軸的彙總類型（分箱）。 |
| [setAggregationType(int value)](#setAggregationType-int-) | 代表類別軸的彙總類型（分箱）。 |
| [getBinWidth()](#getBinWidth--) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。 |
| [setBinWidth(double value)](#setBinWidth-double-) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。 |
| [getNumberOfBins()](#getNumberOfBins--) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。 |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。 |
| [isOverflowBin()](#isOverflowBin--) | 指定是否套用溢位箱。 |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | 指定是否套用溢位箱。 |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 指定自動溢位箱值。 |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 指定自動溢位箱值。 |
| [getOverflowBin()](#getOverflowBin--) | 指定溢位箱自訂值。 |
| [setOverflowBin(double value)](#setOverflowBin-double-) | 指定溢位箱自訂值。 |
| [isUnderflowBin()](#isUnderflowBin--) | 指定是否套用欠位箱。 |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | 指定是否套用欠位箱。 |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 指定自動欠位箱值。 |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 指定自動欠位箱值。 |
| [getUnderflowBin()](#getUnderflowBin--) | 指定欠位箱自訂值。 |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | 指定欠位箱自訂值。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父圖表。只讀 [IChart](../../com.aspose.slides/ichart)。

**返回：**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

代表數值軸是否在類別之間交叉類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。可讀寫 boolean。

**返回：**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

代表數值軸是否在類別之間交叉類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

指定類別軸的類型。可讀寫 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)。

**返回：**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

指定類別軸的類型。可讀寫 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

設定 IAxis.CategoryAxisType 屬性，其值會根據軸資料自動決定。

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

代表垂直軸與此軸相交的點。可讀寫 float。

**返回：**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

代表垂直軸與此軸相交的點。可讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

指定數值軸顯示單位的縮放值。可讀寫 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**返回：**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

指定數值軸顯示單位的縮放值。可讀寫 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

指定軸上的實際最大值。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。

**返回：**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

指定軸上的實際最小值。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。

**返回：**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

指定軸的實際主要單位。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。

**返回：**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

指定軸的實際次要單位。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。

**返回：**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

指定軸的實際主要單位比例。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。

**返回：**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

指定軸的實際次要單位比例。先前呼叫 IChart.ValidateChartLayout() 方法以取得實際值。

**返回：**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

指示最大值是否自動指派。可讀寫 boolean。

**返回：**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

指示最大值是否自動指派。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

代表數值軸的最大值。可讀寫 double。

**返回：**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

代表數值軸的最大值。可讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

代表日期或數值軸的次要單位。可讀寫 double。

**返回：**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

代表日期或數值軸的次要單位。可讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

指示軸的次要單位是否自動指派。可讀寫 boolean。

**返回：**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

指示軸的次要單位是否自動指派。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

代表日期或數值軸的主要單位。可讀寫 double。

**返回：**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

代表日期或數值軸的主要單位。可讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

指示軸的主要單位是否自動指派。可讀寫 boolean。

**返回：**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

指示軸的主要單位是否自動指派。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

指示最小值是否自動指派。可讀寫 boolean。

**返回：**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

指示最小值是否自動指派。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

代表數值軸的最小值。可讀寫 double。

**返回：**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

代表數值軸的最小值。可讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

代表數值軸的比例類型是否為對數。可讀寫 boolean。

**返回：**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

代表數值軸的比例類型是否為對數。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

代表對數底數。預設值為 10。可讀寫 double。

**返回：**
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

代表對數底數。預設值為 10。可讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

代表 MS PowerPoint 是否將資料點從最後繪製到第一。可讀寫 boolean。

**返回：**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

代表 MS PowerPoint 是否將資料點從最後繪製到第一。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

代表軸是否可見。可讀寫 boolean。

**返回：**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

代表軸是否可見。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

代表指定軸的主要刻度標記類型。可讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**返回：**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

代表指定軸的主要刻度標記類型。可讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

代表指定軸的次要刻度標記類型。可讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**返回：**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

代表指定軸的次要刻度標記類型。可讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

代表指定軸上刻度標籤的位置。可讀寫 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**返回：**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

代表指定軸上刻度標籤的位置。可讀寫 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

代表日期軸的主要單位比例。可讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

代表日期軸的主要單位比例。可讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

代表日期軸的主要單位比例。可讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

代表日期軸的主要單位比例。可讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

指定日期軸上所表示的最小時間單位。可讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**返回：**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

指定日期軸上所表示的最小時間單位。可讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

代表圖表軸的次要格線格式。只讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**返回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

代表圖表軸的主要格線格式。只讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**返回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

若要隱藏次要格線，將 MinorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。只讀 boolean。

**返回：**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

若要隱藏主要格線，將 MajorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。只讀 boolean。

**返回：**
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

代表軸的格式。只讀 [IAxisFormat](../../com.aspose.slides/iaxisformat)。

**返回：**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

代表文字的格式。只讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

取得軸的標題。只讀 [IChartTitle](../../com.aspose.slides/icharttitle)。

**返回：**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

代表指定軸上另一軸交叉的 CrossType。可讀寫 [CrossesType](../../com.aspose.slides/crossestype)。

**返回：**
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

代表指定軸上另一軸交叉的 CrossType。可讀寫 [CrossesType](../../com.aspose.slides/crossestype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

代表軸的位置。可讀寫 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**返回：**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

代表軸的位置。可讀寫 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

判斷軸是否具有可見的標題。可讀寫 boolean。

**返回：**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

判斷軸是否具有可見的標題。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

代表軸標籤的格式字串。可讀寫 String。

**返回：**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

代表軸標籤的格式字串。可讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

指示該格式是否連結至來源資料。可讀寫 boolean。

**返回：**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

指示該格式是否連結至來源資料。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

代表刻度標籤的旋轉角度。可讀寫 float。

**返回：**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

代表刻度標籤的旋轉角度。可讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

指定在已繪製的標籤之間要跳過多少個刻度標籤。應用於類別或系列軸。可讀寫 long。

**返回：**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

指定在已繪製的標籤之間要跳過多少個刻度標籤。應用於類別或系列軸。可讀寫 long。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。可讀寫 boolean。

**返回：**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

指定在繪製下一個刻度標記前要跳過多少個刻度標記。應用於類別或系列軸。可讀寫 int。

**返回：**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

指定在繪製下一個刻度標記前要跳過多少個刻度標記。應用於類別或系列軸。可讀寫 int。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。可讀寫 boolean。

**返回：**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

指定標籤與軸的距離。應用於類別或日期軸。值必須介於 0% 與 1000% 之間。可讀寫 int。

**返回：**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

指定標籤與軸的距離。應用於類別或日期軸。值必須介於 0% 與 1000% 之間。可讀寫 int。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

代表類別軸的彙總類型（分箱）。應用於類別。僅於 Histogram 或 HistogramPareto 系列使用。

**返回：**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

代表類別軸的彙總類型（分箱）。應用於類別。僅於 Histogram 或 HistogramPareto 系列使用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。應用於類別軸。僅於 Histogram 或 HistogramPareto 系列使用。

**返回：**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。應用於類別軸。僅於 Histogram 或 HistogramPareto 系列使用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。應用於類別軸。僅於 Histogram 或 HistogramPareto 系列使用。

**返回：**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。應用於類別軸。僅於 Histogram 或 HistogramPareto 系列使用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

指定是否套用溢位箱。使用 IsAutomaticOverflowBin 和 OverflowBin 來調整溢位箱值。

**返回：**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

指定是否套用溢位箱。使用 IsAutomaticOverflowBin 和 OverflowBin 來調整溢位箱值。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

指定自動溢位箱值。若為 false：使用 OverflowBin 屬性。

**返回：**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

指定自動溢位箱值。若為 false：使用 OverflowBin 屬性。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

指定溢位箱自訂值。當 IsAutomaticOverflowBin 屬性設定為 false 且 IsOverflowBin 屬性為 true 時套用。

**返回：**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

指定溢位箱自訂值。當 IsAutomaticOverflowBin 屬性設定為 false 且 IsOverflowBin 屬性為 true 時套用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

指定是否套用欠位箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 來調整欠位箱值。

**返回：**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

指定是否套用欠位箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 來調整欠位箱值。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

指定自動欠位箱值。若為 false：使用 UnderflowBin 屬性。

**返回：**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

指定自動欠位箱值。若為 false：使用 UnderflowBin 屬性。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

指定欠位箱自訂值。當 IsAutomaticUnderflowBin 屬性設定為 false 且 IsUnderflowBin 屬性為 true 時套用。

**返回：**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

指定欠位箱自訂值。當 IsAutomaticUnderflowBin 屬性設定為 false 且 IsUnderflowBin 屬性為 true 時套用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父投影片。只讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父簡報。只讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)