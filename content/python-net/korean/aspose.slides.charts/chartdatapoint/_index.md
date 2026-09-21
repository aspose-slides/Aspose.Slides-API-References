---
title: ChartDataPoint class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint 클래스

시리즈 데이터 포인트를 나타냅니다.

ChartDataPoint 형식은 다음 구성원을 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`x_value`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            읽기 전용 [`IStringOrDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/size_value/) | 차트 데이터 포인트의 크기 값을 반환합니다.<br/>            Treemap 및 Sunburst 차트와 함께 사용됩니다. <br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/color_value/) | 차트 데이터 포인트의 색상 값을 반환합니다.<br/>            Map 차트와 함께 사용됩니다. <br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | 사용자 지정 값 유형인 경우 시리즈 오류 표시줄 값을 나타냅니다.<br/>            읽기 전용 [`IErrorBarsCustomValues`](/slides/python-net/ko/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            읽기 전용 [`IDataLabel`](/slides/python-net/ko/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | 거품에 3D 효과가 적용됨을 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`explosion`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/explosion/) | 파이 중심에서 데이터 포인트가 이동될 양을 지정합니다.<br/>            읽기/쓰기 **int**. |
| [`format`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/format/) | 서식 속성을 나타냅니다.<br/>            읽기/쓰기 [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/marker/) | 데이터 마커를 지정합니다.<br/>            읽기 전용 [`IMarker`](/slides/python-net/ko/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/set_as_total/) | 데이터 포인트를 총합으로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다. |
| [`related_legend_entry`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/related_legend_entry/) | 다음 목록에 있는 차트 유형에 대한 해당 범례 항목의 속성:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            읽기 전용 [`ILegendEntryProperties`](/slides/python-net/ko/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/data_point_levels/) | 데이터 포인트 레벨 컨테이너를 반환합니다. Treeamp 및 Sunburst 시리즈에 적용됩니다.<br/>            데이터 포인트 레벨 인덱스는 0부터 시작합니다. |
| [`index`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/invert_if_negative/) | 값이 음수인 경우 데이터 포인트가 색상을 반전하도록 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`actual_x`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/actual_x/) | 차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리를 기준으로 지정합니다.<br/>            실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. <br/>            읽기 **float**. |
| [`actual_y`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/actual_y/) | 차트 요소의 실제 위쪽 위치를 차트 왼쪽 상단 모서리를 기준으로 지정합니다.<br/>            실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. <br/>            읽기 **float**. |
| [`actual_width`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/actual_width/) | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. <br/>            읽기 **float**. |
| [`actual_height`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/actual_height/) | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. <br/>            읽기 **float**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/remove/#) | 차트 시리즈에서 DataPoint를 제거합니다. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ko/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | 시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 데이터 포인트의 자동 색상을 반환합니다.<br/>            FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다. |

### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)