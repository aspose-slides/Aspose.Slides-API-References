---
title: Chart
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/chart/
---
## Chart 类

 Represents an graphic chart on a slide.
 
### createThemeEffective {#createThemeEffective}

| 名称 | 描述 |
| --- | --- |
| createThemeEffective () | 返回此图表的有效主题。 |

 **返回：**
ThemeEffectiveData


---


### getAxes {#getAxes}

| 名称 | 描述 |
| --- | --- |
| getAxes () | 提供对图表坐标轴的访问。 Read-only IAxesManager. |

 **返回：**
[AxesManager](../axesmanager)


---


### getBackWall {#getBackWall}

| 名称 | 描述 |
| --- | --- |
| getBackWall () | 返回一个对象，可更改 3D 图表背面墙的格式。 Read-only IChartWall. |

 **返回：**
[ChartWall](../chartwall)


---


### getChart {#getChart}

| 名称 | 描述 |
| --- | --- |
| getChart () |  |

 **返回：**
[Chart](../chart)


---


### getChartData {#getChartData}

| 名称 | 描述 |
| --- | --- |
| getChartData () | 返回有关与图表关联的链接或嵌入数据的信息。 Read-only IChartData. |

 **返回：**
[ChartData](../chartdata)


---


### getChartDataTable {#getChartDataTable}

| 名称 | 描述 |
| --- | --- |
| getChartDataTable () | 返回图表的数据表。 Read-only IDataTable. |

 **返回：**
[DataTable](../datatable)


---


### getChartTitle {#getChartTitle}

| 名称 | 描述 |
| --- | --- |
| getChartTitle () | 返回或设置图表标题。 Read-only IChartTitle. |

 **返回：**
[ChartTitle](../charttitle)


---


### getDisplayBlanksAs {#getDisplayBlanksAs}

| 名称 | 描述 |
| --- | --- |
| getDisplayBlanksAs () | 返回或设置在图表上绘制空单元格的方式。 Read/write DisplayBlanksAsType. |

 **返回：**
int


---


### getFloor {#getFloor}

| 名称 | 描述 |
| --- | --- |
| getFloor () | 返回一个对象，可更改 3D 图表底面的格式。 Read-only IChartWall. |

 **返回：**
[ChartWall](../chartwall)


---


### getLegend {#getLegend}

| 名称 | 描述 |
| --- | --- |
| getLegend () | 返回或设置图表的图例。 Read-only ILegend. |

 **返回：**
[Legend](../legend)


---


### getPlotArea {#getPlotArea}

| 名称 | 描述 |
| --- | --- |
| getPlotArea () | 表示图表的绘图区域。 Read-only IChartPlotArea. |

 **返回：**
[ChartPlotArea](../chartplotarea)


---


### getPlotVisibleCellsOnly {#getPlotVisibleCellsOnly}

| 名称 | 描述 |
| --- | --- |
| getPlotVisibleCellsOnly () | 确定是否仅绘制可见单元格。设置为 false 时同时绘制可见和隐藏单元格。 Read/write boolean. |

 **返回：**
boolean


---


### getRotation3D {#getRotation3D}

| 名称 | 描述 |
| --- | --- |
| getRotation3D () | 返回图表的 3D 旋转。 Read-only IRotation3D. |

 **返回：**
[Rotation3D](../rotation3d)


---


### getShowDataLabelsOverMaximum {#getShowDataLabelsOverMaximum}

| 名称 | 描述 |
| --- | --- |
| getShowDataLabelsOverMaximum () | 指定是否在图表的最大值上显示数据标签。 Read/write boolean. |

 **返回：**
boolean


---


### getSideWall {#getSideWall}

| 名称 | 描述 |
| --- | --- |
| getSideWall () | 返回一个对象，可更改 3D 图表侧墙的格式。 Read-only IChartWall. |

 **返回：**
[ChartWall](../chartwall)


---


### getStyle {#getStyle}

| 名称 | 描述 |
| --- | --- |
| getStyle () | 返回或设置图表样式。 Read/write StyleType. |

 **返回：**
int


---


### getTextFormat {#getTextFormat}

