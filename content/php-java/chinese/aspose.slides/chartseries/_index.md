---
title: ChartSeries
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/chartseries/
---
## ChartSeries 类

 表示一个图表序列。

### getAutomaticSeriesColor {#getAutomaticSeriesColor}

| 名称 | 描述 |
| --- | --- |
| getAutomaticSeriesColor () | 返回基于系列索引和图表样式的自动颜色。如果 FillType 等于 NotDefined，则默认使用此颜色。 |

 **返回:**  
Color


---


### getBar3DShape {#getBar3DShape}

| 名称 | 描述 |
| --- | --- |
| getBar3DShape () | 指定 3-D 条形图系列的形状。更改此属性的值可能会导致系列类型自动更改。读/写 ChartShapeType。 |

 **返回:**  
int


---


### getBubbleSizeRepresentation {#getBubbleSizeRepresentation}

| 名称 | 描述 |
| --- | --- |
| getBubbleSizeRepresentation () | 指定气泡图上气泡大小值的表示方式。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeRepresentation 读/写属性更改值。这是属性 ParentSeriesGroup.BubbleSizeRepresentation 的投影。 |

 **返回:**  
int


---


### getBubbleSizeScale {#getBubbleSizeScale}

| 名称 | 描述 |
| --- | --- |
| getBubbleSizeScale () | 指定气泡图的比例因子（可在默认大小的 0% 到 300% 之间）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.BubbleSizeScale 读/写属性更改值。这是属性 ParentSeriesGroup.BubbleSizeScale 的投影。 |

 **返回:**  
int


---


### getChart {#getChart}

| 名称 | 描述 |
| --- | --- |
| getChart () | 返回父图表。只读 IChart。 |

 **返回:**  
[Chart](../chart)


---


### getDataPoints {#getDataPoints}

| 名称 | 描述 |
| --- | --- |
| getDataPoints () | 返回此系列的数据点集合。只读 IChartDataPointCollection。 |

 **返回:**  
[ChartDataPointCollection](../chartdatapointcollection)


---


### getDoughnutHoleSize {#getDoughnutHoleSize}

| 名称 | 描述 |
| --- | --- |
| getDoughnutHoleSize () | 指定环形图中孔的大小（可在绘图区域大小的 10% 到 90% 之间）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.DoughnutHoleSize 读/写属性更改值。只读 byte。这是属性 ParentSeriesGroup.DoughnutHoleSize 的投影。 |

 **返回:**  
byte


---


### getErrorBarsXFormat {#getErrorBarsXFormat}

