---
title: IChart
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片上的图形图表。
type: docs
url: /zh/com.aspose.slides/ichart/
---
**所有已实现的接口：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

表示幻灯片上的图形图表。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | 确定是否仅绘制可见的单元格。 |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | 确定是否仅绘制可见的单元格。 |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | 返回或设置在图表上绘制空白单元格的方式。 |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | 返回或设置在图表上绘制空白单元格的方式。 |
| [getChartData()](#getChartData--) | 返回有关与图表关联的链接或嵌入数据的信息。 |
| [hasTitle()](#hasTitle--) | 确定图表是否具有可见标题。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 确定图表是否具有可见标题。 |
| [getChartTitle()](#getChartTitle--) | 返回或设置图表标题 只读 [IChartTitle](../../com.aspose.slides/icharttitle)。 |
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
| [getBackWall()](#getBackWall--) | 返回一个对象，允许更改 3D 图表后壁的格式。 |
| [getSideWall()](#getSideWall--) | 返回一个对象，允许更改 3D 图表侧壁的格式。 |
| [getFloor()](#getFloor--) | 返回一个对象，允许更改 3D 图表地板的格式。 |
| [getUserShapes()](#getUserShapes--) | 指定绘制在图表之上的形状。 |
| [getAxes()](#getAxes--) | 提供对图表坐标轴的访问。 |
| [validateChartLayout()](#validateChartLayout--) | 计算图表元素的实际值。 |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | 指定是否应在图表的最大值上方显示数据标签。 |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | 指定是否应在图表的最大值上方显示数据标签。 |
| [hasRoundedCorners()](#hasRoundedCorners--) | 指定图表区域是否应具有圆角。 |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | 指定图表区域是否应具有圆角。 |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

确定是否仅绘制可见的单元格。若为 false，则绘制可见和隐藏的单元格。可读写布尔值。

**返回值：**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

确定是否仅绘制可见的单元格。若为 false，则绘制可见和隐藏的单元格。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

返回或设置在图表上绘制空白单元格的方式。可读写 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**返回值：**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

返回或设置在图表上绘制空白单元格的方式。可读写 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

返回有关与图表关联的链接或嵌入数据的信息。只读 [IChartData](../../com.aspose.slides/ichartdata)。

**返回值：**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

确定图表是否具有可见标题。可读写布尔值。

**返回值：**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

确定图表是否具有可见标题。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

返回或设置图表标题 只读 [IChartTitle](../../com.aspose.slides/icharttitle)。

**返回值：**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

确定图表是否具有数据表。可读写布尔值。

**返回值：**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

确定图表是否具有数据表。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

确定图表是否具有图例。可读写布尔值。

**返回值：**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

确定图表是否具有图例。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

返回图表的图例。只读 [ILegend](../../com.aspose.slides/ilegend)。

**返回值：**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

返回图表的数据表。只读 [IDataTable](../../com.aspose.slides/idatatable)。

**返回值：**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

返回或设置图表样式。可读写 [StyleType](../../com.aspose.slides/styletype)。

**返回值：**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

返回或设置图表样式。可读写 [StyleType](../../com.aspose.slides/styletype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

返回或设置图表类型。可读写 [ChartType](../../com.aspose.slides/charttype)。

**返回值：**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

返回或设置图表类型。可读写 [ChartType](../../com.aspose.slides/charttype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

表示图表的绘图区域。只读 [IChartPlotArea](../../com.aspose.slides/ichartplotarea)。

**返回值：**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

返回图表的 3D 旋转。只读 [IRotation3D](../../com.aspose.slides/irotation3d)。

**返回值：**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

返回一个对象，允许更改 3D 图表后壁的格式。只读 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

返回一个对象，允许更改 3D 图表侧壁的格式。只读 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

返回一个对象，允许更改 3D 图表地板的格式。只读 [IChartWall](../../com.aspose.slides/ichartwall)。

**返回值：**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

指定绘制在图表之上的形状。只读 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回值：**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

提供对图表坐标轴的访问。只读 [IAxesManager](../../com.aspose.slides/iaxesmanager)。

**返回值：**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

计算图表元素的实际值。实际值包括实现 IActualLayout 接口的元素的位置 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) 以及实际坐标轴值 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)。

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

指定是否应在图表的最大值上方显示数据标签。可读写布尔值。

**返回值：**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

指定是否应在图表的最大值上方显示数据标签。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

指定图表区域是否应具有圆角。可读写布尔值。

**返回值：**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

指定图表区域是否应具有圆角。可读写布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |