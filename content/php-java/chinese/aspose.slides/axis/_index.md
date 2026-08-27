---
title: Axis
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/axis/
---
## Axis 类

封装表示图表轴的对象。

### getActualMajorUnit {#getActualMajorUnit}

| 名称 | 描述 |
| --- | --- |
| getActualMajorUnit () | 指定轴的实际主单位。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |

**返回：**
double


---


### getActualMajorUnitScale {#getActualMajorUnitScale}

| 名称 | 描述 |
| --- | --- |
| getActualMajorUnitScale () | 指定轴的实际主单位比例。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |

**返回：**
int


---


### getActualMaxValue {#getActualMaxValue}

| 名称 | 描述 |
| --- | --- |
| getActualMaxValue () | 指定轴上的实际最大值。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |

**返回：**
double


---


### getActualMinValue {#getActualMinValue}

| 名称 | 描述 |
| --- | --- |
| getActualMinValue () | 指定轴上的实际最小值。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |

**返回：**
double


---


### getActualMinorUnit {#getActualMinorUnit}

| 名称 | 描述 |
| --- | --- |
| getActualMinorUnit () | 指定轴的实际次单位。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |

**返回：**
double


---


### getActualMinorUnitScale {#getActualMinorUnitScale}

| 名称 | 描述 |
| --- | --- |
| getActualMinorUnitScale () | 指定轴的实际次单位比例。请先调用方法 IChart.ValidateChartLayout() 以获取实际值。 |

**返回：**
int


---


### getAggregationType {#getAggregationType}

| 名称 | 描述 |
| --- | --- |
| getAggregationType () | 表示分类轴的聚合类型（分箱）。适用于分类轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |

**返回：**
int


---


### getAxisBetweenCategories {#getAxisBetweenCategories}

| 名称 | 描述 |
| --- | --- |
| getAxisBetweenCategories () | 表示数值轴是否在分类之间穿过分类轴。此属性仅适用于分类轴，不适用于 3-D 图表。读/写 boolean。 |

**返回：**
boolean


---


### getBaseUnitScale {#getBaseUnitScale}

| 名称 | 描述 |
| --- | --- |
| getBaseUnitScale () | 指定日期轴上表示的最小时间单位。读/写 TimeUnitType。 |

**返回：**
int


---


### getBinWidth {#getBinWidth}

| 名称 | 描述 |
| --- | --- |
| getBinWidth () | 当 AggregationType 属性值设为 AxisAggregationType.ByBinWidth 时指定分箱宽度。适用于分类轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |

**返回：**
double


---


### getCategoryAxisType {#getCategoryAxisType}

| 名称 | 描述 |
| --- | --- |
| getCategoryAxisType () | 指定分类轴的类型。读/写 CategoryAxisType。 |

**返回：**
int


---


### getChart {#getChart}

| 名称 | 描述 |
| --- | --- |
| getChart () | 返回父图表。只读 IChart。 |

**返回：**
[Chart](../chart)


---


### getCrossAt {#getCrossAt}

| 名称 | 描述 |
| --- | --- |
| getCrossAt () | 表示另一轴垂直交叉该轴的点。读/写 float。 |

**返回：**
float


---


### getCrossType {#getCrossType}

| 名称 | 描述 |
| --- | --- |
| getCrossType () | 表示在指定轴上另一轴交叉时的 CrossType。读/写 CrossesType。 |

**返回：**
int


---


### getDisplayUnit {#getDisplayUnit}

| 名称 | 描述 |
| --- | --- |
| getDisplayUnit () | 指定数值轴的显示单位的缩放值。读/写 DisplayUnitType。 |

**返回：**
int


---


### getFormat {#getFormat}

| 名称 | 描述 |
| --- | --- |
| getFormat () | 表示轴的格式。只读 IAxisFormat。 |

**返回：**
[AxisFormat](../axisformat)


---


### getLabelOffset {#getLabelOffset}

| 名称 | 描述 |
| --- | --- |
| getLabelOffset () | 指定标签与轴的距离。适用于分类轴或日期轴。值必须在 0% 到 1000% 之间。读/写 int。 |

**返回：**
int


---


### getLogBase {#getLogBase}

| 名称 | 描述 |
| --- | --- |
| getLogBase () | 表示对数底数。默认值为 10。读/写 double。 |