| 名称 | 描述 |
| --- | --- |
| getErrorBarsXFormat () | 表示 X 方向的系列误差条。只读 IErrorBarsFormat。X 方向的误差条适用于 area、bar、scatter 和 bubble 类型的系列。对于其他类型的图表，此属性返回 null（包括 3D 图表）。如需自定义值，请使用 DataPoints 集合指定值（使用 ( IChartDataPoint#getErrorBarsCustomValues) 属性）。 |

 **返回:**  
[ErrorBarsFormat](../errorbarsformat)


---


### getErrorBarsYFormat {#getErrorBarsYFormat}

| 名称 | 描述 |
| --- | --- |
| getErrorBarsYFormat () | 表示 Y 方向的系列误差条。只读 IErrorBarsFormat。Y 方向的误差条适用于 area、bar、line、scatter 和 bubble 类型的系列。对于其他类型的图表，此属性返回 null（包括 3D 图表）。如需自定义值，请使用 DataPoints 集合指定值（使用 ( IChartDataPoint#getErrorBarsCustomValues) 属性）。 |

 **返回:**  
[ErrorBarsFormat](../errorbarsformat)


---


### getExplosion {#getExplosion}

| 名称 | 描述 |
| --- | --- |
| getExplosion () | 打开的饼图切片与饼图中心的距离以饼图直径的百分比表示。读/写 int。 |

 **返回:**  
int


---


### getFirstSliceAngle {#getFirstSliceAngle}

| 名称 | 描述 |
| --- | --- |
| getFirstSliceAngle () | 指定第一个饼图或环形图切片的角度（单位：度，顺时针从上方，范围 0 到 360 度）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.FirstSliceAngle 读/写属性更改值。只读 int。这是属性 ParentSeriesGroup.FirstSliceAngle 的投影。 |

 **返回:**  
int


---


### getFormat {#getFormat}

| 名称 | 描述 |
| --- | --- |
| getFormat () | 返回系列的格式。只读 IFormat。 |

 **返回:**  
[Format](../format)


---


### getGapDepth {#getGapDepth}

| 名称 | 描述 |
| --- | --- |
| getGapDepth () | 返回或设置 3D 图表中数据系列之间的距离（以标记宽度的百分比表示）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapDepth 读/写属性更改值。只读 int。这是属性 ParentSeriesGroup.GapDepth 的投影。 |

 **返回:**  
int


---


### getGapWidth {#getGapWidth}

| 名称 | 描述 |
| --- | --- |
| getGapWidth () | 指定条形或柱形簇之间的间距（以条形或柱形宽度的百分比表示）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.GapWidth 读/写属性更改值。只读 int。这是属性 ParentSeriesGroup.GapWidth 的投影。 |

 **返回:**  
int


---


### getInvertIfNegative {#getInvertIfNegative}

| 名称 | 描述 |
| --- | --- |
| getInvertIfNegative () | 指定如果值为负，则条形、柱形或气泡系列应反转其颜色。读/写 boolean。 |

 **返回:**  
boolean


---


### getInvertedSolidFillColor {#getInvertedSolidFillColor}

| 名称 | 描述 |
| --- | --- |
| getInvertedSolidFillColor () | 指定系列的反转实色。要应用颜色设置，请将系列格式 FillType 设置为 FillType.Solid。读/写 ColorFormat。 |

 **返回:**  
[ColorFormat](../colorformat)


---


### getLabels {#getLabels}

| 名称 | 描述 |
| --- | --- |
| getLabels () | 返回系列的 Labels。只读 IDataLabelCollection。 |

 **返回:**  
[DataLabelCollection](../datalabelcollection)


---


### getMarker {#getMarker}

| 名称 | 描述 |
| --- | --- |
| getMarker () | 标记。只读 IMarker。 |

 **返回:**  
[Marker](../marker)


---


### getName {#getName}

| 名称 | 描述 |
| --- | --- |
| getName () | 返回系列名称。只读 IStringChartValue。 |

 **返回:**  
[StringChartValue](../stringchartvalue)


---


### getNumberFormatOfBubbleSizes {#getNumberFormatOfBubbleSizes}

| 名称 | 描述 |
| --- | --- |
| getNumberFormatOfBubbleSizes () | NumberFormatOfBubbleSizes。读/写 String。 |

 **返回:**  
String


---


### getNumberFormatOfValues {#getNumberFormatOfValues}

| 名称 | 描述 |
| --- | --- |
| getNumberFormatOfValues () | NumberFormatOfValues。读/写 String。 |

 **返回:**  
String


---


### getNumberFormatOfXValues {#getNumberFormatOfXValues}

| 名称 | 描述 |
| --- | --- |
| getNumberFormatOfXValues () | NumberFormatOfXValues。读/写 String。 |

 **返回:**  
String


---


### getNumberFormatOfYValues {#getNumberFormatOfYValues}

| 名称 | 描述 |
| --- | --- |
| getNumberFormatOfYValues () | NumberFormatOfYValues。读/写 String。 |

 **返回:**  
String


---


### getOrder {#getOrder}

| 名称 | 描述 |
| --- | --- |
| getOrder () | 返回系列的顺序。读/写 int。 |

 **返回:**  
int


---


### getOverlap {#getOverlap}

| 名称 | 描述 |
| --- | --- |
| getOverlap () | 指定 2-D 图表中条形和柱形的重叠程度，以百分比表示（范围 -100% 到 100%）。此属性不仅属于本系列，还属于父系列组的所有系列。它是父系列组中相应属性的投影，因此此属性为只读。要更改该值，请使用 ParentSeriesGroup.Overlap 读/写属性。只读 byte。Overlap 指定条形和柱形之间的重叠或间距程度，以它们宽度的百分比表示：- -100%：最大间距（条形完全分离）。- 0%：条形并排放置，无重叠也无间距。- 100%：最大重叠（条形完全重叠）。这是一属性 ParentSeriesGroup.Overlap 的投影。 |

 **返回:**  
byte


---


### getParentLabelLayout {#getParentLabelLayout}

| 名称 | 描述 |
| --- | --- |
| getParentLabelLayout () | 表示父类别标签的布局。仅适用于 Treemap 图表。 |

 **返回:**  
int


---


### getParentSeriesGroup {#getParentSeriesGroup}

| 名称 | 描述 |
| --- | --- |
| getParentSeriesGroup () | ParentSeriesGroup。只读 IChartSeriesGroup。 |

 **返回:**  
[ChartSeriesGroup](../chartseriesgroup)


---


### getPieSplitBy {#getPieSplitBy}

| 名称 | 描述 |
| --- | --- |
| getPieSplitBy () | 指定如何确定哪些数据点位于饼图或柱形图的第二个饼或柱上（用于 pie-of-pie 或 bar-of-pie 图表）。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitBy 读/写属性更改值。只读 PieSplitType。1) 这是属性 ParentSeriesGroup.PieSplitBy 的投影。2) 如果属性值为 PieSplitType.Custom，则可以使用 ParentSeriesGroup.PieSplitCustomPoints 属性定义自定义拆分信息。 |

 **返回:**  