| 名称 | 描述 |
| --- | --- |
| getTextFormat () | 返回图表文本格式。以下类型不适用此属性：ChartType#Treemap、ChartType#Sunburst、ChartType#Waterfall、ChartType#Histogram、ChartType#Funnel、ChartType#BoxAndWhisker。 Read-only IChartTextFormat. |

 **返回：**
[ChartTextFormat](../charttextformat)


---


### getThemeManager {#getThemeManager}

| 名称 | 描述 |
| --- | --- |
| getThemeManager () | 返回主题管理器。 Read-only IOverrideThemeManager. |

 **返回：**
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager)


---


### getType {#getType}

| 名称 | 描述 |
| --- | --- |
| getType () | 返回或设置图表类型。 Read/write ChartType. |

 **返回：**
int


---


### getUserShapes {#getUserShapes}

| 名称 | 描述 |
| --- | --- |
| getUserShapes () | 指定绘制在图表之上的形状。 Read-only IGroupShape. |

 **返回：**
[GroupShape](../groupshape)


---


### hasDataTable {#hasDataTable}

| 名称 | 描述 |
| --- | --- |
| hasDataTable () | 确定图表是否具有数据表。 Read/write boolean. |

 **返回：**
boolean


---


### hasLegend {#hasLegend}

| 名称 | 描述 |
| --- | --- |
| hasLegend () | 确定图表是否具有图例。 Read/write boolean. |

 **返回：**
boolean


---


### hasRoundedCorners {#hasRoundedCorners}

| 名称 | 描述 |
| --- | --- |
| hasRoundedCorners () | 指定图表区域是否应具有圆角。 Read/write boolean. |

 **返回：**
boolean


---


### hasTitle {#hasTitle}

| 名称 | 描述 |
| --- | --- |
| hasTitle () | 确定图表是否具有可见标题。 Read/write boolean. |

 **返回：**
boolean


---


### setDataTable {#setDataTable}

| 名称 | 描述 |
| --- | --- |
| setDataTable (boolean) | 确定图表是否具有数据表。 Read/write boolean. |

 **返回：**
void


---


### setDisplayBlanksAs {#setDisplayBlanksAs}

| 名称 | 描述 |
| --- | --- |
| setDisplayBlanksAs (int) | 返回或设置在图表上绘制空单元格的方式。 Read/write DisplayBlanksAsType. |

 **返回：**
void


---


### setLegend {#setLegend}

| 名称 | 描述 |
| --- | --- |
| setLegend (boolean) | 确定图表是否具有图例。 Read/write boolean. |

 **返回：**
void


---


### setPlotVisibleCellsOnly {#setPlotVisibleCellsOnly}

| 名称 | 描述 |
| --- | --- |
| setPlotVisibleCellsOnly (boolean) | 确定是否仅绘制可见单元格。设置为 false 时同时绘制可见和隐藏单元格。 Read/write boolean. |

 **返回：**
void


---


### setRoundedCorners {#setRoundedCorners}

| 名称 | 描述 |
| --- | --- |
| setRoundedCorners (boolean) | 指定图表区域是否应具有圆角。 Read/write boolean. |

 **返回：**
void


---


### setShowDataLabelsOverMaximum {#setShowDataLabelsOverMaximum}

| 名称 | 描述 |
| --- | --- |
| setShowDataLabelsOverMaximum (boolean) | 指定是否在图表的最大值上显示数据标签。 Read/write boolean. |

 **返回：**
void


---


### setStyle {#setStyle}

| 名称 | 描述 |
| --- | --- |
| setStyle (int) | 返回或设置图表样式。 Read/write StyleType. |

 **返回：**
void


---


### setTitle {#setTitle}

| 名称 | 描述 |
| --- | --- |
| setTitle (boolean) | 确定图表是否具有可见标题。 Read/write boolean. |

 **返回：**
void


---


### setType {#setType}

| 名称 | 描述 |
| --- | --- |
| setType (int) | 返回或设置图表类型。 Read/write ChartType. |

 **返回：**
void


---


### validateChartLayout {#validateChartLayout}

| 名称 | 描述 |
| --- | --- |
| validateChartLayout () | 计算图表元素的实际值。实际值包括实现 IActualLayout 接口的元素位置 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) 和实际坐标轴值 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

 **返回：**
void


---