**返回：**
double


---


### getMajorGridLinesFormat {#getMajorGridLinesFormat}

| 名称 | 描述 |
| --- | --- |
| getMajorGridLinesFormat () | 表示图表轴上的主网格线格式。只读 IChartLinesFormat。 |

**返回：**
[ChartLinesFormat](../chartlinesformat)


---


### getMajorTickMark {#getMajorTickMark}

| 名称 | 描述 |
| --- | --- |
| getMajorTickMark () | 表示指定轴的主刻度标记类型。读/写 TickMarkType。 |

**返回：**
int


---


### getMajorUnit {#getMajorUnit}

| 名称 | 描述 |
| --- | --- |
| getMajorUnit () | 表示日期轴或数值轴的主要单位。读/写 double。 |

**返回：**
double


---


### getMajorUnitScale {#getMajorUnitScale}

| 名称 | 描述 |
| --- | --- |
| getMajorUnitScale () | 表示日期轴的主单位比例。读/写 TimeUnitType。 |

**返回：**
int


---


### getMaxValue {#getMaxValue}

| 名称 | 描述 |
| --- | --- |
| getMaxValue () | 表示数值轴上的最大值。读/写 double。 |

**返回：**
double


---


### getMinValue {#getMinValue}

| 名称 | 描述 |
| --- | --- |
| getMinValue () | 表示数值轴上的最小值。读/写 double。 |

**返回：**
double


---


### getMinorGridLinesFormat {#getMinorGridLinesFormat}

| 名称 | 描述 |
| --- | --- |
| getMinorGridLinesFormat () | 表示图表轴上的次网格线格式。只读 IChartLinesFormat。 |

**返回：**
[ChartLinesFormat](../chartlinesformat)


---


### getMinorTickMark {#getMinorTickMark}

| 名称 | 描述 |
| --- | --- |
| getMinorTickMark () | 表示指定轴的次刻度标记类型。读/写 TickMarkType。 |

**返回：**
int


---


### getMinorUnit {#getMinorUnit}

| 名称 | 描述 |
| --- | --- |
| getMinorUnit () | 表示日期轴或数值轴的次单位。读/写 double。 |

**返回：**
double


---


### getMinorUnitScale {#getMinorUnitScale}

| 名称 | 描述 |
| --- | --- |
| getMinorUnitScale () | 表示日期轴的主单位比例。读/写 TimeUnitType。 |

**返回：**
int


---


### getNumberFormat {#getNumberFormat}

| 名称 | 描述 |
| --- | --- |
| getNumberFormat () | 表示轴标签的格式字符串。读/写 String。 |

**返回：**
String


---


### getNumberOfBins {#getNumberOfBins}

| 名称 | 描述 |
| --- | --- |
| getNumberOfBins () | 当 AggregationType 属性值设为 AxisAggregationType.ByNumberOfBins 时指定分箱数量。适用于分类轴。仅在 Histogram 或 HistogramPareto 系列中使用。 |

**返回：**
long


---


### getOverflowBin {#getOverflowBin}

| 名称 | 描述 |
| --- | --- |
| getOverflowBin () | 指定溢出分箱的自定义值。用于 IsAutomaticOverflowBin 属性设为 false 且 IsOverflowBin 属性为 true 时。 |

**返回：**
double


---


### getPosition {#getPosition}

| 名称 | 描述 |
| --- | --- |
| getPosition () | 表示轴的位置。读/写 AxisPositionType。 |

**返回：**
int


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 FillFormat 的父演示文稿。只读 IPresentation。 |

**返回：**
[Presentation](../presentation)


---


### getShowMajorGridLines {#getShowMajorGridLines}

| 名称 | 描述 |
| --- | --- |
| getShowMajorGridLines () | 若要隐藏主网格线，请将 MajorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。只读 boolean。 |

**返回：**
boolean


---


### getShowMinorGridLines {#getShowMinorGridLines}

| 名称 | 描述 |
| --- | --- |
| getShowMinorGridLines () | 若要隐藏次网格线，请将 MinorGridLinesFormat.Line.FillFormat.FillType 设置为 FillType.NoFill。只读 boolean。 |

**返回：**
boolean


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回 FillFormat 的父幻灯片。只读 BaseSlide。 |

**返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getTextFormat {#getTextFormat}

| 名称 | 描述 |
| --- | --- |
| getTextFormat () | 表示文本的格式。只读 IChartTextFormat。 |

**返回：**
[ChartTextFormat](../charttextformat)


---


### getTickLabelPosition {#getTickLabelPosition}

| 名称 | 描述 |
| --- | --- |
| getTickLabelPosition () | 表示指定轴上刻度标签的位置。读/写 TickLabelPositionType。 |

**返回：**
int


---


### getTickLabelRotationAngle {#getTickLabelRotationAngle}

| 名称 | 描述 |
| --- | --- |
| getTickLabelRotationAngle () | 表示刻度标签的旋转角度。读/写 float。 |

**返回：**
float


---


### getTickLabelSpacing {#getTickLabelSpacing}

| 名称 | 描述 |
| --- | --- |
| getTickLabelSpacing () | 指定在绘制的标签之间要跳过的刻度标签数量。适用于分类轴或系列轴。读/写 long。 |

**返回：**
long


---


### getTickMarksSpacing {#getTickMarksSpacing}

| 名称 | 描述 |
| --- | --- |
| getTickMarksSpacing () | 指定在绘制下一个刻度线之前要跳过的刻度线数量。适用于分类轴或系列轴。读/写 int。 |

**返回：**
long


---


### getTitle {#getTitle}

| 名称 | 描述 |
| --- | --- |
| getTitle () | 获取轴的标题。只读 IChartTitle。 |

**返回：**
[ChartTitle](../charttitle)


---


### getUnderflowBin {#getUnderflowBin}

| 名称 | 描述 |
| --- | --- |
| getUnderflowBin () | 指定下溢分箱的自定义值。用于 IsAutomaticUnderflowBin 属性设为 false 且 IsUnderflowBin 属性为 true 时。 |

**返回：**
double


---


### hasTitle {#hasTitle}

| 名称 | 描述 |
| --- | --- |
| hasTitle () | 确定轴是否具有可见标题。读/写 boolean。 |

**返回：**
boolean


---


### isAutomaticMajorUnit {#isAutomaticMajorUnit}

| 名称 | 描述 |
| --- | --- |
| isAutomaticMajorUnit () | 指示轴的主单位是否自动分配。读/写 boolean。 |

**返回：**
boolean


---


### isAutomaticMaxValue {#isAutomaticMaxValue}

| 名称 | 描述 |
| --- | --- |
| isAutomaticMaxValue () | 指示最大值是否自动分配。读/写 boolean。 |

**返回：**
boolean


---


### isAutomaticMinValue {#isAutomaticMinValue}

| 名称 | 描述 |
| --- | --- |
| isAutomaticMinValue () | 指示最小值是否自动分配。读/写 boolean。 |

**返回：**
boolean


---


### isAutomaticMinorUnit {#isAutomaticMinorUnit}

| 名称 | 描述 |
| --- | --- |
| isAutomaticMinorUnit () | 指示轴的次单位是否自动分配。读/写 boolean。 |

**返回：**
boolean


---


### isAutomaticOverflowBin {#isAutomaticOverflowBin}

| 名称 | 描述 |
| --- | --- |
| isAutomaticOverflowBin () | 指定自动溢出分箱的值。如果为 false：使用 OverflowBin 属性。 |

**返回：**
boolean


---


### isAutomaticTickLabelSpacing {#isAutomaticTickLabelSpacing}

| 名称 | 描述 |
| --- | --- |
| isAutomaticTickLabelSpacing () | 指定自动刻度标签间距的值。如果为 false：使用 TickLabelSpacing 属性。读/写 boolean。 |

**返回：**
boolean


---


### isAutomaticTickMarksSpacing {#isAutomaticTickMarksSpacing}

| 名称 | 描述 |
| --- | --- |
| isAutomaticTickMarksSpacing () | 指定自动刻度线间距的值。如果为 false：使用 TickMarksSpacing 属性。读/写 boolean。 |

**返回：**
boolean


---
### isAutomaticUnderflowBin {#isAutomaticUnderflowBin}

| 名称 | 描述 |
| --- | --- |
| isAutomaticUnderflowBin () | 指定自动下溢箱的值。如果为 false：使用 UnderflowBin 属性。 |

 **返回值:**
boolean


---


### isLogarithmic {#isLogarithmic}

| 名称 | 描述 |
| --- | --- |
| isLogarithmic () | 表示值轴的刻度类型是否为对数。可读写 boolean。 |

 **返回值:**
boolean


---


### isNumberFormatLinkedToSource {#isNumberFormatLinkedToSource}

| 名称 | 描述 |
| --- | --- |
| isNumberFormatLinkedToSource () | 指示格式是否链接到源数据。可读写 boolean。 |

 **返回值:**
boolean


---


### isOverflowBin {#isOverflowBin}

| 名称 | 描述 |
| --- | --- |
| isOverflowBin () | 指定是否应用溢出箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出箱的值。 |

 **返回值:**
boolean


---


### isPlotOrderReversed {#isPlotOrderReversed}

| 名称 | 描述 |
| --- | --- |
| isPlotOrderReversed () | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。可读写 boolean。 |

 **返回值:**
boolean


---


### isUnderflowBin {#isUnderflowBin}

| 名称 | 描述 |
| --- | --- |
| isUnderflowBin () | 指定是否应用下溢箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下溢箱的值。 |

 **返回值:**
boolean


---


### isVisible {#isVisible}

| 名称 | 描述 |
| --- | --- |
| isVisible () | 表示轴是否可见。可读写 boolean。 |

 **返回值:**
boolean


---


### setAggregationType {#setAggregationType}

| 名称 | 描述 |
| --- | --- |
| setAggregationType (int) | 表示分类轴（分箱）的聚合类型。仅适用于直方图或 HistogramPareto 系列。 |

 **返回值:**
void


---


### setAutomaticMajorUnit {#setAutomaticMajorUnit}

| 名称 | 描述 |
| --- | --- |
| setAutomaticMajorUnit (boolean) | 指示轴的主单位是否自动分配。可读写 boolean。 |

 **返回值:**
void


---


### setAutomaticMaxValue {#setAutomaticMaxValue}

| 名称 | 描述 |
| --- | --- |
| setAutomaticMaxValue (boolean) | 指示最大值是否自动分配。可读写 boolean。 |

 **返回值:**
void


---


### setAutomaticMinValue {#setAutomaticMinValue}

| 名称 | 描述 |
| --- | --- |
| setAutomaticMinValue (boolean) | 指示最小值是否自动分配。可读写 boolean。 |

 **返回值:**
void


---


### setAutomaticMinorUnit {#setAutomaticMinorUnit}

| 名称 | 描述 |
| --- | --- |
| setAutomaticMinorUnit (boolean) | 指示轴的次单位是否自动分配。可读写 boolean。 |

 **返回值:**
void


---


### setAutomaticOverflowBin {#setAutomaticOverflowBin}

| 名称 | 描述 |
| --- | --- |
| setAutomaticOverflowBin (boolean) | 指定自动溢出箱的值。如果为 false：使用 OverflowBin 属性。 |

 **返回值:**
void


---


### setAutomaticTickLabelSpacing {#setAutomaticTickLabelSpacing}

| 名称 | 描述 |
| --- | --- |
| setAutomaticTickLabelSpacing (boolean) | 指定自动刻度标签间距的值。如果为 false：使用 TickLabelSpacing 属性。可读写 boolean。 |

 **返回值:**
void


---


### setAutomaticTickMarksSpacing {#setAutomaticTickMarksSpacing}

| 名称 | 描述 |
| --- | --- |
| setAutomaticTickMarksSpacing (boolean) | 指定自动刻度线间距的值。如果为 false：使用 TickMarksSpacing 属性。可读写 boolean。 |

 **返回值:**
void


---


### setAutomaticUnderflowBin {#setAutomaticUnderflowBin}

| 名称 | 描述 |
| --- | --- |
| setAutomaticUnderflowBin (boolean) | 指定自动下溢箱的值。如果为 false：使用 UnderflowBin 属性。 |

 **返回值:**
void


---


### setAxisBetweenCategories {#setAxisBetweenCategories}

| 名称 | 描述 |
| --- | --- |
| setAxisBetweenCategories (boolean) | 表示值轴是否在分类轴之间交叉。此属性仅适用于分类轴，并且不适用于 3-D 图表。可读写 boolean。 |

 **返回值:**
void


---


### setBaseUnitScale {#setBaseUnitScale}

| 名称 | 描述 |
| --- | --- |
| setBaseUnitScale (int) | 指定日期轴上表示的最小时间单位。可读写 TimeUnitType。 |

 **返回值:**
void


---


### setBinWidth {#setBinWidth}

| 名称 | 描述 |
| --- | --- |
| setBinWidth (double) | 当 AggregationType 属性值设为 AxisAggregationType.ByBinWidth 时指定分箱宽度。仅适用于分类轴，且仅用于直方图或 HistogramPareto 系列。 |

 **返回值:**
void


---


### setCategoryAxisType {#setCategoryAxisType}

| 名称 | 描述 |
| --- | --- |
| setCategoryAxisType (int) | 指定分类轴的类型。可读写 CategoryAxisType。 |

 **返回值:**
void


---


### setCategoryAxisTypeAutomatically {#setCategoryAxisTypeAutomatically}

| 名称 | 描述 |
| --- | --- |
| setCategoryAxisTypeAutomatically () | 根据轴数据自动确定并设置 IAxis.CategoryAxisType 属性的值。 |

 **返回值:**
void


---


### setCrossAt {#setCrossAt}

| 名称 | 描述 |
| --- | --- |
| setCrossAt (float) | 表示另一轴垂直交叉轴时的交叉点位置。可读写 float。 |

 **返回值:**
void


---


### setCrossType {#setCrossType}

| 名称 | 描述 |
| --- | --- |
| setCrossType (int) | 表示指定轴上另一轴交叉的 CrossType。可读写 CrossesType。 |

 **返回值:**
void


---


### setDisplayUnit {#setDisplayUnit}

| 名称 | 描述 |
| --- | --- |
| setDisplayUnit (int) | 指定值轴显示单位的缩放值。可读写 DisplayUnitType。 |

 **返回值:**
void


---


### setLabelOffset {#setLabelOffset}

| 名称 | 描述 |
| --- | --- |
| setLabelOffset (int) | 指定标签相对于轴的距离。适用于分类轴或日期轴。取值必须在 0% 到 1000% 之间。可读写 int。 |

 **返回值:**
void


---


### setLogBase {#setLogBase}

| 名称 | 描述 |
| --- | --- |
| setLogBase (double) | 表示对数基数。默认值为 10。可读写 double。 |

 **返回值:**
void


---


### setLogarithmic {#setLogarithmic}

| 名称 | 描述 |
| --- | --- |
| setLogarithmic (boolean) | 表示值轴的刻度类型是否为对数。可读写 boolean。 |

 **返回值:**
void


---


### setMajorTickMark {#setMajorTickMark}

| 名称 | 描述 |
| --- | --- |
| setMajorTickMark (int) | 表示指定轴的主刻度标记类型。可读写 TickMarkType。 |

 **返回值:**
void


---


### setMajorUnit {#setMajorUnit}

| 名称 | 描述 |
| --- | --- |
| setMajorUnit (double) | 表示日期或值轴的主单位。可读写 double。 |

 **返回值:**
void


---


### setMajorUnitScale {#setMajorUnitScale}

| 名称 | 描述 |
| --- | --- |
| setMajorUnitScale (int) | 表示日期轴的主单位比例。可读写 TimeUnitType。 |

 **返回值:**
void


---


### setMaxValue {#setMaxValue}

| 名称 | 描述 |
| --- | --- |
| setMaxValue (double) | 表示值轴上的最大值。可读写 double。 |

 **返回值:**
void


---


### setMinValue {#setMinValue}

| 名称 | 描述 |
| --- | --- |
| setMinValue (double) | 表示值轴上的最小值。可读写 double。 |

 **返回值:**
void


---


### setMinorTickMark {#setMinorTickMark}

| 名称 | 描述 |
| --- | --- |
| setMinorTickMark (int) | 表示指定轴的次刻度标记类型。可读写 TickMarkType。 |

 **返回值:**
void


---


### setMinorUnit {#setMinorUnit}

| 名称 | 描述 |
| --- | --- |
| setMinorUnit (double) | 表示日期或值轴的次单位。可读写 double。 |

 **返回值:**
void


---


### setMinorUnitScale {#setMinorUnitScale}

| 名称 | 描述 |
| --- | --- |
| setMinorUnitScale (int) | 表示日期轴的主单位比例。可读写 TimeUnitType。 |

 **返回值:**
void


---


### setNumberFormat {#setNumberFormat}

| 名称 | 描述 |
| --- | --- |
| setNumberFormat (String) | 表示轴标签的格式字符串。可读写 String。 |

 **返回值:**
void


---


### setNumberFormatLinkedToSource {#setNumberFormatLinkedToSource}

| 名称 | 描述 |
| --- | --- |
| setNumberFormatLinkedToSource (boolean) | 指示格式是否链接到源数据。可读写 boolean。 |

 **返回值:**
void


---


### setNumberOfBins {#setNumberOfBins}

| 名称 | 描述 |
| --- | --- |
| setNumberOfBins (long) | 当 AggregationType 属性值设为 AxisAggregationType.ByNumberOfBins 时指定分箱数量。仅适用于分类轴，且仅用于直方图或 HistogramPareto 系列。 |

 **返回值:**
void


---


### setOverflowBin {#setOverflowBin}

| 名称 | 描述 |
| --- | --- |
| setOverflowBin (boolean) | 指定是否应用溢出箱。使用 IsAutomaticOverflowBin 和 OverflowBin 来调整溢出箱的值。 |

 **返回值:**
void


---


### setOverflowBin {#setOverflowBin}

| 名称 | 描述 |
| --- | --- |
| setOverflowBin (double) | 指定溢出箱的自定义值。当 IsAutomaticOverflowBin 属性设为 false 且 IsOverflowBin 属性为 true 时生效。 |

 **返回值:**
void


---


### setPlotOrderReversed {#setPlotOrderReversed}

| 名称 | 描述 |
| --- | --- |
| setPlotOrderReversed (boolean) | 表示 MS PowerPoint 是否从最后到第一个绘制数据点。可读写 boolean。 |

 **返回值:**
void


---


### setPosition {#setPosition}

| 名称 | 描述 |
| --- | --- |
| setPosition (int) | 表示轴的位置。可读写 AxisPositionType。 |

 **返回值:**
void


---


### setTickLabelPosition {#setTickLabelPosition}

| 名称 | 描述 |
| --- | --- |
| setTickLabelPosition (int) | 表示指定轴上刻度标签的位置。可读写 TickLabelPositionType。 |

 **返回值:**
void


---


### setTickLabelRotationAngle {#setTickLabelRotationAngle}

| 名称 | 描述 |
| --- | --- |
| setTickLabelRotationAngle (float) | 表示刻度标签的旋转角度。可读写 float。 |

 **返回值:**
void


---


### setTickLabelSpacing {#setTickLabelSpacing}

| 名称 | 描述 |
| --- | --- |
| setTickLabelSpacing (long) | 指定在绘制标签之间跳过多少个刻度标签。适用于分类轴或系列轴。可读写 long。 |

 **返回值:**
void


---


### setTickMarksSpacing {#setTickMarksSpacing}

| 名称 | 描述 |
| --- | --- |
| setTickMarksSpacing (long) | 指定在绘制下一个刻度线前应跳过多少个刻度线。适用于分类轴或系列轴。可读写 int。 |

 **返回值:**
void


---


### setTitle {#setTitle}

| 名称 | 描述 |
| --- | --- |
| setTitle (boolean) | 确定轴是否具有可见标题。可读写 boolean。 |

 **返回值:**
void


---


### setUnderflowBin {#setUnderflowBin}

| 名称 | 描述 |
| --- | --- |
| setUnderflowBin (boolean) | 指定是否应用下溢箱。使用 IsAutomaticUnderflowBin 和 UnderflowBin 来调整下溢箱的值。 |

 **返回值:**
void


---


### setUnderflowBin {#setUnderflowBin}

| 名称 | 描述 |
| --- | --- |
| setUnderflowBin (double) | 指定下溢箱的自定义值。当 IsAutomaticUnderflowBin 属性设为 false 且 IsUnderflowBin 属性为 true 时生效。 |

 **返回值:**
void


---


### setVisible {#setVisible}

| 名称 | 描述 |
| --- | --- |
| setVisible (boolean) | 表示轴是否可见。可读写 boolean。 |

 **返回值:**
void


---