int


---


### getPieSplitCustomPoints {#getPieSplitCustomPoints}

| 名称 | 描述 |
| --- | --- |
| getPieSplitCustomPoints () | 针对具有自定义拆分的 pie-of-pie 或 bar-of-pie 图表的自定义拆分信息。包含应在第二个饼或柱中绘制的数据点。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影，只读 PieSplitCustomPointCollection。这是属性 ParentSeriesGroup.PieSplitCustomPoints 的投影。 |

 **返回:**  
[PieSplitCustomPointCollection](../piesplitcustompointcollection)


---


### getPieSplitPosition {#getPieSplitPosition}

| 名称 | 描述 |
| --- | --- |
| getPieSplitPosition () | 指定用于确定哪些数据点位于 pie-of-pie 或 bar-of-pie 图表第二个饼或柱的值。与 PieSplitBy 属性一起使用。此属性不仅属于本系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性为只读。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.PieSplitPosition 读/写属性更改值。只读 double。这是属性 ParentSeriesGroup.PieSplitPosition 的投影。 |

 **返回:**  
double


---


### getPlotOnSecondAxis {#getPlotOnSecondAxis}

| 名称 | 描述 |
| --- | --- |
| getPlotOnSecondAxis () | 指示此系列是否绘制在次坐标轴上。读/写 boolean。 |

 **返回:**  
boolean


---


### getPresentation {#getPresentation}
| --- | --- |
| getPresentation () | 返回 FillFormat 的父演示文稿。只读 IPresentation。 |

**返回：**
[Presentation](../presentation)

---

### getQuartileMethod {#getQuartileMethod}

| Name | Description |
| --- | --- |
| getQuartileMethod () | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |

**返回：**
int

---

### getRelatedLegendEntry {#getRelatedLegendEntry}

| Name | Description |
| --- | --- |
| getRelatedLegendEntry () | 表示与此系列相关的图例条目。只读 ILegendEntryProperties。 |

**返回：**
[LegendEntryProperties](../legendentryproperties)

---

### getSecondPieSize {#getSecondPieSize}

| Name | Description |
| --- | --- |
| getSecondPieSize () | 指定饼中饼图或条形饼图中第二个饼或条的大小，以第一个饼的大小的百分比表示（可以在 5 到 200 百分之间）。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.SecondPieSize 读写属性来更改值。只读 int。它是属性 ParentSeriesGroup.SecondPieSize 的投影。 |

**返回：**
int

---

### getShowConnectorLines {#getShowConnectorLines}

| Name | Description |
| --- | --- |
| getShowConnectorLines () | 表示连接线。仅适用于 Waterfall 图表。 |

**返回：**
boolean

---

### getShowInnerPoints {#getShowInnerPoints}

