---
title: ChartTypeCharacterizer
second_title: Aspose.Slides for C++ API リファレンス
description: ChartType に基づいてチャートや系列の追加情報を取得するためのヘルパーです。
type: docs
weight: 339
url: /ja/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer クラス

ChartType に基づいてチャートおよび系列に関する追加情報を取得するためのヘルパーです。

```cpp
class ChartTypeCharacterizer
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | 指定されたシリーズタイプにトレンドラインがあるかどうかを返します。 |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | *chartType* が 2D チャート タイプのいずれかである場合に true を返します。 |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | *chartType* が 3D チャート タイプのいずれかである場合に true を返します。 |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | chartType が bar3DChart のサブタイプ（3D 列またはバー）のいずれかである場合に true を返します。 |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | chartType が Area のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | chartType が Bar のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | chartType が Bubble のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | chartType が [Column](../../aspose.slides/column/) のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | chartType が Doughnut のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | chartType が Line のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | chartType が Pie のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | chartType が Radar のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | chartType が Scatter のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | chartType が Stock のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | chartType が Surface のサブタイプのいずれかである場合に true を返します。サブタイプのセットは PowerPoint の対応するセットに対応しています（PowerPoint の \"Change Chart Type\" ダイアログを参照）： [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | 指定されたシリーズタイプでエラーバー X が許可されているかどうかを返します。 |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | 指定されたシリーズタイプでエラーバー Y が許可されているかどうかを返します。 |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | 指定されたシリーズタイプでバブル サイズ座標が使用できるかどうかを返します。 |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | 指定されたシリーズタイプが値座標を使用するかどうかを返します。 |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | 指定されたシリーズタイプが X 値座標を使用するかどうかを返します。 |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | 指定されたシリーズタイプが Y 値座標を使用するかどうかを返します。 |

## 参照

* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)