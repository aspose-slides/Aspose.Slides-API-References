---
title: ErrorBarsFormat class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat 클래스

차트 시리즈의 오류 막대를 나타냅니다. ErrorBars 사용자 정의 값은 IChartDataPointCollection에 있으며
            ([`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 속성에) 있습니다.

ErrorBarsFormat 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`type`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/type/) | 오류 막대의 유형을 가져오거나 설정합니다. <br/>            읽기/쓰기 [`ErrorBarType`](/slides/python-net/ko/aspose.slides.charts/errorbartype). |
| [`value_type`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/value_type/) | 오류 막대 길이를 결정하는 가능한 방법을 나타냅니다. <br/>            사용자 정의 값 유형의 경우 값을 지정하려면 시리즈의 DataPoints 컬렉션에 있는 특정 데이터 포인트의 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 속성을 사용합니다.<br/>            Fixed, Percentage 또는 StandardDeviation 값 유형의 경우 값을 지정하려면 Value 속성을 사용합니다.  <br/>            읽기/쓰기 [`ErrorBarValueType`](/slides/python-net/ko/aspose.slides.charts/errorbarvaluetype). |
| [`has_end_cap`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/has_end_cap/) | 오류 막대에 끝 캡이 그려지지 않음을 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`value`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/value/) | Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되어 오류 막대 길이를 결정하는 값을 가져오거나 설정합니다. <br/>            다른 경우에는 NaN을 반환합니다.<br/>            읽기/쓰기 **float**. |
| [`format`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/format/) | 오류 막대의 형식을 나타냅니다.<br/>            읽기/쓰기 [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/chart/) | 부모 차트를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/is_visible/) | 오류 막대 가시성을 가져오거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat/presentation/) |  |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)