---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: कॉम्बिनेबल श्रृंखला प्रकारों के समूहों का एन्यूमरेशन। प्रत्येक तत्व उन प्रकारों के समूह से संबंधित है जो चार्ट श्रृंखला में होते हैं और एक ChartSeriesGroup में एक साथ मौजूद रह सकते हैं। उदाहरण के लिए, ChartType.PercentsStackedArea श्रृंखला एक ही ChartSeriesGroup में ChartType.StackedArea श्रृंखला के साथ एक साथ नहीं हो सकती। लेकिन दो या अधिक ChartType.PercentsStackedArea एक ही ChartSeriesGroup में एक साथ हो सकते हैं जैसे CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea। और ChartType.Line श्रृंखला ChartType.LineWithMarkers श्रृंखला के साथ एक ही CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup में एक साथ हो सकती है।
type: docs
weight: 1530
url: /hi/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup एन्यूमरेशन

कॉम्बिनेबल सीरीज़ प्रकारों के समूहों का एन्यूमरेशन। प्रत्येक तत्व एक ChartSeriesGroup में एक साथ जारी रह सकने वाले चार्ट श्रृंखला प्रकारों के समूह से संबंधित है। उदाहरण के लिए: ChartType.PercentsStackedArea श्रृंखला ChartType.StackedArea श्रृंखला के साथ एक ही ChartSeriesGroup में एक साथ नहीं हो सकती। लेकिन दो या अधिक ChartType.PercentsStackedArea एक ही ChartSeriesGroup में एक साथ हो सकते हैं (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea)। और ChartType.Line श्रृंखला ChartType.LineWithMarkers श्रृंखला के साथ एक ही CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup में एक साथ हो सकती है।

```csharp
public enum CombinableSeriesTypesGroup
```

### मान

| Name | Value | Description |
| --- | --- | --- |
| AreaChart_Area | `4` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Line3D } |
| StockHighLowClose | `18` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Histogram } |
| ParetoLineChart | `54` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Waterfall } |
| FunnelChart | `57` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Funnel } |
| TreemapChart | `58` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Treemap } |
| MapChart | `59` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Map } |
| SunburstChart | `60` | इस सेट के श्रृंखला प्रकारों को समूहित करता है: { ChartType.Sunburst } |

### देखें

* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->