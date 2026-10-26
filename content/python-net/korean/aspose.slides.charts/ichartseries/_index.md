---
title: IChartSeries class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/ichartseries/
---
## IChartSeries 클래스

차트 시리즈를 나타냅니다.

IChartSeries 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`explosion`](/slides/python-net/ko/aspose.slides.charts/ichartseries/explosion/) | 열린 파이 조각이 파이 차트 중심에서 떨어진 거리를 파이 직경의 백분율로 표시합니다.<br/>             읽기/쓰기 **int**. |
| [`smooth`](/slides/python-net/ko/aspose.slides.charts/ichartseries/smooth/) | 곡선 스무딩을 나타냅니다. 선 차트 또는 산점도 차트에 곡선 스무딩이 켜져 있으면 true입니다. 선 및 선으로 연결된 산점도 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`marker`](/slides/python-net/ko/aspose.slides.charts/ichartseries/marker/) | 시리즈 마커를 반환합니다.<br/>            읽기 전용 [`IMarker`](/slides/python-net/ko/aspose.slides.charts/imarker). |
| [`bar_3d_shape`](/slides/python-net/ko/aspose.slides.charts/ichartseries/bar_3d_shape/) | 3D 막대 차트의 시리즈 모양을 지정합니다.<br/>            이 속성 값을 변경하면 자동으로 시리즈 유형이 변경될 수 있습니다.<br/>            읽기/쓰기 [`ChartShapeType`](/slides/python-net/ko/aspose.slides.charts/chartshapetype). |
| [`name`](/slides/python-net/ko/aspose.slides.charts/ichartseries/name/) | 시리즈 이름을 반환합니다.<br/>            읽기 전용 [`IStringChartValue`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue). |
| [`data_points`](/slides/python-net/ko/aspose.slides.charts/ichartseries/data_points/) | 이 시리즈의 데이터 포인트 컬렉션을 반환합니다.<br/>            읽기 전용 [`IChartDataPointCollection`](/slides/python-net/ko/aspose.slides.charts/ichartdatapointcollection). |
| [`type`](/slides/python-net/ko/aspose.slides.charts/ichartseries/type/) | 이 시리즈의 유형을 반환합니다.<br/>            읽기/쓰기 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype). |
| [`parent_series_group`](/slides/python-net/ko/aspose.slides.charts/ichartseries/parent_series_group/) | 상위 시리즈 그룹을 반환합니다.<br/>            읽기 전용 [`IChartSeriesGroup`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup). |
| [`format`](/slides/python-net/ko/aspose.slides.charts/ichartseries/format/) | 시리즈의 형식을 반환합니다.<br/>            읽기 전용 [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`order`](/slides/python-net/ko/aspose.slides.charts/ichartseries/order/) | 시리즈의 순서를 반환합니다.<br/>            읽기/쓰기 **int**. |
| [`labels`](/slides/python-net/ko/aspose.slides.charts/ichartseries/labels/) | 시리즈의 라벨을 반환합니다.<br/>            읽기 전용 [`IDataLabelCollection`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection). |
| [`trend_lines`](/slides/python-net/ko/aspose.slides.charts/ichartseries/trend_lines/) | 시리즈 추세선 컬렉션<br/>            읽기 전용 [`ITrendlineCollection`](/slides/python-net/ko/aspose.slides.charts/itrendlinecollection). |
| [`error_bars_x_format`](/slides/python-net/ko/aspose.slides.charts/ichartseries/error_bars_x_format/) | X 방향 오류 막대를 나타냅니다. <br/>            <br/>            X 방향 오류 막대는 area, bar, scatter 및 bubble 유형의 시리즈에 사용할 수 있습니다. <br/>            다른 차트 유형에서는 이 속성이 None을 반환합니다(3D 차트 포함).<br/>            사용자 지정값의 경우 DataPoints 컬렉션을 사용하여 값을 지정합니다<br/>            ([`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 속성 사용).<br/>            <br/>            읽기 전용 [`IErrorBarsFormat`](/slides/python-net/ko/aspose.slides.charts/ierrorbarsformat). |
| [`error_bars_y_format`](/slides/python-net/ko/aspose.slides.charts/ichartseries/error_bars_y_format/) | Y 방향 오류 막대를 나타냅니다.<br/>            <br/>            Y 방향 오류 막대는 area, bar, line, scatter 및 bubble 유형의 시리즈에 사용할 수 있습니다. <br/>            다른 차트 유형에서는 이 속성이 None을 반환합니다(3D 차트 포함). <br/>            사용자 지정값의 경우 DataPoints 컬렉션을 사용하여 값을 지정합니다<br/>            ([`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 속성 사용).<br/>            <br/>            읽기 전용 [`IErrorBarsFormat`](/slides/python-net/ko/aspose.slides.charts/ierrorbarsformat). |
| [`plot_on_second_axis`](/slides/python-net/ko/aspose.slides.charts/ichartseries/plot_on_second_axis/) | 이 시리즈가 두 번째 값 축에 플롯되는지 여부를 나타냅니다.<br/>            읽기/쓰기 **bool**. |
| [`number_format_of_values`](/slides/python-net/ko/aspose.slides.charts/ichartseries/number_format_of_values/) | 시리즈 값에 대한 숫자 서식을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`number_format_of_x_values`](/slides/python-net/ko/aspose.slides.charts/ichartseries/number_format_of_x_values/) | 시리즈 x 값에 대한 숫자 서식을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`number_format_of_y_values`](/slides/python-net/ko/aspose.slides.charts/ichartseries/number_format_of_y_values/) | 시리즈 y 값에 대한 숫자 서식을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`number_format_of_bubble_sizes`](/slides/python-net/ko/aspose.slides.charts/ichartseries/number_format_of_bubble_sizes/) | 시리즈 버블 크기에 대한 숫자 서식을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`invert_if_negative`](/slides/python-net/ko/aspose.slides.charts/ichartseries/invert_if_negative/) | 값이 음수인 경우 바, 열 또는 버블 시리즈가 색상을 반전시켜야 함을 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`inverted_solid_fill_color`](/slides/python-net/ko/aspose.slides.charts/ichartseries/inverted_solid_fill_color/) | 시리즈에 대해 고체 색상을 반전시킵니다. 색상 설정을 적용하려면 시리즈 형식 FillType을 FillType.Solid으로 설정합니다.<br/>            읽기/쓰기 [`IColorFormat`](/slides/python-net/ko/aspose.slides/icolorformat). |
| [`related_legend_entry`](/slides/python-net/ko/aspose.slides.charts/ichartseries/related_legend_entry/) | 이 시리즈와 관련된 범례 항목을 나타냅니다<br/>            읽기 전용 [`ILegendEntryProperties`](/slides/python-net/ko/aspose.slides.charts/ilegendentryproperties). |
| [`show_inner_points`](/slides/python-net/ko/aspose.slides.charts/ichartseries/show_inner_points/) | 내부 포인트를 나타냅니다. BoxAndWhisker 차트에 내부 포인트가 표시되면 true입니다. BoxAndWhisker 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`show_outlier_points`](/slides/python-net/ko/aspose.slides.charts/ichartseries/show_outlier_points/) | 외부 포인트를 나타냅니다. BoxAndWhisker 차트에 외부 포인트가 표시되면 true입니다. BoxAndWhisker 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`show_mean_markers`](/slides/python-net/ko/aspose.slides.charts/ichartseries/show_mean_markers/) | 평균 마커를 나타냅니다. BoxAndWhisker 차트에 평균 마커가 표시되면 true입니다. BoxAndWhisker 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`show_mean_line`](/slides/python-net/ko/aspose.slides.charts/ichartseries/show_mean_line/) | 평균 라인을 나타냅니다. BoxAndWhisker 차트에 평균 라인이 표시되면 true입니다. BoxAndWhisker 차트에만 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`quartile_method`](/slides/python-net/ko/aspose.slides.charts/ichartseries/quartile_method/) | 사분위 방법을 나타냅니다. BoxAndWhisker 차트에만 적용됩니다. |
| [`show_connector_lines`](/slides/python-net/ko/aspose.slides.charts/ichartseries/show_connector_lines/) | 연결선을 나타냅니다. Waterfall 차트에만 적용됩니다. |
| [`parent_label_layout`](/slides/python-net/ko/aspose.slides.charts/ichartseries/parent_label_layout/) | 상위 카테고리 레이블의 레이아웃을 나타냅니다. Treemap 차트에만 적용됩니다. |
| [`bubble_size_scale`](/slides/python-net/ko/aspose.slides.charts/ichartseries/bubble_size_scale/) | 버블 차트의 스케일 팩터를 지정합니다(기본 크기의 0~300% 사이).<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다.<br/>            상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.BubbleSizeScale 읽기/쓰기 속성을 사용하세요. |
| [`has_up_down_bars`](/slides/python-net/ko/aspose.slides.charts/ichartseries/has_up_down_bars/) | 라인 또는 주식 차트에 상승/하락 막대가 있는지 여부를 결정합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다.<br/>            상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.UpDownBars.HasUpDownBars 읽기/쓰기 속성을 사용하세요.<br/>            상승/하락 막대 형식은 ParentSeriesGroup.UpDownBars 속성을 사용하세요.<br/>            읽기 전용 **bool**. |
| [`gap_width`](/slides/python-net/ko/aspose.slides.charts/ichartseries/gap_width/) | 바 또는 열 클러스터 사이의 간격을 바 또는 열 너비의 백분율로 지정합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다.<br/>            상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.GapWidth 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`gap_depth`](/slides/python-net/ko/aspose.slides.charts/ichartseries/gap_depth/) | 3D 차트에서 데이터 시리즈 간의 거리(마커 너비의 백분율)를 반환하거나 설정합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다.<br/>            상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.GapDepth 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`is_color_varied`](/slides/python-net/ko/aspose.slides.charts/ichartseries/is_color_varied/) | 시리즈의 각 데이터 마커가 서로 다른 색을 가지도록 지정합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다.<br/>            상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.IsColorVaried 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **bool**. |
| [`has_series_lines`](/slides/python-net/ko/aspose.slides.charts/ichartseries/has_series_lines/) | 이 시리즈 및 연관 시리즈에 시리즈 라인이 있는지 여부를 결정합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영입니다. 따라서 이 속성은 읽기 전용입니다.<br/>            상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.HasSeriesLines 읽기/쓰기 속성을 사용하세요.<br/>            시리즈 라인 형식은 ParentSeriesGroup.SeriesLinesFormat 속성을 사용하세요.<br/>            읽기 전용 **bool**. |
| [`overlap`](/slides/python-net/ko/aspose.slides.charts/ichartseries/overlap/) | 2D 차트에서 바와 열이 겹치는 정도를 백분율(-100%~100%)로 지정합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영이며, 따라서 읽기 전용입니다.<br/>            값을 변경하려면 ParentSeriesGroup.Overlap 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`second_pie_size`](/slides/python-net/ko/aspose.slides.charts/ichartseries/second_pie_size/) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이 크기의 백분율로 지정합니다(5~200% 사이).<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영이며, 따라서 읽기 전용입니다.<br/>            상위 시리즈 그룹에 접근하려면 ParentSeriesGroup 속성을 사용하세요.<br/>            값을 변경하려면 ParentSeriesGroup.SecondPieSize 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`pie_split_position`](/slides/python-net/ko/aspose.slides.charts/ichartseries/pie_split_position/) | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 값입니다.<br/>            PieSplitBy 속성과 함께 사용됩니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영이며, 따라서 읽기 전용입니다.<br/>            값을 변경하려면 ParentSeriesGroup.PieSplitPosition 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **float**. |
| [`pie_split_by`](/slides/python-net/ko/aspose.slides.charts/ichartseries/pie_split_by/) | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방법을 지정합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영이며, 따라서 읽기 전용입니다.<br/>            값을 변경하려면 ParentSeriesGroup.PieSplitBy 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 [`PieSplitType`](/slides/python-net/ko/aspose.slides.charts/piesplittype). |
| [`doughnut_hole_size`](/slides/python-net/ko/aspose.slides.charts/ichartseries/doughnut_hole_size/) | 도넛 차트의 구멍 크기를 지정합니다(플롯 영역 크기의 10~90% 사이).<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영이며, 따라서 읽기 전용입니다.<br/>            값을 변경하려면 ParentSeriesGroup.DoughnutHoleSize 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`first_slice_angle`](/slides/python-net/ko/aspose.slides.charts/ichartseries/first_slice_angle/) | 첫 번째 파이 또는 도넛 차트 조각의 각도를 지정합니다(시계 방향, 0~360도).<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영이며, 따라서 읽기 전용입니다.<br/>            값을 변경하려면 ParentSeriesGroup.FirstSliceAngle 읽기/쓰기 속성을 사용하세요.<br/>            읽기 전용 **int**. |
| [`pie_split_custom_points`](/slides/python-net/ko/aspose.slides.charts/ichartseries/pie_split_custom_points/) | 사용자 지정 분할이 있는 파이-오브-파이 또는 바-오브-파이 차트에 대한 사용자 정의 분할 정보입니다.<br/>            두 번째 파이 또는 바에 그려질 데이터 포인트를 포함합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영이며,<br/>            읽기 전용 [`IPieSplitCustomPointCollection`](/slides/python-net/ko/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`bubble_size_representation`](/slides/python-net/ko/aspose.slides.charts/ichartseries/bubble_size_representation/) | 버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다.<br/>            이 속성은 이 시리즈뿐 아니라 상위 시리즈 그룹의 모든 시리즈에 대한 속성의 투영이며, 따라서 읽기 전용입니다.<br/>            값을 변경하려면 ParentSeriesGroup.BubbleSizeRepresentation 읽기/쓰기 속성을 사용하세요. |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/ichartseries/chart/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/ichartseries/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/ichartseries/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_automatic_series_color(self)`](/slides/python-net/ko/aspose.slides.charts/ichartseries/get_automatic_series_color/#) | 시리즈 인덱스와 차트 스타일을 기반으로 자동 색상을 반환합니다.<br/>            FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)