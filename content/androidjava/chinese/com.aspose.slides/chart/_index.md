---
title: Chart
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示幻灯片上的图形图表。
type: docs
url: /zh/com.aspose.slides/chart/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有实现的接口:**  
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)  
```
public class Chart extends GraphicalObject implements IChart
```

表示幻灯片上的图形图表。

## 方法

| 方法 | 描述 |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | 计算图表元素的实际值。 |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | 确定是否仅绘制可见单元格。 |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | 确定是否仅绘制可见单元格。 |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | 返回或设置在图表上绘制空白单元格的方式。 |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | 返回或设置在图表上绘制空白单元格的方式。 |
| [getChartData()](#getChartData--) | 返回与图表关联的链接或嵌入数据的信息。 |
| [hasTitle()](#hasTitle--) | 确定图表是否具有可见标题。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 确定图表是否具有可见标题。 |
| [getChartTitle()](#getChartTitle--) | 返回或设置图表标题。 |
| [hasDataTable()](#hasDataTable--) | 确定图表是否具有数据表。 |
| [setDataTable(boolean value)](#setDataTable-boolean-) | 确定图表是否具有数据表。 |
| [hasLegend()](#hasLegend--) | 确定图表是否具有图例。 |
| [setLegend(boolean value)](#setLegend-boolean-) | 确定图表是否具有图例。 |
| [getLegend()](#getLegend--) | 返回或设置图表的图例。 |
| [getChartDataTable()](#getChartDataTable--) | 返回图表的数据表。 |
| [getStyle()](#getStyle--) | 返回或设置图表样式。 |
| [setStyle(int value)](#setStyle-int-) | 返回或设置图表样式。 |
| [getType()](#getType--) | 返回或设置图表类型。 |
| [setType(int value)](#setType-int-) | 返回或设置图表类型。 |
| [getPlotArea()](#getPlotArea--) | 表示图表的绘图区域。 |
| [getRotation3D()](#getRotation3D--) | 返回图表的 3D 旋转。 |
| [getBackWall()](#getBackWall--) | 返回一个对象，可更改 3D 图表背墙的格式。 |
| [getSideWall()](#getSideWall--) | 返回一个对象，可更改 3D 图表侧墙的格式。 |
| [getFloor()](#getFloor--) | 返回一个对象，可更改 3D 图表底面的格式。 |
| [getTextFormat()](#getTextFormat--) | 返回图表文本格式。 |
| [createThemeEffective()](#createThemeEffective--) | 返回此图表的有效主题。 |
| [getThemeManager()](#getThemeManager--) | 返回主题管理器。 |
| [getUserShapes()](#getUserShapes--) | 指定绘制在图表顶部的形状。 |
| [getAxes()](#getAxes--) | 提供对图表坐标轴的访问。 |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | 指定是否在图表最大值上方显示数据标签。 |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | 指定是否在图表最大值上方显示数据标签。 |
| [hasRoundedCorners()](#hasRoundedCorners--) | 指定图表区域应具有圆角。 |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | 指定图表区域应具有圆角。 |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

计算图表元素的实际值。实际值包括实现 IActualLayout 接口的元素的位置 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) 和实际轴值 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)。

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

确定是否仅绘制可见单元格。若为 false，则绘制可见和隐藏的单元格。读/写 boolean。

**返回:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

确定是否仅绘制可见单元格。若为 false，则绘制可见和隐藏的单元格。读/写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

返回或设置在图表上绘制空白单元格的方式。读/写 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**返回:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

返回或设置在图表上绘制空白单元格的方式。读/写 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

返回与图表关联的链接或嵌入数据的信息。只读 [IChartData](../../com.aspose.slides/ichartdata)。

**返回:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

确定图表是否具有可见标题。读/写 boolean。

**返回:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

确定图表是否具有可见标题。读/写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

返回或设置图表标题。只读 [IChartTitle](../../com.aspose.slides/icharttitle)。

**返回:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

确定图表是否具有数据表。读/写 boolean。

**返回:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

确定图表是否具有数据表。读/写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

确定图表是否具有图例。读/写 boolean。

**返回:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

确定图表是否具有图例。读/写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

返回或设置图表的图例。只读 [ILegend](../../com.aspose.slides/ilegend)。

**返回:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

返回图表的数据表。只读 [IDataTable](../../com.aspose.slides/idatatable)。

**返回:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

返回或设置图表样式。读/写 [StyleType](../../com.aspose.slides/styletype)。

**返回:**  
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

返回或设置图表样式。读/写 [StyleType](../../com.aspose.slides/styletype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

返回或设置图表类型。读/写 [ChartType](../../com.aspose.slides/charttype)。

**返回:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

返回或设置图表类型。读/写 [ChartType](../../com.aspose.slides/charttype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

表示图表的绘图区域。只读 [IChartPlotArea](../../com.aspose.slides/ichartplotarea)。

**返回:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

返回图表的 3D 旋转。只读 [IRotation3D](../../com.aspose.slides/irotation3d)。

**返回:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

返回一个对象，可更改 3D 图表背墙的格式。只读 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

返回一个对象，可更改 3D 图表侧墙的格式。只读 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

返回一个对象，可更改 3D 图表底面的格式。只读 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回图表文本格式。此属性不适用于以下类型：[ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker)。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

返回此图表的有效主题。

**返回:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

返回主题管理器。只读 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**返回:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

指定绘制在图表顶部的形状。只读 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

提供对图表坐标轴的访问。只读 [IAxesManager](../../com.aspose.slides/iaxesmanager)。

**返回:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

指定是否在图表最大值上方显示数据标签。读/写 boolean。

**返回:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

指定是否在图表最大值上方显示数据标签。读/写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

指定图表区域应具有圆角。读/写 boolean。

**返回:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

指定图表区域应具有圆角。读/写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回:**  
[IChart](../../com.aspose.slides/ichart)