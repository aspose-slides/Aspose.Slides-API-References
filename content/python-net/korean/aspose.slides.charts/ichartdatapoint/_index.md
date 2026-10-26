---
title: IChartDataPoint class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint 클래스

시리즈 데이터 포인트를 나타냅니다.

IChartDataPoint 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`x_value`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/x_value/) | 차트 데이터 포인트의 x 값을 반환합니다.<br/>            읽기 전용 [`IStringOrDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/y_value/) | 차트 데이터 포인트의 y 값을 반환합니다.<br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/bubble_size/) | 차트 데이터 포인트의 버블 크기를 반환합니다.<br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/value/) | 차트 데이터 포인트의 값을 반환합니다.<br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/size_value/) | 차트 데이터 포인트의 크기 값을 반환합니다.<br/>            Treemap 및 Sunburst 차트에서 사용됩니다. <br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/color_value/) | 차트 데이터 포인트의 색상 값을 반환합니다.<br/>            Map 차트에서 사용됩니다. <br/>            읽기 전용 [`IDoubleChartValue`](/slides/python-net/ko/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | 사용자 정의 값 유형인 경우 시리즈 오류 막대 값을 나타냅니다.<br/>            읽기 전용 [`IErrorBarsCustomValues`](/slides/python-net/ko/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/label/) | 차트 데이터 포인트의 레이블을 나타냅니다.<br/>            읽기 전용 [`IDataLabel`](/slides/python-net/ko/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | 버블에 3-D 효과가 적용되었음을 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`explosion`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/explosion/) | 파이 중심에서 데이터 포인트가 이동할 양을 지정합니다.<br/>            읽기/쓰기 **int**. |
| [`format`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/format/) | 서식 지정 속성을 나타냅니다.<br/>            읽기/쓰기 [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/marker/) | 데이터 마커를 지정합니다.<br/>            읽기 전용 [`IMarker`](/slides/python-net/ko/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | 다음 차트 유형 목록에 해당하는 경우 해당 범례 항목의 속성:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            읽기 전용 [`ILegendEntryProperties`](/slides/python-net/ko/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/set_as_total/) | 데이터 포인트를 총합으로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다. |
| [`invert_if_negative`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | 값이 음수일 경우 데이터 포인트가 색상을 반전하도록 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`data_point_levels`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/data_point_levels/) | 데이터 포인트 레벨의 컨테이너를 반환합니다. TreeMap 및 Sunburst 시리즈에 적용됩니다.<br/>            데이터 포인트 레벨 인덱스는 0부터 시작합니다. |
| [`index`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/index/) | 이 데이터 포인트가 적용되는 부모의 자식 컬렉션을 결정합니다.<br/>            읽기 **int**. |
| [`actual_x`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/remove/#) | 차트 시리즈에서 DataPoint를 제거합니다. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | 시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 데이터 포인트의 자동 색상을 반환합니다.<br/>            FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다. |

### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)