---
title: Axis
second_title: Aspose.Slides for Java API 參考文件
description: 封裝表示圖表軸的物件。
type: docs
url: /zh-hant/com.aspose.slides/axis/
---
**Inheritance:**  
繼承：  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
所有已實作的介面：  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

封裝代表圖表軸的物件。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getChart()](#getChart--) | 傳回父圖表。 |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 表示值軸是否在類別之間穿過類別軸。 |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 表示值軸是否在類別之間穿過類別軸。 |
| [getCategoryAxisType()](#getCategoryAxisType--) | 指定類別軸的類型。 |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | 指定類別軸的類型。 |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 使用根據軸資料自動決定的值設定 IAxis.CategoryAxisType 屬性。 |
| [getCrossAt()](#getCrossAt--) | 表示軸上垂直軸交叉的位置。 |
| [setCrossAt(float value)](#setCrossAt-float-) | 表示軸上垂直軸交叉的位置。 |
| [getDisplayUnit()](#getDisplayUnit--) | 指定值軸的顯示單位縮放值。 |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 指定值軸的顯示單位縮放值。 |
| [getActualMaxValue()](#getActualMaxValue--) | 指定軸上的實際最大值。 |
| [getActualMinValue()](#getActualMinValue--) | 指定軸上的實際最小值。 |
| [getActualMajorUnit()](#getActualMajorUnit--) | 指定軸的實際主要單位。 |
| [getActualMinorUnit()](#getActualMinorUnit--) | 指定軸的實際次要單位。 |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 指定軸的實際主要單位比例。 |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 指定軸的實際次要單位比例。 |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 表示是否自動分配最大值。 |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 表示是否自動分配最大值。 |
| [getMaxValue()](#getMaxValue--) | 表示值軸的最大值。 |
| [setMaxValue(double value)](#setMaxValue-double-) | 表示值軸的最大值。 |
| [getMinorUnit()](#getMinorUnit--) | 表示日期或值軸的次要單位。 |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 表示日期或值軸的次要單位。 |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 表示是否自動分配軸的次要單位。 |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 表示是否自動分配軸的次要單位。 |
| [getMajorUnit()](#getMajorUnit--) | 表示日期或值軸的主要單位。 |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 表示日期或值軸的主要單位。 |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 表示是否自動分配軸的主要單位。 |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 表示是否自動分配軸的主要單位。 |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 表示是否自動分配最小值。 |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 表示是否自動分配最小值。 |
| [getMinValue()](#getMinValue--) | 表示值軸的最小值。 |
| [setMinValue(double value)](#setMinValue-double-) | 表示值軸的最小值。 |
| [isLogarithmic()](#isLogarithmic--) | 表示值軸的比例類型是否為對數。 |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 表示值軸的比例類型是否為對數。 |
| [getLogBase()](#getLogBase--) | 表示對數基底。 |
| [setLogBase(double value)](#setLogBase-double-) | 表示對數基底。 |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | 表示 MS PowerPoint 是否從最後到第一個繪製資料點。 |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | 表示 MS PowerPoint 是否從最後到第一個繪製資料點。 |
| [isVisible()](#isVisible--) | 表示軸是否可見。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 表示軸是否可見。 |
| [getMajorTickMark()](#getMajorTickMark--) | 表示指定軸的主要刻度標記類型。 |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 表示指定軸的主要刻度標記類型。 |
| [getMinorTickMark()](#getMinorTickMark--) | 表示指定軸的次要刻度標記類型。 |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 表示指定軸的次要刻度標記類型。 |
| [getTickLabelPosition()](#getTickLabelPosition--) | 表示指定軸上刻度標籤的定位。 |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 表示指定軸上刻度標籤的定位。 |
| [getMajorUnitScale()](#getMajorUnitScale--) | 表示日期軸的主要單位比例。 |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 表示日期軸的主要單位比例。 |
| [getMinorUnitScale()](#getMinorUnitScale--) | 表示日期軸的主要單位比例。 |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 表示日期軸的主要單位比例。 |
| [getBaseUnitScale()](#getBaseUnitScale--) | 指定日期軸所表示的最小時間單位。 |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 指定日期軸所表示的最小時間單位。 |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | 表示圖表軸的次要格線格式。 |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | 表示圖表軸的主要格線格式。 |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 若要隱藏次要格線，將 MinorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。 |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 若要隱藏主要格線，將 MajorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。 |
| [getFormat()](#getFormat--) | 表示軸的格式。 |
| [getTextFormat()](#getTextFormat--) | 表示文字的格式。 |
| [getTitle()](#getTitle--) | 取得軸的標題。 |
| [getCrossType()](#getCrossType--) | 表示指定軸上另一軸交叉時的 CrossType。 |
| [setCrossType(int value)](#setCrossType-int-) | 表示指定軸上另一軸交叉時的 CrossType。 |
| [getPosition()](#getPosition--) | 表示軸的位置。 |
| [setPosition(int value)](#setPosition-int-) | 表示軸的位置。 |
| [hasTitle()](#hasTitle--) | 判斷軸是否具有可見的標題。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 判斷軸是否具有可見的標題。 |
| [getNumberFormat()](#getNumberFormat--) | 代表軸標籤的格式字串。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 代表軸標籤的格式字串。 |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 表示格式是否連結至來源資料。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 表示格式是否連結至來源資料。 |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 代表刻度標籤的旋轉角度。 |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 代表刻度標籤的旋轉角度。 |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 指定在繪製的標籤之間要跳過多少個刻度標籤。 |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 指定在繪製的標籤之間要跳過多少個刻度標籤。 |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 指定自動刻度標籤間距值。 |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 指定自動刻度標籤間距值。 |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 指定在繪製下一個刻度標記前要跳過多少個刻度標記。 |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 指定在繪製下一個刻度標記前要跳過多少個刻度標記。 |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 指定自動刻度標記間距值。 |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 指定自動刻度標記間距值。 |
| [getLabelOffset()](#getLabelOffset--) | 指定標籤與軸的距離。 |
| [setLabelOffset(int value)](#setLabelOffset-int-) | 指定標籤與軸的距離。 |
| [getAggregationType()](#getAggregationType--) | 代表類別軸的聚合類型（分箱）。 |
| [setAggregationType(int value)](#setAggregationType-int-) | 代表類別軸的聚合類型（分箱）。 |
| [getBinWidth()](#getBinWidth--) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。 |
| [setBinWidth(double value)](#setBinWidth-double-) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByBinWidth 時，指定分箱寬度。 |
| [getNumberOfBins()](#getNumberOfBins--) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。 |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | 當 AggregationType 屬性值設定為 AxisAggregationType.ByNumberOfBins 時，指定分箱數量。 |
| [isOverflowBin()](#isOverflowBin--) | 指定是否套用溢位分箱。 |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | 指定是否套用溢位分箱。 |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 指定自動溢位分箱值。 |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 指定自動溢位分箱值。 |
| [getOverflowBin()](#getOverflowBin--) | 指定自訂的溢位分箱值。 |
| [setOverflowBin(double value)](#setOverflowBin-double-) | 指定自訂的溢位分箱值。 |
| [isUnderflowBin()](#isUnderflowBin--) | 指定是否套用欠位分箱。 |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | 指定是否套用欠位分箱。 |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 指定自動欠位分箱值。 |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 指定自動欠位分箱值。 |
| [getUnderflowBin()](#getUnderflowBin--) | 指定自訂的欠位分箱值。 |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | 指定自訂的欠位分箱值。 |
| [getSlide()](#getSlide--) | 傳回 FillFormat 所屬的投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 FillFormat 所屬的簡報。 |

### getChart() {#getChart--}
```
public final IChart getChart()
```

傳回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**傳回：**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

表示值軸是否在類別之間穿過類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。可讀寫 boolean。

**傳回：**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

表示值軸是否在類別之間穿過類別軸。此屬性僅適用於類別軸，且不適用於 3-D 圖表。可讀寫 boolean。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

指定類別軸的類型。可讀寫 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)。

**傳回：**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

指定類別軸的類型。可讀寫 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

使用根據軸資料自動決定的值設定 IAxis.CategoryAxisType 屬性。

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

表示軸上垂直軸交叉的位置。可讀寫 float。

**傳回：**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

表示軸上垂直軸交叉的位置。可讀寫 float。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

指定值軸的顯示單位縮放值。可讀寫 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**傳回：**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

指定值軸的顯示單位縮放值。可讀寫 [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

指定軸上的實際最大值。先前呼叫 IChart.ValidateChartLayout() 可取得實際值。

**傳回：**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

指定軸上的實際最小值。先前呼叫 IChart.ValidateChartLayout() 可取得實際值。

**傳回：**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

指定軸的實際主要單位。先前呼叫 IChart.ValidateChartLayout() 可取得實際值。

**傳回：**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

指定軸的實際次要單位。先前呼叫 IChart.ValidateChartLayout() 可取得實際值。

**傳回：**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

指定軸的實際主要單位比例。先前呼叫 IChart.ValidateChartLayout() 可取得實際值。

**傳回：**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

指定軸的實際次要單位比例。先前呼叫 IChart.ValidateChartLayout() 可取得實際值。

**傳回：**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

表示是否自動分配最大值。可讀寫 boolean。

**傳回：**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

表示是否自動分配最大值。可讀寫 boolean。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

表示值軸的最大值。可讀寫 double。

**傳回：**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

表示值軸的最大值。可讀寫 double。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

表示日期或值軸的次要單位。可讀寫 double。

**傳回：**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

表示日期或值軸的次要單位。可讀寫 double。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
指示軸的次要單位是否自動分配。讀寫 boolean。

**傳回值：**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

指示軸的次要單位是否自動分配。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

表示日期或數值軸的主要單位。讀寫 double。

**傳回值：**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

表示日期或數值軸的主要單位。讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

指示軸的主要單位是否自動分配。讀寫 boolean。

**傳回值：**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

指示軸的主要單位是否自動分配。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

指示最小值是否自動分配。讀寫 boolean。

**傳回值：**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

指示最小值是否自動分配。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

表示數值軸上的最小值。讀寫 double。

**傳回值：**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

表示數值軸上的最小值。讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

表示數值軸的刻度類型是否為對數。讀寫 boolean。

**傳回值：**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

表示數值軸的刻度類型是否為對數。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

表示對數基底。預設值為 10。讀寫 double。

**傳回值：**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

表示對數基底。預設值為 10。讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

表示 MS PowerPoint 是否從最後到第一個繪製資料點。讀寫 boolean。

**傳回值：**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

表示 MS PowerPoint 是否從最後到第一個繪製資料點。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

表示軸是否可見。讀寫 boolean。

**傳回值：**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

表示軸是否可見。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

表示指定軸的主要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**傳回值：**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

表示指定軸的主要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

表示指定軸的次要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**傳回值：**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

表示指定軸的次要刻度標記類型。讀寫 [TickMarkType](../../com.aspose.slides/tickmarktype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

表示指定軸上刻度標籤的位置。讀寫 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**傳回值：**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

表示指定軸上刻度標籤的位置。讀寫 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

表示日期軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回值：**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

表示日期軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

表示日期軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回值：**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

表示日期軸的主要單位比例。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

指定日期軸上所表示的最小時間單位。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**傳回值：**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

指定日期軸上所表示的最小時間單位。讀寫 [TimeUnitType](../../com.aspose.slides/timeunittype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

表示圖表軸的次要格線格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**傳回值：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

表示圖表軸的主要格線格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**傳回值：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

若要隱藏次要格線，請將 MinorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。唯讀 boolean。

**傳回值：**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

若要隱藏主要格線，請將 MajorGridLinesFormat.Line.FillFormat.FillType 設為 FillType.NoFill。唯讀 boolean。

**傳回值：**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

表示軸的格式。唯讀 [IAxisFormat](../../com.aspose.slides/iaxisformat)。

**傳回值：**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

表示文字的格式。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**傳回值：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

取得軸的標題。唯讀 [IChartTitle](../../com.aspose.slides/icharttitle)。

**傳回值：**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

表示在指定軸上，另一軸交叉的位置之 CrossType。讀寫 [CrossesType](../../com.aspose.slides/crossestype)。

**傳回值：**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

表示在指定軸上，另一軸交叉的位置之 CrossType。讀寫 [CrossesType](../../com.aspose.slides/crossestype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getPosition() {#getPosition--}
```
public final int getPosition()
```

表示軸的位置。讀寫 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**傳回值：**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

表示軸的位置。讀寫 [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

判斷軸是否具有可見的標題。讀寫 boolean。

**傳回值：**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

判斷軸是否具有可見的標題。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

表示軸標籤的格式字串。讀寫 String。

**傳回值：**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

表示軸標籤的格式字串。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

指示格式是否連結至來源資料。讀寫 boolean。

**傳回值：**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

指示格式是否連結至來源資料。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

表示刻度標籤的旋轉角度。讀寫 float。

**傳回值：**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

表示刻度標籤的旋轉角度。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

指定在繪製的標籤之間要跳過多少個刻度標籤。適用於類別或序列軸。讀寫 long。

**傳回值：**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

指定在繪製的標籤之間要跳過多少個刻度標籤。適用於類別或序列軸。讀寫 long。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。讀寫 boolean。

**傳回值：**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

指定自動刻度標籤間距值。若為 false：使用 TickLabelSpacing 屬性。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

指定在繪製下一個刻度標記前應跳過多少個刻度標記。適用於類別或序列軸。讀寫 int。

**傳回值：**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

指定在繪製下一個刻度標記前應跳過多少個刻度標記。適用於類別或序列軸。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |
### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。讀寫 boolean。

**傳回值：**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

指定自動刻度標記間距值。若為 false：使用 TickMarksSpacing 屬性。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

指定標籤與軸之間的距離。適用於類別或日期軸。值必須介於 0% 與 1000% 之間。讀寫 int。

**傳回值：**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

指定標籤與軸之間的距離。適用於類別或日期軸。值必須介於 0% 與 1000% 之間。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

表示類別軸 (分箱) 的彙總類型。套用於類別。僅用於 Histogram 或 HistogramPareto 系列。

**傳回：**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

表示類別軸 (分箱) 的彙總類型。套用於類別。僅用於 Histogram 或 HistogramPareto 系列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

指定當 AggregationType 屬性值設為 AxisAggregationType.ByBinWidth 時的分箱寬度。套用於類別軸。僅用於 Histogram 或 HistogramPareto 系列。

**傳回：**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

指定當 AggregationType 屬性值設為 AxisAggregationType.ByBinWidth 時的分箱寬度。套用於類別軸。僅用於 Histogram 或 HistogramPareto 系列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

指定當 AggregationType 屬性值設為 AxisAggregationType.ByNumberOfBins 時的分箱數量。套用於類別軸。僅用於 Histogram 或 HistogramPareto 系列。

**傳回：**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

指定當 AggregationType 屬性值設為 AxisAggregationType.ByNumberOfBins 時的分箱數量。套用於類別軸。僅用於 Histogram 或 HistogramPareto 系列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 來調整溢位分箱值。

**傳回：**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

指定是否套用溢位分箱。使用 IsAutomaticOverflowBin 與 OverflowBin 來調整溢位分箱值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

指定自動溢位分箱的值。若為 false：使用 OverflowBin 屬性。

**傳回：**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

指定自動溢位分箱的值。若為 false：使用 OverflowBin 屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

指定自訂的溢位分箱值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。

**傳回：**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

指定自訂的溢位分箱值。當 IsAutomaticOverflowBin 屬性設為 false 且 IsOverflowBin 屬性為 true 時套用。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

指定是否套用下限分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 來調整下限分箱值。

**傳回：**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

指定是否套用下限分箱。使用 IsAutomaticUnderflowBin 與 UnderflowBin 來調整下限分箱值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

指定自動下限分箱的值。若為 false：使用 UnderflowBin 屬性。

**傳回：**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

指定自動下限分箱的值。若為 false：使用 UnderflowBin 屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

指定自訂的下限分箱值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。

**傳回：**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

指定自訂的下限分箱值。當 IsAutomaticUnderflowBin 屬性設為 false 且 IsUnderflowBin 屬性為 true 時套用。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回：**
[IPresentation](../../com.aspose.slides/ipresentation)