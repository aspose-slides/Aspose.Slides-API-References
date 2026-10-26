---
title: Chart
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示投影片上的圖形圖表。
type: docs
url: /zh-hant/com.aspose.slides/chart/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

表示投影片上的圖形圖表。
## 方法

| 方法 | 說明 |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | 計算圖表元素的實際值。 |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | 判斷是否僅繪製可見儲存格。 |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | 判斷是否僅繪製可見儲存格。 |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | 取得或設定在圖表上繪製空白儲存格的方式。 |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | 取得或設定在圖表上繪製空白儲存格的方式。 |
| [getChartData()](#getChartData--) | 取得與圖表相關聯的連結或嵌入資料資訊。 |
| [hasTitle()](#hasTitle--) | 判斷圖表是否具有可見的標題。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 判斷圖表是否具有可見的標題。 |
| [getChartTitle()](#getChartTitle--) | 取得或設定圖表標題。 |
| [hasDataTable()](#hasDataTable--) | 判斷圖表是否具有資料表格。 |
| [setDataTable(boolean value)](#setDataTable-boolean-) | 判斷圖表是否具有資料表格。 |
| [hasLegend()](#hasLegend--) | 判斷圖表是否具有圖例。 |
| [setLegend(boolean value)](#setLegend-boolean-) | 判斷圖表是否具有圖例。 |
| [getLegend()](#getLegend--) | 取得或設定圖表的圖例。 |
| [getChartDataTable()](#getChartDataTable--) | 取得圖表的資料表格。 |
| [getStyle()](#getStyle--) | 取得或設定圖表樣式。 |
| [setStyle(int value)](#setStyle-int-) | 取得或設定圖表樣式。 |
| [getType()](#getType--) | 取得或設定圖表類型。 |
| [setType(int value)](#setType-int-) | 取得或設定圖表類型。 |
| [getPlotArea()](#getPlotArea--) | 代表圖表的繪圖區域。 |
| [getRotation3D()](#getRotation3D--) | 取得圖表的 3D 旋轉。 |
| [getBackWall()](#getBackWall--) | 取得一個物件，可變更 3D 圖表背牆的格式。 |
| [getSideWall()](#getSideWall--) | 取得一個物件，可變更 3D 圖表側牆的格式。 |
| [getFloor()](#getFloor--) | 取得一個物件，可變更 3D 圖表底面的格式。 |
| [getTextFormat()](#getTextFormat--) | 取得圖表文字格式。 |
| [createThemeEffective()](#createThemeEffective--) | 取得此圖表的有效佈景主題。 |
| [getThemeManager()](#getThemeManager--) | 取得佈景主題管理器。 |
| [getUserShapes()](#getUserShapes--) | 指定繪製於圖表之上的形狀。 |
| [getAxes()](#getAxes--) | 提供存取圖表座標軸的功能。 |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | 指定是否在圖表的最大值上方顯示資料標籤。 |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | 指定是否在圖表的最大值上方顯示資料標籤。 |
| [hasRoundedCorners()](#hasRoundedCorners--) | 指定圖表區域是否具有圓角。 |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | 指定圖表區域是否具有圓角。 |
| [getChart()](#getChart--) |  |
### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```


計算圖表元素的實際值。實際值包含實作 IActualLayout 介面的元素位置 (IActualLayout.ActualX、IActualLayout.ActualY、IActualLayout.ActualWidth、IActualLayout.ActualHeight) 以及實際座標軸值 (IAxis.ActualMaxValue、IAxis.ActualMinValue、IAxis.ActualMajorUnit、IAxis.ActualMinorUnit、IAxis.ActualMajorUnitScale、IAxis.ActualMinorUnitScale)。

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```


判斷是否僅繪製可見儲存格。若為 false，則同時繪製可見和隱藏的儲存格。可讀寫布林值。

**返回值：**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```


判斷是否僅繪製可見儲存格。若為 false，則同時繪製可見和隱藏的儲存格。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```


取得或設定在圖表上繪製空白儲存格的方式。可讀寫 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**返回值：**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```


取得或設定在圖表上繪製空白儲存格的方式。可讀寫 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```


取得與圖表相關聯的連結或嵌入資料資訊。唯讀 [IChartData](../../com.aspose.slides/ichartdata)。

**返回值：**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


判斷圖表是否具有可見的標題。可讀寫布林值。

**返回值：**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


判斷圖表是否具有可見的標題。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```


取得或設定圖表標題。唯讀 [IChartTitle](../../com.aspose.slides/icharttitle)。

**返回值：**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```


判斷圖表是否具有資料表格。可讀寫布林值。

**返回值：**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```


判斷圖表是否具有資料表格。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```


判斷圖表是否具有圖例。可讀寫布林值。

**返回值：**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```


判斷圖表是否具有圖例。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```


取得或設定圖表的圖例。唯讀 [ILegend](../../com.aspose.slides/ilegend)。

**返回值：**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```


取得圖表的資料表格。唯讀 [IDataTable](../../com.aspose.slides/idatatable)。

**返回值：**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```


取得或設定圖表樣式。可讀寫 [StyleType](../../com.aspose.slides/styletype)。

**返回值：**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


取得或設定圖表樣式。可讀寫 [StyleType](../../com.aspose.slides/styletype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```


取得或設定圖表類型。可讀寫 [ChartType](../../com.aspose.slides/charttype)。

**返回值：**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


取得或設定圖表類型。可讀寫 [ChartType](../../com.aspose.slides/charttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```


代表圖表的繪圖區域。唯讀 [IChartPlotArea](../../com.aspose.slides/ichartplotarea)。

**返回值：**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```


取得圖表的 3D 旋轉。唯讀 [IRotation3D](../../com.aspose.slides/irotation3d)。

**返回值：**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```


取得一個物件，可變更 3D 圖表背牆的格式。唯讀 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```


取得一個物件，可變更 3D 圖表側牆的格式。唯讀 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```


取得一個物件，可變更 3D 圖表底面的格式。唯讀 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


取得圖表文字格式。此屬性不適用於以下類型：[ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap)、[ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst)、[ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)、[ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram)、[ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel)、[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)。唯讀 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回值：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


取得此圖表的有效佈景主題。

**返回值：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


取得佈景主題管理器。唯讀 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**返回值：**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```


指定繪製於圖表之上的形狀。唯讀 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回值：**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```


提供存取圖表座標軸的功能。唯讀 [IAxesManager](../../com.aspose.slides/iaxesmanager)。

**返回值：**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```


指定是否在圖表的最大值上方顯示資料標籤。可讀寫布林值。

**返回值：**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```


指定是否在圖表的最大值上方顯示資料標籤。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```


指定圖表區域是否具有圓角。可讀寫布林值。

**返回值：**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```


指定圖表區域是否具有圓角。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```


取得圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**返回值：**
[IChart](../../com.aspose.slides/ichart)