| Name | Description |
| --- | --- |
| getShowInnerPoints () | 表示内部点。如果在 BoxAndWhisker 图表上显示内部点，则为 True。仅适用于 BoxAndWhisker 图表。读写 boolean。 |

**返回：**
boolean

---

### getShowMeanLine {#getShowMeanLine}

| Name | Description |
| --- | --- |
| getShowMeanLine () | 表示均值线。如果在 BoxAndWhisker 图表上显示均值线，则为 True。仅适用于 BoxAndWhisker 图表。读写 boolean。 |

**返回：**
boolean

---

### getShowMeanMarkers {#getShowMeanMarkers}

| Name | Description |
| --- | --- |
| getShowMeanMarkers () | 表示均值标记。如果在 BoxAndWhisker 图表上显示均值标记，则为 True。仅适用于 BoxAndWhisker 图表。读写 boolean。 |

**返回：**
boolean

---

### getShowOutlierPoints {#getShowOutlierPoints}

| Name | Description |
| --- | --- |
| getShowOutlierPoints () | 表示异常值点。如果在 BoxAndWhisker 图表上显示异常值点，则为 True。仅适用于 BoxAndWhisker 图表。读写 boolean。 |

**返回：**
boolean

---

### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | 返回 FillFormat 的父幻灯片。只读 BaseSlide。 |

**返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### getSmooth {#getSmooth}

| Name | Description |
| --- | --- |
| getSmooth () | 表示曲线平滑。如果为折线图或散点图开启曲线平滑，则为 True。仅适用于折线和通过线连接的散点图。读写 boolean。 |

**返回：**
boolean

---

### getTrendLines {#getTrendLines}

| Name | Description |
| --- | --- |
| getTrendLines () | 系列趋势线的集合。只读 ITrendlineCollection。TrendLines 在未堆叠的 2-D 区域、条形、柱形、折线、股票、xy（散点）和气泡图表中的数据系列可用（非 null）。在任何堆叠或 3-D 的图表类型中，数据系列的趋势线不可用。趋势线也不可用于雷达图、饼图、曲面图或环形图。 |

**返回：**
[TrendlineCollection](../trendlinecollection)

---

### getType {#getType}

| Name | Description |
| --- | --- |
| getType () | 返回此系列的类型。读写 ChartType。 |

**返回：**
int

---

### hasSeriesLines {#hasSeriesLines}

| Name | Description |
| --- | --- |
| hasSeriesLines () | 确定此系列及其相关系列是否具有系列线。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.HasSeriesLines 读写属性来更改值。使用 ParentSeriesGroup.SeriesLinesFormat 属性来格式化系列线。只读 boolean。它是属性 ParentSeriesGroup.HasSeriesLines 的投影。 |

**返回：**
boolean

---

### hasUpDownBars {#hasUpDownBars}

| Name | Description |
| --- | --- |
| hasUpDownBars () | 确定折线图或股票图是否具有上下条形。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.UpDownBars.HasUpDownBars 读写属性来更改值。使用 ParentSeriesGroup.UpDownBars 属性来格式化上下条形。只读 boolean。它是属性 ParentSeriesGroup.UpDownBars.HasUpDownBars 的投影。 |

**返回：**
boolean

---

### isColorVaried {#isColorVaried}

| Name | Description |
| --- | --- |
| isColorVaried () | 指定系列中的每个数据标记具有不同的颜色。此属性不仅属于此系列，还属于父系列组的所有系列——它是相应组属性的投影。因此此属性是只读的。使用 ParentSeriesGroup 属性访问父系列组。使用 ParentSeriesGroup.IsColorVaried 读写属性来更改值。只读 boolean。它是属性 ParentSeriesGroup.IsColorVaried 的投影。 |

**返回：**
boolean

---

### setBar3DShape {#setBar3DShape}

| Name | Description |
| --- | --- |
| setBar3DShape (int) | 指定 3-D 条形图系列的形状。更改此属性的值可能会自动更改系列的 Type。读写 ChartShapeType。 |

**返回：**
void

---

### setExplosion {#setExplosion}

| Name | Description |
| --- | --- |
| setExplosion (int) | 打开的饼块与饼图中心的距离以饼直径的百分比表示。读写 int。 |

