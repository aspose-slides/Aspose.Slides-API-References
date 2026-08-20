---
title: IAxis
second_title: Aspose.Slides for Java API 參考
description: 封裝代表圖表軸的物件。
type: docs
url: /zh-hant/com.aspose.slides/iaxis/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

封裝表示圖表軸的物件。

## Methods

| 方法 | 說明 |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 表示數值軸是否在類別之間跨越類別軸。 |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 表示數值軸是否在類別之間跨越類別軸。 |
| [getCrossAt()](#getCrossAt--) | 表示垂直軸與該軸相交的點。 |
| [setCrossAt(float value)](#setCrossAt-float-) | 表示垂直軸與該軸相交的點。 |
| [getDisplayUnit()](#getDisplayUnit--) | 指定數值軸顯示單位的比例值。 |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 指定數值軸顯示單位的比例值。 |
| [getActualMaxValue()](#getActualMaxValue--) | 指定軸上的實際最大值。 |
| [getActualMinValue()](#getActualMinValue--) | 指定軸上的實際最小值。 |
| [getActualMajorUnit()](#getActualMajorUnit--) | 指定軸的實際主要單位。 |
| [getActualMinorUnit()](#getActualMinorUnit--) | 指定軸的實際次要單位。 |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 指定軸的實際主要單位比例。 |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 指定軸的實際次要單位比例。 |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 指示是否自動指派最大值。 |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 指示是否自動指派最大值。 |
| [getMaxValue()](#getMaxValue--) | 表示數值軸上的最大值。 |
| [setMaxValue(double value)](#setMaxValue-double-) | 表示數值軸上的最大值。 |
| [getMinorUnit()](#getMinorUnit--) | 表示日期或數值軸的次要單位。 |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 表示日期或數值軸的次要單位。 |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 指示是否自動指派軸的次要單位。 |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 指示是否自動指派軸的次要單位。 |
| [getMajorUnit()](#getMajorUnit--) | 表示日期或數值軸的主要單位。 |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 表示日期或數值軸的主要單位。 |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 指示是否自動指派軸的主要單位。 |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 指示是否自動指派軸的主要單位。 |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 指示是否自動指派最小值。 |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 指示是否自動指派最小值。 |
| [getMinValue()](#getMinValue--) | 表示數值軸上的最小值。 |
| [setMinValue(double value)](#setMinValue-double-) | 表示數值軸上的最小值。 |
| [isLogarithmic()](#isLogarithmic--) | 表示數值軸的刻度類型是否為對數。 |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 表示數值軸的刻度類型是否為對數。 |
| [getLogBase()](#getLogBase--) | 表示對數的底數。 |
| [setLogBase(double value)](#setLogBase-double-) | 表示對數的底數。 |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | 表示 MS PowerPoint 是否從最後到第一繪製資料點。 |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | 表示 MS PowerPoint 是否從最後到第一繪製資料點。 |
| [isVisible()](#isVisible--) | 表示軸是否可見。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 表示軸是否可見。 |
| [getMajorTickMark()](#getMajorTickMark--) | 表示指定軸的主要刻度標記類型。 |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 表示指定軸的主要刻度標記類型。 |
| [getMinorTickMark()](#getMinorTickMark--) | 表示指定軸的次要刻度標記類型。 |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 表示指定軸的次要刻度標記類型。 |
| [getTickLabelPosition()](#getTickLabelPosition--) | 表示指定軸上刻度標籤的位置。 |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 表示指定軸上刻度標籤的位置。 |
| [getMajorUnitScale()](#getMajorUnitScale--) | 表示日期軸的主要單位比例。 |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 表示日期軸的主要單位比例。 |
| [getMinorUnitScale()](#getMinorUnitScale--) | 表示日期軸的主要單位比例。 |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 表示日期軸的主要單位比例。 |
| [getBaseUnitScale()](#getBaseUnitScale--) | 指定日期軸上所表示的最小時間單位。 |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 指定日期軸上所表示的最小時間單位。 |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | 表示圖表軸上次要格線的格式。 |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | 表示圖表軸上主要格線的格式。 |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 表示是否顯示次要格線。 |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 表示是否顯示主要格線。 |
| [getFormat()](#getFormat--) | 表示軸的格式。 |
| [getTitle()](#getTitle--) | 取得軸的標題。 |
| [getCrossType()](#getCrossType--) | 表示在指定軸上另一軸交叉的位置之交叉類型。 |
| [setCrossType(int value)](#setCrossType-int-) | 表示在指定軸上另一軸交叉的位置之交叉類型。 |
| [getPosition()](#getPosition--) | 表示軸的位置。 |
| [setPosition(int value)](#setPosition-int-) | 表示軸的位置。 |
| [hasTitle()](#hasTitle--) | 確定軸是否具有可見的標題。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 確定軸是否具有可見的標題。 |
| [getNumberFormat()](#getNumberFormat--) | 表示軸標籤的格式字串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 表示軸標籤的格式字串。 |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 指示該格式是否連結至來源資料。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 指示該格式是否連結至來源資料。 |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 表示刻度標籤的旋轉角度。可讀寫浮點數。 |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 表示刻度標籤的旋轉角度。可讀寫浮點數。 |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 指定在繪製的標籤之間要跳過多少個刻度標籤。 |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 指定在繪製的標籤之間要跳過多少個刻度標籤。 |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 指定自動刻度標籤間距的值。 |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 指定自動刻度標籤間距的值。 |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 指定在繪製下一個刻度標記前要跳過多少個刻度標記。 |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 指定在繪製下一個刻度標記前要跳過多少個刻度標記。 |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 指定自動刻度標記間距的值。 |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 指定自動刻度標記間距的值。 |
| [getLabelOffset()](#getLabelOffset--) | 指定標籤與軸之間的距離。 |
| [setLabelOffset(int value)](#setLabelOffset-int-) | 指定標籤與軸之間的距離。 |
| [getCategoryAxisType()](#getCategoryAxisType--) | 指定類別軸的類型。 |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | 指定類別軸的類型。 |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 設定 IAxis.CategoryAxisType 屬性，使用根據軸資料自動決定的值。 |
| [getAggregationType()](#getAggregationType--) | 表示類別軸的聚合類型（分箱）。 |
| [setAggregationType(int value)](#setAggregationType-int-) | 表示類別軸的聚合類型（分箱）。 |
| [getBinWidth()](#getBinWidth--) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。 |
| [setBinWidth(double value)](#setBinWidth-double-) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。 |
| [getNumberOfBins()](#getNumberOfBins--) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。 |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。 |
| [isOverflowBin()](#isOverflowBin--) | 指定是否套用溢位分箱。 |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | 指定是否套用溢位分箱。 |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 指定自動溢位分箱的值。 |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 指定自動溢位分箱的值。 |
| [getOverflowBin()](#getOverflowBin--) | 指定自訂的溢位分箱值。 |
| [setOverflowBin(double value)](#setOverflowBin-double-) | 指定自訂的溢位分箱值。 |
| [isUnderflowBin()](#isUnderflowBin--) | 指定是否套用下溢分箱。 |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | 指定是否套用下溢分箱。 |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 指定自動下溢分箱的值。 |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 指定自動下溢分箱的值。 |
| [getUnderflowBin()](#getUnderflowBin--) | 指定自訂的下溢分箱值。 |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | 指定自訂的下溢分箱值。 |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

表示數值軸是否在類別之間跨越類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。可讀寫布林值。

**返回:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

表示數值軸是否在類別之間跨越類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。可讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

表示垂直軸與該軸相交的點。可讀寫浮點數。

**返回:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

表示垂直軸與該軸相交的點。可讀寫浮點數。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

指定數值軸顯示單位的比例值。可讀寫 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**返回:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

指定數值軸顯示單位的比例值。可讀寫 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

指定軸上的實際最大值。先前呼叫方法 IChart.ValidateChartLayout() 以取得實際值。

**返回:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

指定軸上的實際最小值。先前呼叫方法 IChart.ValidateChartLayout() 以取得實際值。

**返回:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

指定軸的實際主要單位。先前呼叫方法 IChart.ValidateChartLayout() 以取得實際值。

**返回:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

指定軸的實際次要單位。先前呼叫方法 IChart.ValidateChartLayout() 以取得實際值。

**返回:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

指定軸的實際主要單位比例。先前呼叫方法 IChart.ValidateChartLayout() 以取得實際值。

**返回:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

指定軸的實際次要單位比例。先前呼叫方法 IChart.ValidateChartLayout() 以取得實際值。

**返回:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

指示是否自動指派最大值。可讀寫布林值。

**返回:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

指示是否自動指派最大值。可讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

表示數值軸上的最大值。可讀寫 double。

**返回:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

表示數值軸上的最大值。可讀寫 double。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

表示日期或數值軸的次要單位。可讀寫 double。

**返回:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

表示日期或數值軸的次要單位。可讀寫 double。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

指示是否自動指派軸的次要單位。可讀寫布林值。

**返回:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

指示是否自動指派軸的次要單位。可讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

表示日期或數值軸的主要單位。可讀寫 double。

**返回:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

表示日期或數值軸的主要單位。可讀寫 double。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

指示是否自動指派軸的主要單位。可讀寫布林值。

**返回:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

指示軸的主要單位是否自動指定。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

指示最小值是否自動指定。讀寫 boolean。

**傳回值：**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

指示最小值是否自動指定。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

表示值軸上的最小值。讀寫 double。

**傳回值：**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

表示值軸上的最小值。讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

表示值軸的比例類型是否為對數。讀寫 boolean。

**傳回值：**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

表示值軸的比例類型是否為對數。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

表示對數基底。預設值為 10。讀寫 double。

**傳回值：**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

表示對數基底。預設值為 10。讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

表示 MS PowerPoint 是否從最後一個資料點開始繪製。讀寫 boolean。

**傳回值：**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

表示 MS PowerPoint 是否從最後一個資料點開始繪製。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

表示軸是否可見。讀寫 boolean。

**傳回值：**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

表示軸是否可見。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

表示指定軸的主要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**傳回值：**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

表示指定軸的主要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

表示指定軸的次要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**傳回值：**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

表示指定軸的次要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

表示指定軸的刻度標籤位置。讀寫 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**傳回值：**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

表示指定軸的刻度標籤位置。讀寫 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

表示日期軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回值：**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

表示日期軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

表示日期軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回值：**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

表示日期軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

指定日期軸上所表示的最小時間單位。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回值：**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

指定日期軸上所表示的最小時間單位。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

表示圖表軸的次要格線格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**傳回值：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

表示圖表軸的主要格線格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**傳回值：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

表示是否顯示次要格線。唯讀 boolean。

**傳回值：**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

表示是否顯示主要格線。唯讀 boolean。

**傳回值：**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

表示軸的格式。唯讀 [IAxisFormat](../../com.aspose.slides/iaxisformat)。

**傳回值：**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

取得軸的標題。唯讀 [IChartTitle](../../com.aspose.slides/icharttitle)。

**傳回值：**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

表示指定軸上另一軸交叉的 CrossType。讀寫 [CrossesType](../../com.aspose.slides/crossestype)。

**傳回值：**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

表示指定軸上另一軸交叉的 CrossType。讀寫 [CrossesType](../../com.aspose.slides/crossestype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

表示軸的位置。讀寫 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**傳回值：**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

表示軸的位置。讀寫 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

判斷軸是否具有可見的標題。讀寫 boolean。

**傳回值：**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

判斷軸是否具有可見的標題。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

表示軸標籤的格式字串。讀寫 String。

**傳回值：**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

表示軸標籤的格式字串。讀寫 String。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

指示格式是否連結至來源資料。讀寫 boolean。

**傳回值：**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

指示格式是否連結至來源資料。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

表示刻度標籤的旋轉角度。讀寫 float。

**傳回值：**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

表示刻度標籤的旋轉角度。讀寫 float。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

指定在繪製之間要跳過多少個刻度標籤。讀寫 long。

**傳回值：**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

指定在繪製之間要跳過多少個刻度標籤。讀寫 long。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
``` 
public abstract boolean isAutomaticTickLabelSpacing()
```

指定自動刻度標籤間距值。若為 false，使用 TickLabelSpacing 屬性。讀寫 boolean。

**傳回值：**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

指定自動刻度標籤間距值。若為 false，使用 TickLabelSpacing 屬性。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

指定在繪製下一個刻度標記前要跳過多少個刻度標記。適用於類別或系列軸。讀寫 int。

**傳回值：**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

指定在繪製下一個刻度標記前要跳過多少個刻度標記。適用於類別或系列軸。讀寫 int。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

指定自動刻度標記間距值。若為 false，使用 TickMarksSpacing 屬性。讀寫 boolean。

**傳回值：**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

指定自動刻度標記間距值。若為 false，使用 TickMarksSpacing 屬性。讀寫 boolean。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

指定標籤距離軸的距離。適用於類別或日期軸。值必須介於 0% 與 1000% 之間。讀寫 int。

**傳回值：**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

指定標籤距離軸的距離。適用於類別或日期軸。值必須介於 0% 與 1000% 之間。讀寫 int。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

指定類別軸的類型。讀寫 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))。

**傳回值：**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

指定類別軸的類型。讀寫 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

設定 IAxis.CategoryAxisType 屬性，其值會根據軸資料自動決定。

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

表示類別軸的彙總類型（分箱）。適用於類別。僅於 Histogram 或 HistogramPareto 系列使用。

**傳回值：**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

表示類別軸的彙總類型（分箱）。適用於類別。僅於 Histogram 或 HistogramPareto 系列使用。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

指定在 AggregationType 屬性值設為 AxisAggregationType.ByBinWidth 時的箱寬。套用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。

**回傳值:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

指定在 AggregationType 屬性值設為 AxisAggregationType.ByBinWidth 時的箱寬。套用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

指定在 AggregationType 屬性值設為 AxisAggregationType.ByNumberOfBins 時的箱數。套用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。

**回傳值:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

指定在 AggregationType 屬性值設為 AxisAggregationType.ByNumberOfBins 時的箱數。套用於類別軸。僅在 Histogram 或 HistogramPareto 系列中使用。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

指定是否套用溢位箱。使用 IsAutomaticOverflowBin 和 OverflowBin 來調整溢位箱的值。

**回傳值:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```




```

指定是否套用溢位箱。使用 IsAutomaticOverflowBin 和 OverflowBin 來調整溢位箱的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

指定自動溢位箱的值。若為 false，則使用 OverflowBin 屬性。

**回傳值:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

指定自動溢位箱的值。若為 false，則使用 OverflowBin 屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

指定溢位箱的自訂值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。

**回傳值:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

指定溢位箱的自訂值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

指定是否套用欠位箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 來調整欠位箱的值。

**回傳值:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

指定是否套用欠位箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 來調整欠位箱的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

指定自動欠位箱的值。若為 false，則使用 UnderflowBin 屬性。

**回傳值:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

指定自動欠位箱的值。若為 false，則使用 UnderflowBin 屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

指定欠位箱的自訂值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。

**回傳值:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

指定欠位箱的自訂值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |