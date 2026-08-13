---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for C++ API 참조
description: ChartType에 따라 차트와 시리즈에 대한 추가 정보를 얻기 위한 도우미.
type: docs
weight: 339
url: /ko/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer 클래스

ChartType에 의해 차트와 시리즈에 대한 추가 정보를 얻기 위한 도우미.

```cpp
class ChartTypeCharacterizer
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | 지정된 시리즈 유형에 대해 시리즈 추세선이 있는지 반환합니다. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | *chartType*이 2D 차트 유형 중 하나이면 true를 반환합니다. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | *chartType*이 3D 차트 유형 중 하나이면 true를 반환합니다. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | chartType이 bar3DChart 하위 타입(3D 열 또는 막대) 중 하나이면 true를 반환합니다. |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | chartType이 Area 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | chartType이 Bar 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | chartType이 Bubble 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | chartType이 [Column](../../aspose.slides/column/) 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | chartType이 Doughnut 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | chartType이 Line 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | chartType이 Pie 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | chartType이 Radar 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | chartType이 Scatter 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | chartType이 Stock 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | chartType이 Surface 하위 타입 중 하나이면 true를 반환합니다. 하위 타입 집합은 PowerPoint에서 해당 집합에 대응합니다(\"Change Chart Type\" 대화 상자를 PowerPoint에서 참조): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | 지정된 시리즈 유형에 대해 오류 막대 X가 허용되는지 반환합니다. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | 지정된 시리즈 유형에 대해 오류 막대 Y가 허용되는지 반환합니다. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | 지정된 시리즈 유형에 대해 버블 크기 좌표를 사용할 수 있는지 반환합니다. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | 지정된 시리즈 유형이 값 좌표를 사용하는지 반환합니다. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | 지정된 시리즈 유형이 X 값 좌표를 사용하는지 반환합니다. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | 지정된 시리즈 유형이 Y 값 좌표를 사용하는지 반환합니다. |

## 참고

* 네임스페이스 [Aspose::Slides::Charts](../)
* 라이브러리 [Aspose.Slides](../../)