**返回：**
void

---

### setInvertIfNegative {#setInvertIfNegative}

| Name | Description |
| --- | --- |
| setInvertIfNegative (boolean) | 指定当值为负时，条形、柱形或气泡系列应反转其颜色。读写 boolean。 |

**返回：**
void

---

### setNumberFormatOfBubbleSizes {#setNumberFormatOfBubbleSizes}

| Name | Description |
| --- | --- |
| setNumberFormatOfBubbleSizes (String) | NumberFormatOfBubbleSizes。读写 String。 |

**返回：**
void

---

### setNumberFormatOfValues {#setNumberFormatOfValues}

| Name | Description |
| --- | --- |
| setNumberFormatOfValues (String) | NumberFormatOfValues。读写 String。 |

**返回：**
void

---

### setNumberFormatOfXValues {#setNumberFormatOfXValues}

| Name | Description |
| --- | --- |
| setNumberFormatOfXValues (String) | NumberFormatOfXValues。读写 String。 |

**返回：**
void

---

### setNumberFormatOfYValues {#setNumberFormatOfYValues}

| Name | Description |
| --- | --- |
| setNumberFormatOfYValues (String) | NumberFormatOfYValues。读写 String。 |

**返回：**
void

---

### setOrder {#setOrder}

| Name | Description |
| --- | --- |
| setOrder (int) | 返回系列的顺序。读写 int。 |

**返回：**
void

---

### setParentLabelLayout {#setParentLabelLayout}

| Name | Description |
| --- | --- |
| setParentLabelLayout (int) | 表示父类别标签的布局。仅适用于 Treemap 图表。 |

**返回：**
void

---

### setPlotOnSecondAxis {#setPlotOnSecondAxis}

| Name | Description |
| --- | --- |
| setPlotOnSecondAxis (boolean) | 指示此系列是否绘制在次坐标轴上。读写 boolean。 |

**返回：**
void

---

### setQuartileMethod {#setQuartileMethod}

| Name | Description |
| --- | --- |
| setQuartileMethod (int) | 表示四分位方法。仅适用于 BoxAndWhisker 图表。 |

**返回：**
void

---

### setShowConnectorLines {#setShowConnectorLines}

| Name | Description |
| --- | --- |
| setShowConnectorLines (boolean) | 表示连接线。仅适用于 Waterfall 图表。 |

**返回：**
void

---

### setShowInnerPoints {#setShowInnerPoints}

| Name | Description |
| --- | --- |
| setShowInnerPoints (boolean) | 表示内部点。如果在 BoxAndWhisker 图表上显示内部点，则为 True。仅适用于 BoxAndWhisker 图表。读写 boolean。 |

**返回：**
void

---

### setShowMeanLine {#setShowMeanLine}

| Name | Description |
| --- | --- |
| setShowMeanLine (boolean) | 表示均值线。如果在 BoxAndWhisker 图表上显示均值线，则为 True。仅适用于 BoxAndWhisker 图表。读写 boolean。 |

**返回：**
void

---

### setShowMeanMarkers {#setShowMeanMarkers}

| Name | Description |
| --- | --- |
| setShowMeanMarkers (boolean) | 表示均值标记。如果在 BoxAndWhisker 图表上显示均值标记，则为 True。仅适用于 BoxAndWhisker 图表。读写 boolean。 |

**返回：**
void

---

### setShowOutlierPoints {#setShowOutlierPoints}

| Name | Description |
| --- | --- |
| setShowOutlierPoints (boolean) | 表示异常值点。如果在 BoxAndWhisker 图表上显示异常值点，则为 True。仅适用于 BoxAndWhisker 图表。读写 boolean。 |

**返回：**
void

---

### setSmooth {#setSmooth}

| Name | Description |
| --- | --- |
| setSmooth (boolean) | 表示曲线平滑。如果为折线图或散点图开启曲线平滑，则为 True。仅适用于折线和通过线连接的散点图。读写 boolean。 |

**返回：**
void

---

### setType {#setType}

| Name | Description |
| --- | --- |
| setType (int) | 返回此系列的类型。读写 ChartType。 |

**返回：**
void

---