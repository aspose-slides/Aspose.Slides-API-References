---
title: IChartSeriesGroup class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup 클래스

시리즈 그룹을 나타냅니다.

IChartSeriesGroup 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/type/) | 이 시리즈 그룹의 유형을 반환합니다.<br/>            읽기 전용 [`CombinableSeriesTypesGroup`](/slides/python-net/ko/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | 이 그룹의 시리즈가 보조 축에 플롯되는지 여부를 나타냅니다.<br/>            읽기 전용 **bool**. |
| [`series`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/series/) | 차트 시리즈의 읽기 전용 컬렉션을 반환합니다.<br/>            읽기 전용 [`IChartSeriesReadonlyCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Line 차트 또는 Stock 차트의 상승/하락 막대에 대한 접근을 제공합니다.<br/>            읽기 전용 [`IUpDownBarsManager`](/slides/python-net/ko/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/gap_width/) | 막대 또는 열 클러스터 사이의 간격을 막대 혹은 열 너비의 백분율로 가져오거나 설정합니다.<br/>            값은 0에서 500 사이여야 합니다.<br/>            읽기/쓰기 **int**. |
| [`gap_depth`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/gap_depth/) | 3D 차트에서 데이터 시리즈 간의 거리를 마커 너비의 백분율로 가져오거나 설정합니다.<br/>            값은 0에서 500 사이여야 합니다.<br/>            읽기/쓰기 **int**. |
| [`first_slice_angle`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | 첫 번째 파이 또는 도넛 차트 조각의 각도를 가져오거나 설정합니다, <br/>            도(°) 단위이며 위쪽을 기준으로 시계 방향, 0에서 360도 사이입니다.<br/>            읽기/쓰기 **int**. |
| [`is_color_varied`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | 시리즈의 각 데이터 마커가 서로 다른 색을 가지도록 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`has_series_lines`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | 차트에 시리즈 라인이 있는 경우 true. 누적 막대 및 OfPie 차트에 적용됩니다.<br/>            읽기/쓰기 **bool**. |
| [`overlap`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/overlap/) | 2D 차트에서 막대와 열이 겹치는 정도를 백분율로 지정합니다 ( -100%에서 100%까지).<br/>             - -100%: 최대 간격 (막대가 완전히 분리됨).<br/>             - 0%: 막대가 겹치거나 간격 없이 나란히 배치됨.<br/>             - 100%: 최대 겹침 (막대가 서로 완전히 겹침).<br/>             이 속성은 읽기/쓰기 **int**. |
| [`second_pie_size`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | 파이-오브-파이 차트 또는 바-오브-파이 차트에서 두 번째 파이 또는 바의 크기를 첫 번째 파이의 크기에 대한 백분율로 지정합니다 (5%에서 200% 사이 가능).<br/>            읽기/쓰기 **int**. |
| [`pie_split_position`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 데 사용되는 값을 지정합니다.<br/>            PieSplitBy 속성과 함께 사용됩니다.<br/>            읽기/쓰기 **float**. |
| [`pie_split_by`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | 파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 포함될 데이터 포인트를 결정하는 방식을 지정합니다.<br/>            읽기/쓰기 [`PieSplitType`](/slides/python-net/ko/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | 맞춤형 분할이 적용된 파이-오브-파이 또는 바-오브-파이 차트의 사용자 정의 분할 정보를 제공합니다.<br/>            파이-오브-파이 또는 바-오브-파이 차트에서 두 번째 파이 또는 바에 그려질 데이터 포인트를 포함합니다.<br/>            읽기 전용 [`IPieSplitCustomPointCollection`](/slides/python-net/ko/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | 도넛 차트의 구멍 크기를 지정합니다 (플롯 영역 크기의 10%에서 90% 사이 가능).<br/>            읽기/쓰기 **int**. |
| [`bubble_size_scale`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | 버블 차트의 배율을 지정합니다 (기본 크기의 0%에서 300% 사이 가능).<br/>            읽기/쓰기 **int**. |
| [`hi_low_lines_format`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | HiLowLines 형식을 지정합니다. <br/>            HiLowLines는 HiLowClose, OpenHiLowClose, VolumeHiLowClose 및 VolumeOpenHiLowClose 차트 유형에 적용됩니다. |
| [`bubble_size_representation`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | 버블 차트에서 버블 크기 값이 표시되는 방식을 지정합니다.<br/>            읽기/쓰기 [`BubbleSizeRepresentationType`](/slides/python-net/ko/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

지정된 인덱스의 요소를 가져옵니다.

## 인덱서

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### 비고

1) ChartSeriesGroupCollection 클래스 및 CombinableSeriesTypesGroup 열거형에 대한 요약 및 비고를 참조하십시오.
2) 시리즈 그룹은 그룹 내 각 시리즈에 공통적인 일부 시리즈 속성을 포함합니다 ("시리즈 그룹 속성").
            ChartSeriesGroup 클래스의 "시리즈 그룹 속성"은 읽기/쓰기입니다.
            각 "시리즈 그룹 속성"은 ChartSeries 클래스에서 읽기 전용 프로젝션을 가질 수 있습니다.

### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)