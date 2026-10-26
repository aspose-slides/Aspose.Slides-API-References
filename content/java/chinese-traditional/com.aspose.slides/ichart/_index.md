---
title: IChart
second_title: Aspose.Slides for Java API 參考
description: 表示投影片上的圖形圖表。
type: docs
url: /zh-hant/com.aspose.slides/ichart/
---
**所有已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

表示投影片上的圖形圖表。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | 判斷是否僅繪製可見的儲存格。 |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | 判斷是否僅繪製可見的儲存格。 |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | 取得或設定圖表上繪製空白儲存格的方式。 |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | 取得或設定圖表上繪製空白儲存格的方式。 |
| [getChartData()](#getChartData--) | 取得有關圖表所連結或嵌入資料的資訊。 |
| [hasTitle()](#hasTitle--) | 判斷圖表是否具有可見的標題。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 判斷圖表是否具有可見的標題。 |
| [getChartTitle()](#getChartTitle--) | 取得或設定圖表標題（唯讀 [IChartTitle](../../com.aspose.slides/icharttitle)）。 |
| [hasDataTable()](#hasDataTable--) | 判斷圖表是否具有資料表。 |
| [setDataTable(boolean value)](#setDataTable-boolean-) | 判斷圖表是否具有資料表。 |
| [hasLegend()](#hasLegend--) | 判斷圖表是否具有圖例。 |
| [setLegend(boolean value)](#setLegend-boolean-) | 判斷圖表是否具有圖例。 |
| [getLegend()](#getLegend--) | 取得或設定圖表的圖例。 |
| [getChartDataTable()](#getChartDataTable--) | 取得圖表的資料表。 |
| [getStyle()](#getStyle--) | 取得或設定圖表樣式。 |
| [setStyle(int value)](#setStyle-int-) | 取得或設定圖表樣式。 |
| [getType()](#getType--) | 取得或設定圖表類型。 |
| [setType(int value)](#setType-int-) | 取得或設定圖表類型。 |
| [getPlotArea()](#getPlotArea--) | 表示圖表的繪圖區域。 |
| [getRotation3D()](#getRotation3D--) | 取得圖表的 3D 旋轉。 |
| [getBackWall()](#getBackWall--) | 取得可變更 3D 圖表背牆格式的物件。 |
| [getSideWall()](#getSideWall--) | 取得可變更 3D 圖表側牆格式的物件。 |
| [getFloor()](#getFloor--) | 取得可變更 3D 圖表底部格式的物件。 |
| [getUserShapes()](#getUserShapes--) | 指定繪製於圖表之上的形狀。 |
| [getAxes()](#getAxes--) | 提供對圖表坐標軸的存取。 |
| [validateChartLayout()](#validateChartLayout--) | 計算圖表元素的實際值。 |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | 指定是否顯示超過圖表最大值的資料標籤。 |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | 指定是否顯示超過圖表最大值的資料標籤。 |
| [hasRoundedCorners()](#hasRoundedCorners--) | 指定圖表區域具有圓角。 |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | 指定圖表區域具有圓角。 |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

判斷是否僅繪製可見的儲存格。若為 false，則同時繪製可見與隱藏的儲存格。可讀寫布林值。

**返回值：**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

判斷是否僅繪製可見的儲存格。若為 false，則同時繪製可見與隱藏的儲存格。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

取得或設定圖表上繪製空白儲存格的方式。可讀寫 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**返回值：**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

取得或設定圖表上繪製空白儲存格的方式。可讀寫 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

取得有關圖表所連結或嵌入資料的資訊。唯讀 [IChartData](../../com.aspose.slides/ichartdata)。

**返回值：**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

判斷圖表是否具有可見的標題。可讀寫布林值。

**返回值：**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

判斷圖表是否具有可見的標題。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

取得或設定圖表標題（唯讀 [IChartTitle](../../com.aspose.slides/icharttitle)）。

**返回值：**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

判斷圖表是否具有資料表。可讀寫布林值。

**返回值：**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

判斷圖表是否具有資料表。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

判斷圖表是否具有圖例。可讀寫布林值。

**返回值：**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

判斷圖表是否具有圖例。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

取得或設定圖表的圖例。唯讀 [ILegend](../../com.aspose.slides/ilegend)。

**返回值：**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

取得圖表的資料表。唯讀 [IDataTable](../../com.aspose.slides/idatatable)。

**返回值：**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

取得或設定圖表樣式。可讀寫 [StyleType](../../com.aspose.slides/styletype)。

**返回值：**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

取得或設定圖表樣式。可讀寫 [StyleType](../../com.aspose.slides/styletype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

取得或設定圖表類型。可讀寫 [ChartType](../../com.aspose.slides/charttype)。

**返回值：**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

取得或設定圖表類型。可讀寫 [ChartType](../../com.aspose.slides/charttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

表示圖表的繪圖區域。唯讀 [IChartPlotArea](../../com.aspose.slides/ichartplotarea)。

**返回值：**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

取得圖表的 3D 旋轉。唯讀 [IRotation3D](../../com.aspose.slides/irotation3d)。

**返回值：**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

取得可變更 3D 圖表背牆格式的物件。唯讀 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

取得可變更 3D 圖表側牆格式的物件。唯讀 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

取得可變更 3D 圖表底部格式的物件。唯讀 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

指定繪製於圖表之上的形狀。唯讀 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回值：**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

提供對圖表坐標軸的存取。唯讀 [IAxesManager](../../com.aspose.slides/iaxesmanager)。

**返回值：**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

計算圖表元素的實際值。實際值包括實作 IActualLayout 介面的元素之位置 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) 以及實際坐標軸值 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)。

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

指定是否顯示超過圖表最大值的資料標籤。可讀寫布林值。

**返回值：**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

指定是否顯示超過圖表最大值的資料標籤。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

指定圖表區域是否具有圓角。可讀寫布林值。

**返回值：**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

指定圖表區域是否具有圓角。可讀寫布林值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |