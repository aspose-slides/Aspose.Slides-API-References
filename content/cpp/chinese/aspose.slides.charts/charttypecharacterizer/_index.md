---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for C++ API 参考
description: 通过其 ChartType 获取有关图表和系列的额外信息的助手。
type: docs
weight: 339
url: /zh/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer 类

Helper for getting additional information about charts and series by its ChartType.

```cpp
class ChartTypeCharacterizer
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | 返回指定系列类型是否有趋势线。 |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | 如果 *chartType* 是 2D 图表类型之一，则返回 true。 |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | 如果 *chartType* 是 3D 图表类型之一，则返回 true。 |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | 如果 chartType 是 bar3DChart 子类型（3D 柱形或条形）之一，则返回 true。 |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | 如果 chartType 是 Area 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::Area](../charttype/)、[ChartType::PercentsStackedArea](../charttype/)、[ChartType::PercentsStackedArea3D](../charttype/)、[ChartType::StackedArea](../charttype/)、[ChartType::StackedArea3D](../charttype/)、[ChartType::Area3D](../charttype/)。 |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | 如果 chartType 是 Bar 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::ClusteredBar](../charttype/)、[ChartType::ClusteredBar3D](../charttype/)、[ChartType::PercentsStackedBar](../charttype/)、[ChartType::PercentsStackedBar3D](../charttype/)、[ChartType::StackedBar](../charttype/)、[ChartType::StackedBar3D](../charttype/)、[ChartType::ClusteredHorizontalCone](../charttype/)、[ChartType::ClusteredHorizontalCylinder](../charttype/)、[ChartType::ClusteredHorizontalPyramid](../charttype/)、[ChartType::StackedHorizontalCone](../charttype/)、[ChartType::StackedHorizontalCylinder](../charttype/)、[ChartType::StackedHorizontalPyramid](../charttype/)、[ChartType::PercentsStackedHorizontalCone](../charttype/)、[ChartType::PercentsStackedHorizontalCylinder](../charttype/)、[ChartType::PercentsStackedHorizontalPyramid](../charttype/)。 |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | 如果 chartType 是 Bubble 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::Bubble](../charttype/)、[ChartType::BubbleWith3D](../charttype/)。 |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | 如果 chartType 是 [Column](../../aspose.slides/column/) 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::ClusteredColumn](../charttype/)、[ChartType::ClusteredColumn3D](../charttype/)、[ChartType::ClusteredCone](../charttype/)、[ChartType::ClusteredCylinder](../charttype/)、[ChartType::ClusteredPyramid](../charttype/)、[ChartType::PercentsStackedColumn](../charttype/)、[ChartType::PercentsStackedColumn3D](../charttype/)、[ChartType::PercentsStackedCone](../charttype/)、[ChartType::PercentsStackedCylinder](../charttype/)、[ChartType::PercentsStackedPyramid](../charttype/)、[ChartType::StackedColumn](../charttype/)、[ChartType::StackedColumn3D](../charttype/)、[ChartType::StackedCone](../charttype/)、[ChartType::StackedCylinder](../charttype/)、[ChartType::StackedPyramid](../charttype/)、[ChartType::Column3D](../charttype/)、[ChartType::Cylinder3D](../charttype/)、[ChartType::Cone3D](../charttype/)、[ChartType::Pyramid3D](../charttype/)。 |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | 如果 chartType 是 Doughnut 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::Doughnut](../charttype/)、[ChartType::ExplodedDoughnut](../charttype/)。 |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | 如果 chartType 是 Line 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::Line](../charttype/)、[ChartType::LineWithMarkers](../charttype/)、[ChartType::PercentsStackedLine](../charttype/)、[ChartType::PercentsStackedLineWithMarkers](../charttype/)、[ChartType::StackedLine](../charttype/)、[ChartType::StackedLineWithMarkers](../charttype/)、[ChartType::Line3D](../charttype/)。 |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | 如果 chartType 是 Pie 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::BarOfPie](../charttype/)、[ChartType::ExplodedPie](../charttype/)、[ChartType::ExplodedPie3D](../charttype/)、[ChartType::Pie](../charttype/)、[ChartType::Pie3D](../charttype/)、[ChartType::PieOfPie](../charttype/)。 |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | 如果 chartType 是 Radar 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::FilledRadar](../charttype/)、[ChartType::Radar](../charttype/)、[ChartType::RadarWithMarkers](../charttype/)。 |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | 如果 chartType 是 Scatter 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::ScatterWithMarkers](../charttype/)、[ChartType::ScatterWithSmoothLines](../charttype/)、[ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/)、[ChartType::ScatterWithStraightLines](../charttype/)、[ChartType::ScatterWithStraightLinesAndMarkers](../charttype/)。 |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | 如果 chartType 是 Stock 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::HighLowClose](../charttype/)、[ChartType::OpenHighLowClose](../charttype/)、[ChartType::VolumeHighLowClose](../charttype/)、[ChartType::VolumeOpenHighLowClose](../charttype/)。 |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | 如果 chartType 是 Surface 子类型之一，则返回 true。子类型集合对应 PowerPoint 中的相应集合（参见 PowerPoint 中的 “Change Chart Type” 对话框）：[ChartType::Surface3D](../charttype/)、[ChartType::WireframeSurface3D](../charttype/)、[ChartType::Contour](../charttype/)、[ChartType::WireframeContour](../charttype/)。 |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | 返回指定系列类型是否允许误差棒 X。 |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | 返回指定系列类型是否允许误差棒 Y。 |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | 返回指定系列类型是否可以使用气泡大小坐标。 |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | 返回指定系列类型是否使用值坐标。 |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | 返回指定系列类型是否使用 X 值坐标。 |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | 返回指定系列类型是否使用 Y 值坐标。 |

## 另请参阅

* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)