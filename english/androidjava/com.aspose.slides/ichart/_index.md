---
title: IChart
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an graphic chart on a slide.
type: docs
weight: 682
url: /androidjava/com.aspose.slides/ichart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Represents an graphic chart on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determines whether the only visible cells are plotted. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determines whether the only visible cells are plotted. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Returns or sets the way to plot blank cells on a chart. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Returns or sets the way to plot blank cells on a chart. |
| [getChartData()](#getChartData--) | Returns information about the linked or embedded data associated with a chart. |
| [hasTitle()](#hasTitle--) | Determines whether a chart has a visible title. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determines whether a chart has a visible title. |
| [getChartTitle()](#getChartTitle--) | Returns or sets a chart title Read-only [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Determines whether a chart has a data table. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Determines whether a chart has a data table. |
| [hasLegend()](#hasLegend--) | Determines whether a chart has a legend. |
| [setLegend(boolean value)](#setLegend-boolean-) | Determines whether a chart has a legend. |
| [getLegend()](#getLegend--) | Returns or sets a legend for a chart. |
| [getChartDataTable()](#getChartDataTable--) | Returns a data table of a chart. |
| [getStyle()](#getStyle--) | Returns or sets the chart style. |
| [setStyle(int value)](#setStyle-int-) | Returns or sets the chart style. |
| [getType()](#getType--) | Returns or sets the chart type. |
| [setType(int value)](#setType-int-) | Returns or sets the chart type. |
| [getPlotArea()](#getPlotArea--) | Represents the plot area of a chart. |
| [getRotation3D()](#getRotation3D--) | Returns a 3D rotation of a chart. |
| [getBackWall()](#getBackWall--) | Returns an object which allows to change format of the back wall of a 3D chart. |
| [getSideWall()](#getSideWall--) | Returns an object which allows to change format of the side wall of a 3D chart. |
| [getFloor()](#getFloor--) | Returns an object which allows to change format of the floor of a 3D chart. |
| [getUserShapes()](#getUserShapes--) | Specify the shapes drawn on top of the chart. |
| [getAxes()](#getAxes--) | Provide access to chart axes. |
| [validateChartLayout()](#validateChartLayout--) | Calculates actual values of chart elements. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Specifies data labels over the maximum of the chart shall be shown. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Specifies data labels over the maximum of the chart shall be shown. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Specifies the chart area shall have rounded corners. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Specifies the chart area shall have rounded corners. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```


Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean.

**Returns:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```


Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```


Returns or sets the way to plot blank cells on a chart. Read/write [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Returns:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```


Returns or sets the way to plot blank cells on a chart. Read/write [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```


Returns information about the linked or embedded data associated with a chart. Read-only [IChartData](../../com.aspose.slides/ichartdata).

**Returns:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```


Determines whether a chart has a visible title. Read/write boolean.

**Returns:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```


Determines whether a chart has a visible title. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```


Returns or sets a chart title Read-only [IChartTitle](../../com.aspose.slides/icharttitle).

**Returns:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```


Determines whether a chart has a data table. Read/write boolean.

**Returns:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```


Determines whether a chart has a data table. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```


Determines whether a chart has a legend. Read/write boolean.

**Returns:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```


Determines whether a chart has a legend. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```


Returns or sets a legend for a chart. Read-only [ILegend](../../com.aspose.slides/ilegend).

**Returns:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```


Returns a data table of a chart. Read-only [IDataTable](../../com.aspose.slides/idatatable).

**Returns:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```


Returns or sets the chart style. Read/write [StyleType](../../com.aspose.slides/styletype).

**Returns:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```


Returns or sets the chart style. Read/write [StyleType](../../com.aspose.slides/styletype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```


Returns or sets the chart type. Read/write [ChartType](../../com.aspose.slides/charttype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Returns or sets the chart type. Read/write [ChartType](../../com.aspose.slides/charttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```


Represents the plot area of a chart. Read-only [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Returns:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```


Returns a 3D rotation of a chart. Read-only [IRotation3D](../../com.aspose.slides/irotation3d).

**Returns:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```


Returns an object which allows to change format of the back wall of a 3D chart. Read-only [IChartWall](../../com.aspose.slides/ichartwall).

**Returns:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```


Returns an object which allows to change format of the side wall of a 3D chart. Read-only [IChartWall](../../com.aspose.slides/ichartwall).

**Returns:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```


Returns an object which allows to change format of the floor of a 3D chart. Read-only [IChartWall](../../com.aspose.slides/ichartwall).

**Returns:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```


Specify the shapes drawn on top of the chart. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```


Provide access to chart axes. Read-only [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Returns:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```


Calculates actual values of chart elements. Actual values inlude position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```


Specifies data labels over the maximum of the chart shall be shown. Read/write boolean.

**Returns:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```


Specifies data labels over the maximum of the chart shall be shown. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```


Specifies the chart area shall have rounded corners. Read/write boolean.

**Returns:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```


Specifies the chart area shall have rounded corners. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

