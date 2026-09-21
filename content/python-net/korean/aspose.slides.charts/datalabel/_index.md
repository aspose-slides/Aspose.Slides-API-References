---
title: DataLabel class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/datalabel/
---
## DataLabel 클래스

시리즈 레이블을 나타냅니다.

DataLabel 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/ko/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | DataLabel 클래스의 새 인스턴스를 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/datalabel/chart/) | 상위 차트를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ko/aspose.slides.charts/datalabel/is_visible/) | False는 데이터 레이블이 보이지 않음을 의미합니다(따라서 모든 Show*-플래그(ShowValue, ...)가 false입니다).<br/>            읽기 전용 **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/ko/aspose.slides.charts/datalabel/text_frame_for_overriding/) | 리치 형식 텍스트를 포함할 수 있습니다. 이 속성이 None이 아니면 이 <br/>            형식화된 텍스트 값이 데이터 레이블의 자동 생성 텍스트를 대체합니다.<br/>            데이터 레이블의 자동 생성 텍스트란 ShowSeriesName, <br/>            ShowValue, ... 속성에 의해 관리되고 TextFormatManager.TextFormat 속성으로 형식이 지정된 텍스트를 의미합니다.<br/>            읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/datalabel/text_format/) | 텍스트 형식을 반환합니다.<br/>            읽기 전용 [`IChartTextFormat`](/slides/python-net/ko/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/ko/aspose.slides.charts/datalabel/x/) | 차트 너비의 비율로 제목의 x 좌표를 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides.charts/datalabel/y/) | 차트 높이의 비율로 제목의 y 좌표를 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides.charts/datalabel/width/) | 차트 너비의 비율로 제목의 너비를 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides.charts/datalabel/height/) | 차트 높이의 비율로 제목의 높이를 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`right`](/slides/python-net/ko/aspose.slides.charts/datalabel/right/) | 오른쪽.<br/>            읽기 전용 **float**. |
| [`bottom`](/slides/python-net/ko/aspose.slides.charts/datalabel/bottom/) | 아래쪽.<br/>            읽기 전용 **float**. |
| [`data_label_format`](/slides/python-net/ko/aspose.slides.charts/datalabel/data_label_format/) | 데이터 레이블 형식을 반환합니다.<br/>            읽기 전용 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/ko/aspose.slides.charts/datalabel/value_from_cell/) | 워크북 데이터 셀을 가져오거나 설정합니다. IDataLabelFormat.ShowLabelValueFromCell 속성이 true인 경우 적용됩니다. |
| [`actual_x`](/slides/python-net/ko/aspose.slides.charts/datalabel/actual_x/) | 차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리를 기준으로 지정합니다.<br/>            실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. <br/>            읽기 **float**. |
| [`actual_y`](/slides/python-net/ko/aspose.slides.charts/datalabel/actual_y/) | 차트 요소의 실제 상단을 차트 왼쪽 상단 모서리를 기준으로 지정합니다.<br/>            실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. <br/>            읽기 **float**. |
| [`actual_width`](/slides/python-net/ko/aspose.slides.charts/datalabel/actual_width/) | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. <br/>            읽기 **float**. |
| [`actual_height`](/slides/python-net/ko/aspose.slides.charts/datalabel/actual_height/) | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. <br/>            읽기 **float**. |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/datalabel/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`hide(self)`](/slides/python-net/ko/aspose.slides.charts/datalabel/hide/#) | 모든 Show*-플래그(ShowValue, ...)를 false 상태로 설정하여 데이터 레이블을 숨깁니다.<br/>            이 후 IsVisible는 false가 됩니다. |
| [`get_actual_label_text(self)`](/slides/python-net/ko/aspose.slides.charts/datalabel/get_actual_label_text/#) | DataLabelFormat 설정 또는 TextFrameForOverriding.Text 값을 기반으로 실제 레이블 텍스트를 반환합니다. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ko/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | 파라미터 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다.<br/>            TextFrameForOverriding이 이미 초기화된 경우 텍스트만 변경합니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)