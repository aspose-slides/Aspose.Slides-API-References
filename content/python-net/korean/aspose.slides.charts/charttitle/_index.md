---
title: ChartTitle class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/charttitle/
---
## ChartTitle 클래스

차트 제목 속성을 나타냅니다.

ChartTitle 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`x`](/slides/python-net/ko/aspose.slides.charts/charttitle/x/) | 제목의 x 좌표를 차트 너비의 비율로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides.charts/charttitle/y/) | 제목의 y 좌표를 차트 높이의 비율로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides.charts/charttitle/width/) | 제목의 너비를 차트 너비의 비율로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides.charts/charttitle/height/) | 제목의 높이를 차트 높이의 비율로 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`right`](/slides/python-net/ko/aspose.slides.charts/charttitle/right/) | 오른쪽.<br/>            읽기 전용 **float**. |
| [`bottom`](/slides/python-net/ko/aspose.slides.charts/charttitle/bottom/) | 아래쪽.<br/>            읽기 전용 **float**. |
| [`overlay`](/slides/python-net/ko/aspose.slides.charts/charttitle/overlay/) | 다른 차트 요소가 제목과 겹치는 것을 허용할지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`format`](/slides/python-net/ko/aspose.slides.charts/charttitle/format/) | 제목의 채우기, 선, 효과 스타일을 반환합니다.<br/>            읽기 전용 [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/ko/aspose.slides.charts/charttitle/text_frame_for_overriding/) | 풍부한 형식의 텍스트를 포함할 수 있습니다. 이 속성이 None이 아니면 이 <br/>            형식화된 텍스트 값이 자동 생성된 텍스트를 대체합니다.<br/>            자동 생성된 텍스트는 데이터 레이블, 값 축의 표시 단위 레이블, 축 제목, 차트 제목, 추세선 레이블의 암시적 속성입니다.<br/>            자동 생성된 텍스트는 IFormattedTextContainer.TextFormat 속성으로 형식이 지정됩니다.<br/>            읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/charttitle/text_format/) | 텍스트 형식을 반환합니다.<br/>            읽기 전용 [`IChartTextFormat`](/slides/python-net/ko/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/ko/aspose.slides.charts/charttitle/actual_x/) | 차트 요소의 실제 x 위치(왼쪽)를 차트 왼쪽 상단 모서리를 기준으로 지정합니다.<br/>            실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. <br/>            읽기 **float**. |
| [`actual_y`](/slides/python-net/ko/aspose.slides.charts/charttitle/actual_y/) | 차트 요소의 실제 상단을 차트 왼쪽 상단 모서리를 기준으로 지정합니다.<br/>            실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. <br/>            읽기 **float**. |
| [`actual_width`](/slides/python-net/ko/aspose.slides.charts/charttitle/actual_width/) | 차트 요소의 실제 너비를 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. <br/>            읽기 **float**. |
| [`actual_height`](/slides/python-net/ko/aspose.slides.charts/charttitle/actual_height/) | 차트 요소의 실제 높이를 지정합니다. 실제 값을 얻으려면 IChart.ValidateChartLayout() 메서드를 먼저 호출하십시오. <br/>            읽기 **float**. |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/charttitle/chart/) | 부모 차트를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/charttitle/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ko/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | 텍스트 매개변수 "text"를 사용하여 TextFrameForOverriding을 초기화합니다.<br/>            TextFrameForOverriding이 이미 초기화된 경우 텍스트만 변경합니다. |


### 다음 보기
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)