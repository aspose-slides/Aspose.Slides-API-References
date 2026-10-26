---
title: Axis class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/axis/
---
## Axis 클래스

Encapsulates the object that represents a chart's axis.

The Axis type exposes the following members:

## 속성

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/axis/chart/) | 부모 차트를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`axis_between_categories`](/slides/python-net/ko/aspose.slides.charts/axis/axis_between_categories/) | 값 축이 범주 축을 범주 사이에서 교차하는지 나타냅니다.<br/>             이 속성은 카테고리 축에만 적용되며 3D 차트에는 적용되지 않습니다.<br/>             읽기/쓰기 **bool**. |
| [`category_axis_type`](/slides/python-net/ko/aspose.slides.charts/axis/category_axis_type/) | 카테고리 축의 유형을 지정합니다.<br/>            읽기/쓰기 [`CategoryAxisType`](/slides/python-net/ko/aspose.slides.charts/categoryaxistype). |
| [`cross_at`](/slides/python-net/ko/aspose.slides.charts/axis/cross_at/) | 축에 수직인 축이 교차하는 지점을 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`display_unit`](/slides/python-net/ko/aspose.slides.charts/axis/display_unit/) | 값 축에 대한 표시 단위의 스케일 값을 지정합니다.<br/>             읽기/쓰기 [`DisplayUnitType`](/slides/python-net/ko/aspose.slides.charts/displayunittype). |
| [`actual_max_value`](/slides/python-net/ko/aspose.slides.charts/axis/actual_max_value/) | 축의 실제 최대값을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_min_value`](/slides/python-net/ko/aspose.slides.charts/axis/actual_min_value/) | 축의 실제 최소값을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_major_unit`](/slides/python-net/ko/aspose.slides.charts/axis/actual_major_unit/) | 축의 실제 주요 단위를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_minor_unit`](/slides/python-net/ko/aspose.slides.charts/axis/actual_minor_unit/) | 축의 실제 보조 단위를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_major_unit_scale`](/slides/python-net/ko/aspose.slides.charts/axis/actual_major_unit_scale/) | 축의 실제 주요 단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`actual_minor_unit_scale`](/slides/python-net/ko/aspose.slides.charts/axis/actual_minor_unit_scale/) | 축의 실제 보조 단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. |
| [`is_automatic_max_value`](/slides/python-net/ko/aspose.slides.charts/axis/is_automatic_max_value/) | 최대값이 자동으로 할당되는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`max_value`](/slides/python-net/ko/aspose.slides.charts/axis/max_value/) | 값 축의 최대값을 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`minor_unit`](/slides/python-net/ko/aspose.slides.charts/axis/minor_unit/) | 날짜 또는 값 축에 대한 보조 단위를 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`is_automatic_minor_unit`](/slides/python-net/ko/aspose.slides.charts/axis/is_automatic_minor_unit/) | 축의 보조 단위가 자동으로 할당되는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`major_unit`](/slides/python-net/ko/aspose.slides.charts/axis/major_unit/) | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`is_automatic_major_unit`](/slides/python-net/ko/aspose.slides.charts/axis/is_automatic_major_unit/) | 축의 주요 단위가 자동으로 할당되는지 여부를 나타냅니다.<br/>            읽기/쓰기 **bool**. |
| [`is_automatic_min_value`](/slides/python-net/ko/aspose.slides.charts/axis/is_automatic_min_value/) | 최소값이 자동으로 할당되는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`min_value`](/slides/python-net/ko/aspose.slides.charts/axis/min_value/) | 값 축의 최소값을 나타냅니다.<br/>             읽기/쓰기 **float**. |
| [`is_logarithmic`](/slides/python-net/ko/aspose.slides.charts/axis/is_logarithmic/) | 값 축의 스케일 유형이 로그인지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`log_base`](/slides/python-net/ko/aspose.slides.charts/axis/log_base/) | 로그 기반을 나타냅니다. 기본값은 10입니다.<br/>             읽기/쓰기 **float**. |
| [`is_plot_order_reversed`](/slides/python-net/ko/aspose.slides.charts/axis/is_plot_order_reversed/) | MS PowerPoint가 마지막부터 첫 번째 순서로 데이터 포인트를 플롯하는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`is_visible`](/slides/python-net/ko/aspose.slides.charts/axis/is_visible/) | 축이 보이는지 여부를 나타냅니다.<br/>             읽기/쓰기 **bool**. |
| [`major_tick_mark`](/slides/python-net/ko/aspose.slides.charts/axis/major_tick_mark/) | 지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다.<br/>             읽기/쓰기 [`TickMarkType`](/slides/python-net/ko/aspose.slides.charts/tickmarktype). |
| [`minor_tick_mark`](/slides/python-net/ko/aspose.slides.charts/axis/minor_tick_mark/) | 지정된 축에 대한 보조 눈금 표시 유형을 나타냅니다.<br/>             읽기/쓰기 [`TickMarkType`](/slides/python-net/ko/aspose.slides.charts/tickmarktype). |
| [`tick_label_position`](/slides/python-net/ko/aspose.slides.charts/axis/tick_label_position/) | 지정된 축에 대한 눈금 레이블 위치를 나타냅니다.<br/>             읽기/쓰기 [`TickLabelPositionType`](/slides/python-net/ko/aspose.slides.charts/ticklabelpositiontype). |
| [`major_unit_scale`](/slides/python-net/ko/aspose.slides.charts/axis/major_unit_scale/) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다.<br/>             읽기/쓰기 [`TimeUnitType`](/slides/python-net/ko/aspose.slides.charts/timeunittype). |
| [`minor_unit_scale`](/slides/python-net/ko/aspose.slides.charts/axis/minor_unit_scale/) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다.<br/>             읽기/쓰기 [`TimeUnitType`](/slides/python-net/ko/aspose.slides.charts/timeunittype). |
| [`base_unit_scale`](/slides/python-net/ko/aspose.slides.charts/axis/base_unit_scale/) | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다.<br/>            읽기/쓰기 [`TimeUnitType`](/slides/python-net/ko/aspose.slides.charts/timeunittype). |
| [`minor_grid_lines_format`](/slides/python-net/ko/aspose.slides.charts/axis/minor_grid_lines_format/) | 차트 축의 보조 격자선 형식을 나타냅니다.<br/>             읽기 전용 [`IChartLinesFormat`](/slides/python-net/ko/aspose.slides.charts/ichartlinesformat). |
| [`major_grid_lines_format`](/slides/python-net/ko/aspose.slides.charts/axis/major_grid_lines_format/) | 차트 축의 주요 격자선 형식을 나타냅니다.<br/>             읽기 전용 [`IChartLinesFormat`](/slides/python-net/ko/aspose.slides.charts/ichartlinesformat). |
| [`show_minor_grid_lines`](/slides/python-net/ko/aspose.slides.charts/axis/show_minor_grid_lines/) | 보조 격자선을 숨기려면 MinorGridLinesFormat.Line.FillFormat.FillType을 FillType.NoFill로 설정하십시오.<br/>            읽기 전용 **bool**. |
| [`show_major_grid_lines`](/slides/python-net/ko/aspose.slides.charts/axis/show_major_grid_lines/) | 주 격자선을 숨기려면 MajorGridLinesFormat.Line.FillFormat.FillType을 FillType.NoFill로 설정하십시오.<br/>            읽기 전용 **bool**. |
| [`format`](/slides/python-net/ko/aspose.slides.charts/axis/format/) | 축의 형식을 나타냅니다.<br/>             읽기 전용 [`IAxisFormat`](/slides/python-net/ko/aspose.slides.charts/iaxisformat). |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/axis/text_format/) | 텍스트의 형식을 나타냅니다.<br/>             읽기 전용 [`IChartTextFormat`](/slides/python-net/ko/aspose.slides.charts/icharttextformat). |
| [`title`](/slides/python-net/ko/aspose.slides.charts/axis/title/) | 축의 제목을 가져옵니다.<br/>             읽기 전용 [`IChartTitle`](/slides/python-net/ko/aspose.slides.charts/icharttitle). |
| [`cross_type`](/slides/python-net/ko/aspose.slides.charts/axis/cross_type/) | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다.<br/>             읽기/쓰기 [`CrossesType`](/slides/python-net/ko/aspose.slides.charts/crossestype). |
| [`position`](/slides/python-net/ko/aspose.slides.charts/axis/position/) | 축의 위치를 나타냅니다.<br/>             읽기/쓰기 [`AxisPositionType`](/slides/python-net/ko/aspose.slides.charts/axispositiontype). |
| [`has_title`](/slides/python-net/ko/aspose.slides.charts/axis/has_title/) | 축에 표시 가능한 제목이 있는지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`number_format`](/slides/python-net/ko/aspose.slides.charts/axis/number_format/) | 축 레이블에 대한 형식 문자열을 나타냅니다.<br/>            읽기/쓰기 **str**. |
| [`is_number_format_linked_to_source`](/slides/python-net/ko/aspose.slides.charts/axis/is_number_format_linked_to_source/) | 형식이 연결된 원본 데이터인지 여부를 나타냅니다.<br/>            읽기/쓰기 **bool**. |
| [`tick_label_rotation_angle`](/slides/python-net/ko/aspose.slides.charts/axis/tick_label_rotation_angle/) | 눈금 레이블의 회전 각도를 나타냅니다.<br/>            읽기/쓰기 **float**. |
| [`tick_label_spacing`](/slides/python-net/ko/aspose.slides.charts/axis/tick_label_spacing/) | 그려지는 레이블 사이에 건너뛸 눈금 레이블 수를 지정합니다. 카테고리 또는 시리즈 축에 적용됩니다.<br/>            읽기/쓰기 **int**. |
| [`is_automatic_tick_label_spacing`](/slides/python-net/ko/aspose.slides.charts/axis/is_automatic_tick_label_spacing/) | 자동 눈금 레이블 간격 값을 지정합니다. false인 경우: TickLabelSpacing 속성을 사용하십시오.<br/>            읽기/쓰기 **bool**. |
| [`tick_marks_spacing`](/slides/python-net/ko/aspose.slides.charts/axis/tick_marks_spacing/) | 다음 눈금이 그려지기 전에 건너뛸 눈금 표시 수를 지정합니다. 카테고리 또는 시리즈 축에 적용됩니다.<br/>            읽기/쓰기 **int**. |
| [`is_automatic_tick_marks_spacing`](/slides/python-net/ko/aspose.slides.charts/axis/is_automatic_tick_marks_spacing/) | 자동 눈금 표시 간격 값을 지정합니다. false인 경우: TickMarksSpacing 속성을 사용하십시오.<br/>            읽기/쓰기 **bool**. |
| [`label_offset`](/slides/python-net/ko/aspose.slides.charts/axis/label_offset/) | 레이블과 축 사이의 거리를 지정합니다. 카테고리 또는 날짜 축에 적용됩니다. 값은 0%에서 1000% 사이여야 합니다.<br/>            읽기/쓰기 **int**. |
| [`aggregation_type`](/slides/python-net/ko/aspose.slides.charts/axis/aggregation_type/) | 카테고리 축의 집계 유형(연결)을 나타냅니다. 카테고리에 적용되며 Histogram 또는 HistogramPareto 시리즈와 함께 사용됩니다. |
| [`bin_width`](/slides/python-net/ko/aspose.slides.charts/axis/bin_width/) | AggregationType 속성값이 AxisAggregationType.ByBinWidth로 설정된 경우 빈 폭을 지정합니다.<br/>            카테고리 축에 적용되며 Histogram 또는 HistogramPareto 시리즈와 함께 사용됩니다. |
| [`number_of_bins`](/slides/python-net/ko/aspose.slides.charts/axis/number_of_bins/) | AggregationType 속성값이 AxisAggregationType.ByNumberOfBins로 설정된 경우 빈 수를 지정합니다.<br/>            카테고리 축에 적용되며 Histogram 또는 HistogramPareto 시리즈와 함께 사용됩니다. |
| [`is_overflow_bin`](/slides/python-net/ko/aspose.slides.charts/axis/is_overflow_bin/) | 오버플로 빈이 적용되는지 여부를 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로 빈 값을 조정하십시오. |
| [`is_automatic_overflow_bin`](/slides/python-net/ko/aspose.slides.charts/axis/is_automatic_overflow_bin/) | 자동 오버플로 빈 값을 지정합니다. false인 경우: OverflowBin 속성을 사용하십시오. |
| [`overflow_bin`](/slides/python-net/ko/aspose.slides.charts/axis/overflow_bin/) | 오버플로 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false이고 IsOverflowBin 속성이 true일 때 적용됩니다. |
| [`is_underflow_bin`](/slides/python-net/ko/aspose.slides.charts/axis/is_underflow_bin/) | 언더플로 빈이 적용되는지 여부를 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로 빈 값을 조정하십시오. |
| [`is_automatic_underflow_bin`](/slides/python-net/ko/aspose.slides.charts/axis/is_automatic_underflow_bin/) | 자동 언더플로 빈 값을 지정합니다. false인 경우: UnderflowBin 속성을 사용하십시오. |
| [`underflow_bin`](/slides/python-net/ko/aspose.slides.charts/axis/underflow_bin/) | 언더플로 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false이고 IsUnderflowBin 속성이 true일 때 적용됩니다. |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/axis/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/axis/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`set_category_axis_type_automatically(self)`](/slides/python-net/ko/aspose.slides.charts/axis/set_category_axis_type_automatically/#) | 축 데이터에 따라 자동으로 결정되는 값으로 IAxis.CategoryAxisType 속성을 설정합니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)