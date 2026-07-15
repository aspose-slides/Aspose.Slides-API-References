---
title: IAxis
second_title: Aspose.Slides for Android via Java API 參考
description: 封裝代表圖表座標軸的物件。
type: docs
url: /zh-hant/com.aspose.slides/iaxis/
---
**已實作的介面：**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

封裝代表圖表座標軸的物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 表示值座標軸是否在類別之間與類別座標軸相交。 |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 表示值座標軸是否在類別之間與類別座標軸相交。 |
| [getCrossAt()](#getCrossAt--) | 表示垂直座標軸與此座標軸相交的點。 |
| [setCrossAt(float value)](#setCrossAt-float-) | 表示垂直座標軸與此座標軸相交的點。 |
| [getDisplayUnit()](#getDisplayUnit--) | 指定值座標軸顯示單位的縮放值。 |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 指定值座標軸顯示單位的縮放值。 |
| [getActualMaxValue()](#getActualMaxValue--) | 指定座標軸上的實際最大值。 |
| [getActualMinValue()](#getActualMinValue--) | 指定座標軸上的實際最小值。 |
| [getActualMajorUnit()](#getActualMajorUnit--) | 指定座標軸的實際主要單位。 |
| [getActualMinorUnit()](#getActualMinorUnit--) | 指定座標軸的實際次要單位。 |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 指定座標軸的實際主要單位比例。 |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 指定座標軸的實際次要單位比例。 |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 指示是否自動指派最大值。 |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 指示是否自動指派最大值。 |
| [getMaxValue()](#getMaxValue--) | 表示值座標軸的最大值。 |
| [setMaxValue(double value)](#setMaxValue-double-) | 表示值座標軸的最大值。 |
| [getMinorUnit()](#getMinorUnit--) | 表示日期或值座標軸的次要單位。 |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 表示日期或值座標軸的次要單位。 |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 指示是否自動指派座標軸的次要單位。 |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 指示是否自動指派座標軸的次要單位。 |
| [getMajorUnit()](#getMajorUnit--) | 表示日期或值座標軸的主要單位。 |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 表示日期或值座標軸的主要單位。 |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 指示是否自動指派座標軸的主要單位。 |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 指示是否自動指派座標軸的主要單位。 |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 指示是否自動指派最小值。 |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 指示是否自動指派最小值。 |
| [getMinValue()](#getMinValue--) | 表示值座標軸的最小值。 |
| [setMinValue(double value)](#setMinValue-double-) | 表示值座標軸的最小值。 |
| [isLogarithmic()](#isLogarithmic--) | 表示值座標軸的比例類型是否為對數。 |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 表示值座標軸的比例類型是否為對數。 |
| [getLogBase()](#getLogBase--) | 表示對數的底數。 |
| [setLogBase(double value)](#setLogBase-double-) | 表示對數的底數。 |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | 表示 Microsoft PowerPoint 是否將資料點從最後一個繪製到第一個。 |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | 表示 Microsoft PowerPoint 是否將資料點從最後一個繪製到第一個。 |
| [isVisible()](#isVisible--) | 表示座標軸是否可見。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 表示座標軸是否可見。 |
| [getMajorTickMark()](#getMajorTickMark--) | 表示指定座標軸的主要刻度標記類型。 |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 表示指定座標軸的主要刻度標記類型。 |
| [getMinorTickMark()](#getMinorTickMark--) | 表示指定座標軸的次要刻度標記類型。 |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 表示指定座標軸的次要刻度標記類型。 |
| [getTickLabelPosition()](#getTickLabelPosition--) | 表示指定座標軸上刻度標籤的位置。 |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 表示指定座標軸上刻度標籤的位置。 |
| [getMajorUnitScale()](#getMajorUnitScale--) | 表示日期座標軸的主要單位比例。 |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 表示日期座標軸的主要單位比例。 |
| [getMinorUnitScale()](#getMinorUnitScale--) | 表示日期座標軸的主要單位比例。 |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 表示日期座標軸的主要單位比例。 |
| [getBaseUnitScale()](#getBaseUnitScale--) | 指定日期座標軸上所表示的最小時間單位。 |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 指定日期座標軸上所表示的最小時間單位。 |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | 表示圖表座標軸的次要格線格式。 |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | 表示圖表座標軸的主要格線格式。 |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 表示次要格線是否顯示。 |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 表示主要格線是否顯示。 |
| [getFormat()](#getFormat--) | 表示座標軸的格式。 |
| [getTitle()](#getTitle--) | 取得座標軸的標題。 |
| [getCrossType()](#getCrossType--) | 表示指定座標軸上另一座標軸相交的 CrossType。 |
| [setCrossType(int value)](#setCrossType-int-) | 表示指定座標軸上另一座標軸相交的 CrossType。 |
| [getPosition()](#getPosition--) | 表示座標軸的位置。 |
| [setPosition(int value)](#setPosition-int-) | 表示座標軸的位置。 |
| [hasTitle()](#hasTitle--) | 判斷座標軸是否具有可見的標題。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 判斷座標軸是否具有可見的標題。 |
| [getNumberFormat()](#getNumberFormat--) | 表示座標軸標籤的格式字串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 表示座標軸標籤的格式字串。 |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 指示格式是否與來源資料連結。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 指示格式是否與來源資料連結。 |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 表示刻度標籤的旋轉角度，讀寫 float。 |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 表示刻度標籤的旋轉角度，讀寫 float。 |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 指定在已繪製的標籤之間要跳過多少個刻度標籤。 |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 指定在已繪製的標籤之間要跳過多少個刻度標籤。 |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 指定自動刻度標籤間距值。 |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 指定自動刻度標籤間距值。 |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 指定在繪製下一個刻度標記前應跳過多少個刻度標記。 |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 指定在繪製下一個刻度標記前應跳過多少個刻度標記。 |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 指定自動刻度標記間距值。 |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 指定自動刻度標記間距值。 |
| [getLabelOffset()](#getLabelOffset--) | 指定標籤與座標軸的距離。 |
| [setLabelOffset(int value)](#setLabelOffset-int-) | 指定標籤與座標軸的距離。 |
| [getCategoryAxisType()](#getCategoryAxisType--) | 指定類別座標軸的類型。 |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | 指定類別座標軸的類型。 |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 根據座標軸資料自動決定的值設定 IAxis.CategoryAxisType 屬性。 |
| [getAggregationType()](#getAggregationType--) | 表示類別座標軸的彙總類型（分箱）。 |
| [setAggregationType(int value)](#setAggregationType-int-) | 表示類別座標軸的彙總類型（分箱）。 |
| [getBinWidth()](#getBinWidth--) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。 |
| [setBinWidth(double value)](#setBinWidth-double-) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。 |
| [getNumberOfBins()](#getNumberOfBins--) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。 |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。 |
| [isOverflowBin()](#isOverflowBin--) | 指定是否套用溢位分箱。 |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | 指定是否套用溢位分箱。 |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 指定自動溢位分箱值。 |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 指定自動溢位分箱值。 |
| [getOverflowBin()](#getOverflowBin--) | 指定溢位分箱的自訂值。 |
| [setOverflowBin(double value)](#setOverflowBin-double-) | 指定溢位分箱的自訂值。 |
| [isUnderflowBin()](#isUnderflowBin--) | 指定是否套用欠位分箱。 |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | 指定是否套用欠位分箱。 |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 指定自動欠位分箱值。 |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 指定自動欠位分箱值。 |
| [getUnderflowBin()](#getUnderflowBin--) | 指定欠位分箱的自訂值。 |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | 指定欠位分箱的自訂值。 |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

表示值座標軸是否在類別之間與類別座標軸相交。此屬性僅適用於類別座標軸，且不適用於 3-D 圖表。讀寫 boolean。

**傳回：**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

表示值座標軸是否在類別之間與類別座標軸相交。此屬性僅適用於類別座標軸，且不適用於 3-D 圖表。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

表示垂直座標軸與此座標軸相交的點。讀寫 float。

**傳回：**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

表示垂直座標軸與此座標軸相交的點。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

指定值座標軸顯示單位的縮放值。讀寫 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**傳回：**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

指定值座標軸顯示單位的縮放值。讀寫 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

指定座標軸上的實際最大值。先呼叫 IChart.ValidateChartLayout() 以取得實際值。

**傳回：**
double
### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

指定座標軸上的實際最小值。先呼叫 IChart.ValidateChartLayout() 以取得實際值。

**傳回：**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

指定座標軸的實際主要單位。先呼叫 IChart.ValidateChartLayout() 以取得實際值。

**傳回：**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

指定座標軸的實際次要單位。先呼叫 IChart.ValidateChartLayout() 以取得實際值。

**傳回：**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

指定座標軸的實際主要單位比例。先呼叫 IChart.ValidateChartLayout() 以取得實際值。

**傳回：**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

指定座標軸的實際次要單位比例。先呼叫 IChart.ValidateChartLayout() 以取得實際值。

**傳回：**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

指示是否自動指派最大值。讀寫 boolean。

**傳回：**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

指示是否自動指派最大值。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

表示值座標軸的最大值。讀寫 double。

**傳回：**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

表示值座標軸的最大值。讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

表示日期或值座標軸的次要單位。讀寫 double。

**傳回：**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

表示日期或值座標軸的次要單位。讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

指示是否自動指派座標軸的次要單位。讀寫 boolean。

**傳回：**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

指示是否自動指派座標軸的次要單位。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

表示日期或值座標軸的主要單位。讀寫 double。

**傳回：**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

表示日期或值座標軸的主要單位。讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

指示是否自動指派座標軸的主要單位。讀寫 boolean。

**傳回：**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

指示是否自動指派座標軸的主要單位。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

指示是否自動指派最小值。讀寫 boolean。

**傳回：**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

指示是否自動指派最小值。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

表示值座標軸的最小值。讀寫 double。

**傳回：**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

表示值座標軸的最小值。讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

表示值座標軸的比例類型是否為對數。讀寫 boolean。

**傳回：**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

表示值座標軸的比例類型是否為對數。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

表示對數的底數。預設值為 10。讀寫 double。

**傳回：**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

表示對數的底數。預設值為 10。讀寫 double。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

表示 Microsoft PowerPoint 是否將資料點從最後一個繪製到第一個。讀寫 boolean。

**傳回：**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

表示 Microsoft PowerPoint 是否將資料點從最後一個繪製到第一個。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

表示座標軸是否可見。讀寫 boolean。

**傳回：**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

表示座標軸是否可見。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

表示指定座標軸的主要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**傳回：**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

表示指定座標軸的主要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

表示指定座標軸的次要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**傳回：**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

表示指定座標軸的次要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

表示指定座標軸上刻度標籤的位置。讀寫 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**傳回：**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

表示指定座標軸上刻度標籤的位置。讀寫 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

表示日期座標軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回：**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

表示日期座標軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

表示日期座標軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回：**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

表示日期座標軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

指定日期座標軸上所表示的最小時間單位。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回：**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

指定日期座標軸上所表示的最小時間單位。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

表示圖表座標軸的次要格線格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**傳回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

表示圖表座標軸的主要格線格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**傳回：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

表示次要格線是否顯示。唯讀 boolean。

**傳回：**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

表示主要格線是否顯示。唯讀 boolean。

**傳回：**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

表示座標軸的格式。唯讀 [IAxisFormat](../../com.aspose.slides/iaxisformat)。

**傳回：**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

取得座標軸的標題。唯讀 [IChartTitle](../../com.aspose.slides/icharttitle)。

**傳回：**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

表示指定座標軸上另一座標軸相交的 CrossType。讀寫 [CrossesType](../../com.aspose.slides/crossestype)。

**傳回：**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

表示指定座標軸上另一座標軸相交的 CrossType。讀寫 [CrossesType](../../com.aspose.slides/crossestype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

表示座標軸的位置。讀寫 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**傳回：**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

表示座標軸的位置。讀寫 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

判斷座標軸是否具有可見的標題。讀寫 boolean。

**傳回：**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

判斷座標軸是否具有可見的標題。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

表示座標軸標籤的格式字串。讀寫 String。

**傳回：**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

表示座標軸標籤的格式字串。讀寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

指示格式是否與來源資料連結。讀寫 boolean。

**傳回：**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

指示格式是否與來源資料連結。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

表示刻度標籤的旋轉角度。讀寫 float。

**傳回：**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

表示刻度標籤的旋轉角度。讀寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

指定在已繪製的標籤之間要跳過多少個刻度標籤。讀寫 long。

**傳回：**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

指定在已繪製的標籤之間要跳過多少個刻度標籤。讀寫 long。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。讀寫 boolean。

**傳回：**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

指定在繪製下一個刻度標記前應跳過多少個刻度標記。適用於類別或系列座標軸。讀寫 int。

**傳回：**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

指定在繪製下一個刻度標記前應跳過多少個刻度標記。適用於類別或系列座標軸。讀寫 int。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。讀寫 boolean。

**傳回：**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

指定標籤與座標軸的距離。適用於類別或日期座標軸。值必須介於 0% 與 1000% 之間。讀寫 int。

**傳回：**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

指定標籤與座標軸的距離。適用於類別或日期座標軸。值必須介於 0% 與 1000% 之間。讀寫 int。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

指定類別座標軸的類型。讀寫 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))。

**傳回：**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

指定類別座標軸的類型。讀寫 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

根據座標軸資料自動決定的值設定 IAxis.CategoryAxisType 屬性。

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

表示類別座標軸的彙總類型（分箱）。適用於類別。僅與 Histogram 或 HistogramPareto 系列搭配使用。

**傳回：**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

表示類別座標軸的彙總類型（分箱）。適用於類別。僅與 Histogram 或 HistogramPareto 系列搭配使用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。適用於類別座標軸。僅與 Histogram 或 HistogramPareto 系列搭配使用。

**傳回：**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。適用於類別座標軸。僅與 Histogram 或 HistogramPareto 系列搭配使用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。適用於類別座標軸。僅與 Histogram 或 HistogramPareto 系列搭配使用。

**傳回：**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。適用於類別座標軸。僅與 Histogram 或 HistogramPareto 系列搭配使用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 調整溢位分箱值。

**傳回：**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 調整溢位分箱值。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

指定自動溢位分箱值。若為 false：使用 OverflowBin 屬性。

**傳回：**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

指定自動溢位分箱值。若為 false：使用 OverflowBin 屬性。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

指定溢位分箱的自訂值。當 IsAutomaticOverflowBin 屬性為 false 且 IsOverflowBin 屬性為 true 時套用。

**傳回：**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

指定溢位分箱的自訂值。當 IsAutomaticOverflowBin 屬性為 false 且 IsOverflowBin 屬性為 true 時套用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

指定是否套用欠位分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 調整欠位分箱值。

**傳回：**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

指定是否套用欠位分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 調整欠位分箱值。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

指定自動欠位分箱值。若為 false：使用 UnderflowBin 屬性。

**傳回：**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

指定自動欠位分箱值。若為 false：使用 UnderflowBin 屬性。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

指定欠位分箱的自訂值。當 IsAutomaticUnderflowBin 屬性為 false 且 IsUnderflowBin 屬性為 true 時套用。

**傳回：**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

指定欠位分箱的自訂值。當 IsAutomaticUnderflowBin 屬性為 false 且 IsUnderflowBin 屬性為 true 時套用。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | double |  |