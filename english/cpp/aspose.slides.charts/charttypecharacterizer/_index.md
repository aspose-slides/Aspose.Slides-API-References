---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for C++ API Reference
description: Helper for getting additional information about charts and series by its ChartType.
type: docs
weight: 339
url: /cpp/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer class


Helper for getting additional information about charts and series by its ChartType.

```cpp
class ChartTypeCharacterizer
```

## Methods

| Method | Description |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Returns if there are series trend lines for specified series type. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Return true if *chartType*  is one of 2D chart types. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Return true if *chartType*  is one of 3D chart types. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Return true if chartType is one of bar3DChart subtypes (3D columns or bars). |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Return true if chartType is one of Area subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Return true if chartType is one of Bar subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Return true if chartType is one of Bubble subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Return true if chartType is one of [Column](../../aspose.slides/column/) subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Return true if chartType is one of Doughnut subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Return true if chartType is one of Line subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Return true if chartType is one of Pie subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Return true if chartType is one of Radar subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Return true if chartType is one of Scatter subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Return true if chartType is one of Stock subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Return true if chartType is one of Surface subtypes. Subtypes set corresponds to the appropriate set in PowerPoint (see \"Change Chart Type\" dialog in PowerPoint): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Returns if error bars X allowed for specified series type. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Returns if error bars Y allowed for specified series type. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Returns if bubble size coordinates can be used for specified series type. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Returns if specified series type uses value coordinates. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Returns if specified series type uses X value coordinates. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Returns if specified series type uses Y value coordinates. |
## See Also

* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)
