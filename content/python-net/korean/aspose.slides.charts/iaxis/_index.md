---
title: IAxis class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/iaxis/
---
## IAxis 클래스

차트 축을 나타내는 객체를 캡슐화합니다.

IAxis 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`axis_between_categories`](/slides/python-net/ko/aspose.slides.charts/iaxis/axis_between_categories/) | 값 축이 범주 축을 범주 사이를 교차하는지 여부를 나타냅니다.<br/>            이 속성은 범주 축에만 적용되며 3-D 차트에는 적용되지 않습니다.<br/>            읽기/쓰기 **bool**. |
| [`cross_at`](/slides/python-net/ko/aspose.slides.charts/iaxis/cross_at/) | 축에서 직각 축이 교차하는 지점을 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`display_unit`](/slides/python-net/ko/aspose.slides.charts/iaxis/display_unit/) | 값 축에 대한 표시 단위의 스케일 값을 지정합니다.<br/>            읽기/쓰기 [`DisplayUnitType`](/slides/python-net/ko/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/ko/aspose.slides.charts/iaxis/actual_max_value/) | 축의 실제 최대값을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_min_value`](/slides/python-net/ko/aspose.slides.charts/iaxis/actual_min_value/) | 축의 실제 최소값을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_major_unit`](/slides/python-net/ko/aspose.slides.charts/iaxis/actual_major_unit/) | 축의 실제 주요 단위를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_minor_unit`](/slides/python-net/ko/aspose.slides.charts/iaxis/actual_minor_unit/) | 축의 실제 부단위를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_major_unit_scale`](/slides/python-net/ko/aspose.slides.charts/iaxis/actual_major_unit_scale/) | 축의 실제 주요 단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_minor_unit_scale`](/slides/python-net/ko/aspose.slides.charts/iaxis/actual_minor_unit_scale/) | 축의 실제 부단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`is_automatic_max_value`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_automatic_max_value/) | 최대값이 자동으로 할당되는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`max_value`](/slides/python-net/ko/aspose.slides.charts/iaxis/max_value/) | 값 축의 최대값을 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`minor_unit`](/slides/python-net/ko/aspose.slides.charts/iaxis/minor_unit/) | 날짜 또는 값 축에 대한 부단위를 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_automatic_minor_unit/) | 축의 부단위가 자동으로 할당되는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`major_unit`](/slides/python-net/ko/aspose.slides.charts/iaxis/major_unit/) | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`is_automatic_major_unit`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_automatic_major_unit/) | 축의 주요 단위가 자동으로 할당되는지 여부를 나타냅니다.<br/>            읽기/쓰기 **bool**. |
| [`is_automatic_min_value`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_automatic_min_value/) | 최소값이 자동으로 할당되는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`min_value`](/slides/python-net/ko/aspose.slides.charts/iaxis/min_value/) | 값 축의 최소값을 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`is_logarithmic`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_logarithmic/) | 값 축 스케일 유형이 로그인지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`log_base`](/slides/python-net/ko/aspose.slides.charts/iaxis/log_base/) | 로그 기준값을 나타냅니다. 기본값은 10입니다.<br/>             읽기/쓰기 **float**. |
| [`is_plot_order_reversed`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_plot_order_reversed/) | MS PowerPoint가 데이터 포인트를 마지막부터 첫 번째 순서로 플롯하는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`is_visible`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_visible/) | 축이 보이는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`major_tick_mark`](/slides/python-net/ko/aspose.slides.charts/iaxis/major_tick_mark/) | 지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다.<br/>             읽기/쓰기 [`TickMarkType`](/slides/python-net/ko/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/ko/aspose.slides.charts/iaxis/minor_tick_mark/) | 지정된 축에 대한 부 눈금 표시 유형을 나타냅니다.<br/>             읽기/쓰기 [`TickMarkType`](/slides/python-net/ko/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/ko/aspose.slides.charts/iaxis/tick_label_position/) | 지정된 축에 대한 눈금 라벨 위치를 나타냅니다.<br/>             읽기/쓰기 [`TickLabelPositionType`](/slides/python-net/ko/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/ko/aspose.slides.charts/iaxis/major_unit_scale/) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다.<br/>             읽기/쓰기 [`TimeUnitType`](/slides/python-net/ko/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/ko/aspose.slides.charts/iaxis/minor_unit_scale/) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다.<br/>             읽기/쓰기 [`TimeUnitType`](/slides/python-net/ko/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/ko/aspose.slides.charts/iaxis/base_unit_scale/) | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다.<br/>            읽기/쓰기 [`TimeUnitType`](/slides/python-net/ko/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/ko/aspose.slides.charts/iaxis/minor_grid_lines_format/) | 차트 축에 대한 부 그리드라인 형식을 나타냅니다.<br/>             읽기 전용 [`IChartLinesFormat`](/slides/python-net/ko/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/ko/aspose.slides.charts/iaxis/major_grid_lines_format/) | 차트 축에 대한 주요 그리드라인 형식을 나타냅니다.<br/>             읽기 전용 [`IChartLinesFormat`](/slides/python-net/ko/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/ko/aspose.slides.charts/iaxis/show_minor_grid_lines/) | 부 그리드라인이 표시되는지 여부를 나타냅니다.<br/>             읽기 전용 **bool**. |
| [`show_major_grid_lines`](/slides/python-net/ko/aspose.slides.charts/iaxis/show_major_grid_lines/) | 주 그리드라인이 표시되는지 여부를 나타냅니다.<br/>             읽기 전용 **bool**. |
| [`format`](/slides/python-net/ko/aspose.slides.charts/iaxis/format/) | 축의 형식을 나타냅니다.<br/>             읽기 전용 [`IAxisFormat`](/slides/python-net/ko/aspose.slides.charts/iaxisformat). |
| [`title`](/slides/python-net/ko/aspose.slides.charts/iaxis/title/) | 축의 제목을 가져옵니다.<br/>             읽기 전용 [`IChartTitle`](/slides/python-net/ko/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/ko/aspose.slides.charts/iaxis/cross_type/) | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다.<br/>             읽기/쓰기 [`CrossesType`](/slides/python-net/ko/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/ko/aspose.slides.charts/iaxis/position/) | 축의 위치를 나타냅니다.<br/>             읽기/쓰기 [`AxisPositionType`](/slides/python-net/ko/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/ko/aspose.slides.charts/iaxis/has_title/) | 축에 표시 가능한 제목이 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`number_format`](/slides/python-net/ko/aspose.slides.charts/iaxis/number_format/) | 축 라벨에 대한 형식 문자열을 나타냅니다.<br/>            읽기/쓰기 **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_number_format_linked_to_source/) | 형식이 연결된 소스 데이터인지 여부를 나타냅니다.<br/>            읽기/쓰기 **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/ko/aspose.slides.charts/iaxis/tick_label_rotation_angle/) | 눈금 라벨의 회전 각도를 나타냅니다<br/>            읽기/쓰기 **float**. |
| [`tick_label_spacing`](/slides/python-net/ko/aspose.slides.charts/iaxis/tick_label_spacing/) | 그려지는 라벨 사이에 건너뛸 눈금 라벨 수를 지정합니다.<br/>            읽기/쓰기 **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_automatic_tick_label_spacing/) | 자동 눈금 라벨 간격 값을 지정합니다. false인 경우: TickLabelSpacing 속성을 사용합니다.<br/>            읽기/쓰기 **bool**. |
| [`tick_marks_spacing`](/slides/python-net/ko/aspose.slides.charts/iaxis/tick_marks_spacing/) | 다음 눈금이 그려지기 전에 건너뛸 눈금 표시 수를 지정합니다.<br/>            카테고리 또는 시리즈 축에 적용됩니다.<br/>            읽기/쓰기 **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_automatic_tick_marks_spacing/) | 자동 눈금 표시 간격 값을 지정합니다. false인 경우: TickMarksSpacing 속성을 사용합니다.<br/>            읽기/쓰기 **bool**. |
| [`label_offset`](/slides/python-net/ko/aspose.slides.charts/iaxis/label_offset/) | 라벨과 축 사이의 거리를 지정합니다. 카테고리 또는 날짜 축에 적용됩니다. 값은 0%와 1000% 사이여야 합니다.<br/>            읽기/쓰기 **int**. |
| [`category_axis_type`](/slides/python-net/ko/aspose.slides.charts/iaxis/category_axis_type/) | 카테고리 축의 유형을 지정합니다.<br/>            읽기/쓰기 [`IAxis.category_axis_type`](/slides/python-net/ko/aspose.slides.charts/iaxis/category_axis_type). |
| [`aggregation_type`](/slides/python-net/ko/aspose.slides.charts/iaxis/aggregation_type/) | 카테고리 축(빈ning)의 집계 유형을 나타냅니다. 카테고리에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [`bin_width`](/slides/python-net/ko/aspose.slides.charts/iaxis/bin_width/) | AggregationType 속성 값이 AxisAggregationType.ByBinWidth로 설정된 경우 빈 너비를 지정합니다.<br/>            카테고리 축에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [`number_of_bins`](/slides/python-net/ko/aspose.slides.charts/iaxis/number_of_bins/) | AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins로 설정된 경우 빈 개수를 지정합니다.<br/>            카테고리 축에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈와 함께 사용할 수 있습니다. |
| [`is_overflow_bin`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_overflow_bin/) | 오버플로 빈이 적용되는지 여부를 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로 빈 값을 조정하십시오. |
| [`is_automatic_overflow_bin`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_automatic_overflow_bin/) | 자동 오버플로 빈 값을 지정합니다. false인 경우: OverflowBin 속성을 사용합니다. |
| [`overflow_bin`](/slides/python-net/ko/aspose.slides.charts/iaxis/overflow_bin/) | 오버플로 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false로 설정되고 IsOverflowBin 속성이 true인 경우에 적용됩니다. |
| [`is_underflow_bin`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_underflow_bin/) | 언더플로 빈이 적용되는지 여부를 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로 빈 값을 조정하십시오. |
| [`is_automatic_underflow_bin`](/slides/python-net/ko/aspose.slides.charts/iaxis/is_automatic_underflow_bin/) | 자동 언더플로 빈 값을 지정합니다. false인 경우: UnderflowBin 속성을 사용합니다. |
| [`underflow_bin`](/slides/python-net/ko/aspose.slides.charts/iaxis/underflow_bin/) | 언더플로 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false로 설정되고 IsUnderflowBin 속성이 true인 경우에 적용됩니다. |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/iaxis/text_format/) |  |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/iaxis/chart/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/iaxis/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/iaxis/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/ko/aspose.slides.charts/iaxis/set_category_axis_type_automatically/#) | 축 데이터에 기반하여 자동으로 결정되는 값을 사용하여 IAxis.CategoryAxisType 속성을 설정합니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)