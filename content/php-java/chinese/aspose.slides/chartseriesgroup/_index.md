---
title: ChartSeriesGroup
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/chartseriesgroup/
---
## ChartSeriesGroup 类

 表示系列的组。
 
 1) 请参阅 ChartSeriesGroupCollection 类的摘要和备注以及 CombinableSeriesTypesGroup 枚举。  
 2) 该系列组包含一些对组中每个系列通用的系列属性（“series group properties”）。
 “Series group properties” 在 ChartSeriesGroup 类中为读/写。  
 每个 “series group properties” 在 ChartSeries 类中可以有只读投影。

### getBubbleSizeRepresentation {#getBubbleSizeRepresentation}

| 名称 | 描述 |
| --- | --- |
| getBubbleSizeRepresentation () | 指定气泡图上气泡大小值的表示方式。读/写 BubbleSizeRepresentationType。 |

 **返回值：**
int


---


### getBubbleSizeScale {#getBubbleSizeScale}

| 名称 | 描述 |
| --- | --- |
| getBubbleSizeScale () | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。读/写 int。 |

 **返回值：**
int


---


### getChart {#getChart}

| 名称 | 描述 |
| --- | --- |
| getChart () | 返回父图表。只读 IChart。 |

 **返回值：**
[Chart](../chart)


---


### getDoughnutHoleSize {#getDoughnutHoleSize}

| 名称 | 描述 |
| --- | --- |
| getDoughnutHoleSize () | 指定环形图中心孔的大小（可在绘图区大小的 0% 到 90% 之间）。读/写 byte。 |

 **返回值：**
byte


---


### getFirstSliceAngle {#getFirstSliceAngle}

| 名称 | 描述 |
| --- | --- |
| getFirstSliceAngle () | 获取或设置第一个饼形或环形切片的角度，单位为度（顺时针从上方，0 到 360 度）。读/写 int。 |

 **返回值：**
int


---


### getGapDepth {#getGapDepth}

| 名称 | 描述 |
| --- | --- |
| getGapDepth () | 返回或设置在 3D 图表中数据系列之间的距离，作为标记宽度的百分比。读/写 int。 |

 **返回值：**
int


---


### getGapWidth {#getGapWidth}

| 名称 | 描述 |
| --- | --- |
| getGapWidth () | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。读/写 int。 |

 **返回值：**
int


---


### getHiLowLinesFormat {#getHiLowLinesFormat}

| 名称 | 描述 |
| --- | --- |
| getHiLowLinesFormat () | 指定 HiLowLines 格式。HiLowLines 适用于 HiLowClose、OpenHiLowClose、VolumeHiLowClose 和 VolumeOpenHiLowClose 图表类型。 |

 **返回值：**
[ChartLinesFormat](../chartlinesformat)


---


### getOverlap {#getOverlap}

| 名称 | 描述 |
| --- | --- |
| getOverlap () | 指定条形和柱形在 2-D 图表上的重叠程度，作为百分比（-100% 到 100%）。-100%：最大间距（条形完全分离）。0%：条形并排放置且不重叠。100%：最大重叠（条形完全重叠）。该属性为读/写 byte。 |

 **返回值：**
byte

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 当值设置在 -100 到 100 的有效范围之外时抛出。 |


---


### getPieSplitBy {#getPieSplitBy}

| 名称 | 描述 |
| --- | --- |
| getPieSplitBy () | 指定如何确定在 pie-of-pie 或 bar-of-pie 图表中哪些数据点位于第二个饼形或条形中。读/写 PieSplitType。 |

 **返回值：**
int


---


### getPieSplitCustomPoints {#getPieSplitCustomPoints}

| 名称 | 描述 |
| --- | --- |
| getPieSplitCustomPoints () | 对具有自定义拆分的 pie-of-pie 或 bar-of-pie 图表的自定义拆分信息。包含应绘制在第二个饼形或条形中的数据点。只读 PieSplitCustomPointCollection。 |

 **返回值：**
[PieSplitCustomPointCollection](../piesplitcustompointcollection)


---


### getPieSplitPosition {#getPieSplitPosition}

| 名称 | 描述 |
| --- | --- |
| getPieSplitPosition () | 指定用于确定在 pie-of-pie 或 bar-of-pie 图表中哪些数据点位于第二个饼形或条形的值。与 PieSplitBy 属性一起使用。读/写 double。 |

 **返回值：**
double


---


### getPlotOnSecondAxis {#getPlotOnSecondAxis}

| 名称 | 描述 |
| --- | --- |
| getPlotOnSecondAxis () | 指示此组的系列是否绘制在次坐标轴上。只读 boolean。 |

 **返回值：**
boolean


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 FillFormat 的父演示文稿。只读 IPresentation。 |

 **返回值：**
[Presentation](../presentation)


---


### getSecondPieSize {#getSecondPieSize}

| 名称 | 描述 |
| --- | --- |
| getSecondPieSize () | 指定 pie-of-pie 或 bar-of-pie 图表中第二个饼形或条形的大小，作为第一个饼形大小的百分比（可在 5% 到 200% 之间）。读/写 int。 |

 **返回值：**
int


---


### getSeries {#getSeries}

| 名称 | 描述 |
| --- | --- |
| getSeries () | 返回系列集合。只读 IChartSeriesReadonlyCollection。 |

 **返回值：**
ChartSeriesReadonlyCollection


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回 FillFormat 的父幻灯片。只读 BaseSlide。 |

 **返回值：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getType {#getType}

| 名称 | 描述 |
| --- | --- |
| getType () | 返回此系列组的类型。只读 CombinableSeriesTypesGroup。 |

 **返回值：**
int


---


### getUpDownBars {#getUpDownBars}

| 名称 | 描述 |
| --- | --- |
| getUpDownBars () | 提供对折线图或股票图的上下柱的访问。只读 IUpDownBarsManager。 |

 **返回值：**
[UpDownBarsManager](../updownbarsmanager)


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。 |

 **返回值：**
[ChartSeries](../chartseries)


---


### hasSeriesLines {#hasSeriesLines}

| 名称 | 描述 |
| --- | --- |
| hasSeriesLines () | 如果图表具有系列线，则返回 true。适用于堆叠柱形图和 OfPie 图表。读/写 boolean。 |

 **返回值：**
boolean


---


### isColorVaried {#isColorVaried}

| 名称 | 描述 |
| --- | --- |
| isColorVaried () | 指定系列中的每个数据标记是否具有不同的颜色。读/写 boolean。 |

 **返回值：**
boolean


---


### setBubbleSizeRepresentation {#setBubbleSizeRepresentation}

| 名称 | 描述 |
| --- | --- |
| setBubbleSizeRepresentation (int) | 指定气泡图上气泡大小值的表示方式。读/写 BubbleSizeRepresentationType。 |

 **返回值：**
void


---


### setBubbleSizeScale {#setBubbleSizeScale}

| 名称 | 描述 |
| --- | --- |
| setBubbleSizeScale (int) | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。读/写 int。 |

 **返回值：**
void


---


### setColorVaried {#setColorVaried}

| 名称 | 描述 |
| --- | --- |
| setColorVaried (boolean) | 指定系列中的每个数据标记是否具有不同的颜色。读/写 boolean。 |

 **返回值：**
void


---


### setDoughnutHoleSize {#setDoughnutHoleSize}

| 名称 | 描述 |
| --- | --- |
| setDoughnutHoleSize (byte) | 指定环形图中心孔的大小（可在绘图区大小的 0% 到 90% 之间）。读/写 byte。 |

 **返回值：**
void


---


### setFirstSliceAngle {#setFirstSliceAngle}

| 名称 | 描述 |
| --- | --- |
| setFirstSliceAngle (int) | 获取或设置第一个饼形或环形切片的角度，单位为度（顺时针从上方，0 到 360 度）。读/写 int。 |

 **返回值：**
void


---


### setGapDepth {#setGapDepth}

| 名称 | 描述 |
| --- | --- |
| setGapDepth (int) | 返回或设置在 3D 图表中数据系列之间的距离，作为标记宽度的百分比。读/写 int。 |

 **返回值：**
void


---


### setGapWidth {#setGapWidth}

| 名称 | 描述 |
| --- | --- |
| setGapWidth (int) | 指定条形或柱形簇之间的间距，作为条形或柱形宽度的百分比。读/写 int。 |

 **返回值：**
void


---


### setOverlap {#setOverlap}

| 名称 | 描述 |
| --- | --- |
| setOverlap (byte) | 指定条形和柱形在 2-D 图表上的重叠程度，作为百分比（-100% 到 100%）。-100%：最大间距（条形完全分离）。0%：条形并排放置且不重叠。100%：最大重叠（条形完全重叠）。该属性为读/写 byte。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 当值设置在 -100 到 100 的有效范围之外时抛出。 |


---


### setPieSplitBy {#setPieSplitBy}

| 名称 | 描述 |
| --- | --- |
| setPieSplitBy (int) | 指定如何确定在 pie-of-pie 或 bar-of-pie 图表中哪些数据点位于第二个饼形或条形中。读/写 PieSplitType。 |

 **返回值：**
void


---


### setPieSplitPosition {#setPieSplitPosition}

| 名称 | 描述 |
| --- | --- |
| setPieSplitPosition (double) | 指定用于确定在 pie-of-pie 或 bar-of-pie 图表中哪些数据点位于第二个饼形或条形的值。与 PieSplitBy 属性一起使用。读/写 double。 |

 **返回值：**
void


---


### setSecondPieSize {#setSecondPieSize}

| 名称 | 描述 |
| --- | --- |
| setSecondPieSize (int) | 指定 pie-of-pie 或 bar-of-pie 图表中第二个饼形或条形的大小，作为第一个饼形大小的百分比（可在 5% 到 200% 之间）。读/写 int。 |

 **返回值：**
void


---


### setSeriesLines {#setSeriesLines}

| 名称 | 描述 |
| --- | --- |
| setSeriesLines (boolean) | 如果图表具有系列线，则为 true。适用于堆叠柱形图和 OfPie 图表。读/写 boolean。 |

 **返回值：**
void


---