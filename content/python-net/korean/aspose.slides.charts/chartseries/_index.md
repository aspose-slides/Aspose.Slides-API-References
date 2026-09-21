---
title: ChartSeries class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartseries/
---
## ChartSeries 클래스

차트 시리즈를 나타냅니다.

ChartSeries 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/chartseries/chart/) | 부(parent chart를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`explosion`](/slides/python-net/ko/aspose.slides.charts/chartseries/explosion/) | 열린 파이 조각이 파이 차트 중심에서 떨어진 거리를 파이 직경의 백분율로 표시합니다.<br/>             읽기/쓰기 **int**. |
| [`smooth`](/slides/python-net/ko/aspose.slides.charts/chartseries/smooth/) | 곡선 부드러움을 나타냅니다. 라인 차트 또는 스캐터 차트에서 곡선 부드러움이 켜져 있으면 true입니다.<br/>            라인 차트 및 라인으로 연결된 스캐터 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`name`](/slides/python-net/ko/aspose.slides.charts/chartseries/name/) | 시리즈 이름을 반환합니다.<br/>            읽기 전용 [`IStringChartValue`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue). |
| [`data_points`](/slides/python-net/ko/aspose.slides.charts/chartseries/data_points/) | 이 시리즈의 데이터 포인트 컬렉션을 반환합니다.<br/>            읽기 전용 [`IChartDataPointCollection`](/slides/python-net/ko/aspose.slides.charts/ichartdatapointcollection). |
| [`type`](/slides/python-net/ko/aspose.slides.charts/chartseries/type/) | 이 시리즈의 유형을 반환합니다.<br/>            읽기/쓰기 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype). |
| [`plot_on_second_axis`](/slides/python-net/ko/aspose.slides.charts/chartseries/plot_on_second_axis/) | 이 시리즈가 보조 축에 표시되는지 여부를 나타냅니다.<br/>            읽기/쓰기 **bool**. |
| [`parent_series_group`](/slides/python-net/ko/aspose.slides.charts/chartseries/parent_series_group/) | ParentSeriesGroup.<br/>            읽기 전용 [`IChartSeriesGroup`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup). |
| [`format`](/slides/python-net/ko/aspose.slides.charts/chartseries/format/) | 시리즈의 형식을 반환합니다.<br/>            읽기 전용 [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`order`](/slides/python-net/ko/aspose.slides.charts/chartseries/order/) | 시리즈의 순서를 반환합니다.<br/>            읽기/쓰기 **int**. |
| [`labels`](/slides/python-net/ko/aspose.slides.charts/chartseries/labels/) | 시리즈의 레이블을 반환합니다.<br/>            읽기 전용 [`IDataLabelCollection`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection). |
| [`trend_lines`](/slides/python-net/ko/aspose.slides.charts/chartseries/trend_lines/) | 시리즈 추세선 컬렉션.<br/>            읽기 전용 [`ITrendlineCollection`](/slides/python-net/ko/aspose.slides.charts/itrendlinecollection). |
| [`error_bars_x_format`](/slides/python-net/ko/aspose.slides.charts/chartseries/error_bars_x_format/) | X 방향의 시리즈 ErrorBars를 나타냅니다. <br/>            <br/>            X 방향의 ErrorBars는 area, bar, scatter 및 bubble 유형의 시리즈에 사용할 수 있습니다. <br/>            다른 차트 유형의 경우 이 속성은 None을 반환합니다(3D 차트 포함).<br/>            사용자 정의 값을 사용하는 경우 DataPoints 컬렉션을 사용하여 값을 지정합니다<br/>            ([`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 속성 사용).<br/>            <br/>            읽기 전용 [`IErrorBarsFormat`](/slides/python-net/ko/aspose.slides.charts/ierrorbarsformat). |
| [`error_bars_y_format`](/slides/python-net/ko/aspose.slides.charts/chartseries/error_bars_y_format/) | Y 방향의 시리즈 ErrorBars를 나타냅니다.<br/>            <br/>            Y 방향의 ErrorBars는 area, bar, line, scatter 및 bubble 유형의 시리즈에 사용할 수 있습니다. <br/>            다른 차트 유형의 경우 이 속성은 None을 반환합니다(3D 차트 포함). <br/>            사용자 정의 값을 사용하는 경우 DataPoints 컬렉션을 사용하여 값을 지정합니다<br/>            ([`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 속성 사용).<br/>            <br/>            읽기 전용 [`IErrorBarsFormat`](/slides/python-net/ko/aspose.slides.charts/ierrorbarsformat). |
| [`related_legend_entry`](/slides/python-net/ko/aspose.slides.charts/chartseries/related_legend_entry/) | 이 시리즈와 관련된 범례 항목을 나타냅니다<br/>            읽기 전용 [`ILegendEntryProperties`](/slides/python-net/ko/aspose.slides.charts/ilegendentryproperties). |
| [`number_format_of_values`](/slides/python-net/ko/aspose.slides.charts/chartseries/number_format_of_values/) | NumberFormatOfValues.<br/>            읽기/쓰기 **str**. |
| [`number_format_of_x_values`](/slides/python-net/ko/aspose.slides.charts/chartseries/number_format_of_x_values/) | NumberFormatOfXValues.<br/>            읽기/쓰기 **str**. |
| [`number_format_of_y_values`](/slides/python-net/ko/aspose.slides.charts/chartseries/number_format_of_y_values/) | NumberFormatOfYValues.<br/>            읽기/쓰기 **str**. |
| [`number_format_of_bubble_sizes`](/slides/python-net/ko/aspose.slides.charts/chartseries/number_format_of_bubble_sizes/) | NumberFormatOfBubbleSizes.<br/>            읽기/쓰기 **str**. |
| [`marker`](/slides/python-net/ko/aspose.slides.charts/chartseries/marker/) | Marker.<br/>            읽기 전용 [`IMarker`](/slides/python-net/ko/aspose.slides.charts/imarker). |
| [`bar_3d_shape`](/slides/python-net/ko/aspose.slides.charts/chartseries/bar_3d_shape/) | 3-D 막대 차트 시리즈의 모양을 지정합니다.<br/>            이 속성 값을 변경하면 시리즈 유형이 자동으로 변경될 수 있습니다.<br/>            읽기/쓰기 [`ChartShapeType`](/slides/python-net/ko/aspose.slides.charts/chartshapetype). |
| [`invert_if_negative`](/slides/python-net/ko/aspose.slides.charts/chartseries/invert_if_negative/) | 값이 음수인 경우 막대, 열 또는 버블 시리즈가 색상을 반전하도록 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`inverted_solid_fill_color`](/slides/python-net/ko/aspose.slides.charts/chartseries/inverted_solid_fill_color/) | 시리즈에 대해 반전된 단색을 지정합니다. 색상 설정을 적용하려면 시리즈 형식의 FillType을 FillType.Solid으로 설정합니다.<br/>            읽기/쓰기 [`ColorFormat`](/slides/python-net/ko/aspose.slides/colorformat). |
| [`show_inner_points`](/slides/python-net/ko/aspose.slides.charts/chartseries/show_inner_points/) | 내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`show_outlier_points`](/slides/python-net/ko/aspose.slides.charts/chartseries/show_outlier_points/) | 이상값 포인트를 나타냅니다. BoxAndWhisker 차트에 이상값 포인트가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`show_mean_markers`](/slides/python-net/ko/aspose.slides.charts/chartseries/show_mean_markers/) | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`show_mean_line`](/slides/python-net/ko/aspose.slides.charts/chartseries/show_mean_line/) | 평균 선을 나타냅니다. BoxAndWhisker 차트에 평균 선이 표시되는 경우 true입니다. BoxAndWhisker 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`quartile_method`](/slides/python-net/ko/aspose.slides.charts/chartseries/quartile_method/) | 사분위 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다. |
| [`show_connector_lines`](/slides/python-net/ko/aspose.slides.charts/chartseries/show_connector_lines/) | 연결선을 나타냅니다. Waterfall 차트에만 적용됩니다. |
| [`parent_label_layout`](/slides/python-net/ko/aspose.slides.charts/chartseries/parent_label_layout/) | 부모 카테고리 레이블의 레이아웃을 나타냅니다.   Treemap 차트에만 적용됩니다. |
| [`has_up_down_bars`](/slides/python-net/ko/aspose.slides.charts/chartseries/has_up_down_bars/) | Line 또는 Stock 차트에 상향/하향 막대가 있는지 여부를 결정합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.UpDownBars.HasUpDownBars 읽기/쓰기 속성을 사용하세요.<br/>            상향/하향 막대의 형식은 ParentSeriesGroup.UpDownBars 속성을 사용합니다.<br/>            읽기 전용 **bool**. |
| [`gap_width`](/slides/python-net/ko/aspose.slides.charts/chartseries/gap_width/) | 막대 또는 열 클러스터 사이의 간격을 막대 또는 열 너비의 백분율로 지정합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.GapWidth 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`gap_depth`](/slides/python-net/ko/aspose.slides.charts/chartseries/gap_depth/) | 3D 차트에서 데이터 시리즈 사이의 거리를 마커 너비의 백분율로 반환하거나 설정합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.GapDepth 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`first_slice_angle`](/slides/python-net/ko/aspose.slides.charts/chartseries/first_slice_angle/) | 첫 번째 파이 또는 도넛 차트 조각의 각도를 지정합니다, <br/>            각도(위에서 시계 방향, 0에서 360도).<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.FirstSliceAngle 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`doughnut_hole_size`](/slides/python-net/ko/aspose.slides.charts/chartseries/doughnut_hole_size/) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10%에서 90% 사이).<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.DoughnutHoleSize 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`overlap`](/slides/python-net/ko/aspose.slides.charts/chartseries/overlap/) | 2-D 차트에서 막대와 열이 겹치는 정도를 백분율( -100%에서 100% )로 지정합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성입니다.<br/>            이는 부모 시리즈 그룹의 해당 속성에 대한 투영이며, 따라서 이 속성은 읽기 전용입니다.<br/>            값을 변경하려면 **ParentSeriesGroup.Overlap** 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`second_pie_size`](/slides/python-net/ko/aspose.slides.charts/chartseries/second_pie_size/) | pie-of-pie 차트 또는 bar-of-pie 차트의 두 번째 파이 또는 막대 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5%~200% 사이).<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.SecondPieSize 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`has_series_lines`](/slides/python-net/ko/aspose.slides.charts/chartseries/has_series_lines/) | 이 시리즈 및 관련 시리즈에 시리즈 라인이 있는지 여부를 결정합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.HasSeriesLines 읽기/쓰기 속성을 사용하세요.<br/>            시리즈 라인의 형식은 ParentSeriesGroup.SeriesLinesFormat 속성을 사용합니다.<br/>            읽기 전용 **bool**. |
| [`bubble_size_representation`](/slides/python-net/ko/aspose.slides.charts/chartseries/bubble_size_representation/) | 버블 차트에서 버블 크기 값을 표시하는 방식을 지정합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.BubbleSizeRepresentation 읽기/쓰기 속성을 사용하세요. |
| [`pie_split_position`](/slides/python-net/ko/aspose.slides.charts/chartseries/pie_split_position/) | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함될 데이터 포인트를 결정하는 데 사용할 값을 지정합니다.<br/>            PieSplitBy 속성과 함께 사용됩니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.PieSplitPosition 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **float**. |
| [`pie_split_by`](/slides/python-net/ko/aspose.slides.charts/chartseries/pie_split_by/) | pie-of-pie 또는 bar-of-pie 차트에서 두 번째 파이 또는 막대에 포함될 데이터 포인트를 결정하는 방법을 지정합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.PieSplitBy 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 [`PieSplitType`](/slides/python-net/ko/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/ko/aspose.slides.charts/chartseries/pie_split_custom_points/) | 사용자 정의 분할이 있는 pie-of-pie 또는 bar-of-pie 차트에 대한 사용자 정의 분할 정보를 나타냅니다.<br/>            두 번째 파이 또는 막대에 그려질 데이터 포인트를 포함합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다.<br/>            읽기 전용 [`PieSplitCustomPointCollection`](/slides/python-net/ko/aspose.slides.charts/piesplitcustompointcollection). |
| [`is_color_varied`](/slides/python-net/ko/aspose.slides.charts/chartseries/is_color_varied/) | 시리즈의 각 데이터 마커가 다른 색을 갖도록 지정합니다.<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.IsColorVaried 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **bool**. |
| [`bubble_size_scale`](/slides/python-net/ko/aspose.slides.charts/chartseries/bubble_size_scale/) | 버블 차트의 스케일 계수를 지정합니다(기본 크기의 0%에서 300% 사이).<br/>            이 속성은 이 시리즈뿐만 아니라 부모 시리즈 그룹의 모든 시리즈에 적용되는 속성으로, 해당 그룹 속성의 투영입니다. 따라서 이 속성은 <br/>            읽기 전용입니다.<br/>            부모 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.BubbleSizeScale 읽기/쓰기 속성을 사용하세요. |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/chartseries/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/chartseries/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`get_automatic_series_color(self)`](/slides/python-net/ko/aspose.slides.charts/chartseries/get_automatic_series_color/#) | 시리즈 인덱스와 차트 스타일을 기반으로 시리즈의 자동 색상을 반환합니다. FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다. |

### 참고
* module [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)