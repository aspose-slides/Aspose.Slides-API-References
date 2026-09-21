---
title: Trendline class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/trendline/
---
## Trendline 클래스

Class represents trend line of chart series

The Trendline type exposes the following members:

## 속성

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/ko/aspose.slides.charts/trendline/trendline_name/) | 추세선의 이름을 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`trendline_type`](/slides/python-net/ko/aspose.slides.charts/trendline/trendline_type/) | 추세선의 유형을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`TrendlineType`](/slides/python-net/ko/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/ko/aspose.slides.charts/trendline/format/) | 추세선의 형식을 나타냅니다.<br/>            읽기/쓰기 [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/ko/aspose.slides.charts/trendline/backward/) | 추세선이 연장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다.<br/>            데이터가 추세를 적용받는 시리즈 이전에.<br/>            산점도 및 비산점도 차트에서는 이 값이 0 이상의 값이어야 합니다.<br/>            읽기/쓰기 **float**. |
| [`forward`](/slides/python-net/ko/aspose.slides.charts/trendline/forward/) | 추세선이 연장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다.<br/>            데이터가 추세를 적용받는 시리즈 이후에.<br/>            산점도 및 비산점도 차트에서는 이 값이 0 이상의 값이어야 합니다.<br/>            읽기/쓰기 **float**. |
| [`intercept`](/slides/python-net/ko/aspose.slides.charts/trendline/intercept/) | 추세선이 y축과 교차하는 값을 지정합니다.<br/>            추세선 유형이 exp, linear 또는 poly인 경우에만 이 속성이 지원됩니다.<br/>            읽기/쓰기 **float**. |
| [`display_equation`](/slides/python-net/ko/aspose.slides.charts/trendline/display_equation/) | 추세선의 방정식이 차트에 표시되도록 지정합니다(R-squared 값과 동일한 레이블에).<br/>            읽기/쓰기 **bool**. |
| [`order`](/slides/python-net/ko/aspose.slides.charts/trendline/order/) | 다항식 추세선의 차수를 지정합니다. 다른 추세선 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다.<br/>            읽기/쓰기 **int**. |
| [`period`](/slides/python-net/ko/aspose.slides.charts/trendline/period/) | 이동 평균 추세선의 기간을 지정합니다.<br/>            다른 추세선 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다.<br/>            읽기/쓰기 **int**. |
| [`display_r_squared_value`](/slides/python-net/ko/aspose.slides.charts/trendline/display_r_squared_value/) | 추세선의 R-squared 값이 차트에 표시되도록 지정합니다(방정식과 동일한 레이블에).<br/>            읽기/쓰기 **bool**. |
| [`related_legend_entry`](/slides/python-net/ko/aspose.slides.charts/trendline/related_legend_entry/) | 이 추세선과 관련된 범례 항목을 나타냅니다.<br/>            읽기 전용 [`ILegendEntryProperties`](/slides/python-net/ko/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/ko/aspose.slides.charts/trendline/text_frame_for_overriding/) | 리치 서식 텍스트를 포함할 수 있습니다. 이 속성이 None이 아니면 이 <br/>            서식이 지정된 텍스트 값이 데이터 레이블의 자동 생성 텍스트를 대체합니다.<br/>            자동 생성 텍스트는 ShowSeriesName, <br/>            ShowValue 등 속성에 의해 관리되며 TextFormatManager.TextFormat 속성으로 서식이 지정된 텍스트를 의미합니다.<br/>            읽기 전용 [`ITextFrame`](/slides/python-net/ko/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/trendline/text_format/) | 텍스트 형식을 반환합니다.<br/>            읽기 전용 [`IChartTextFormat`](/slides/python-net/ko/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/trendline/chart/) | 상위 차트를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/trendline/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ko/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | 매개변수 "text"의 텍스트로 TextFrameForOverriding을 초기화합니다.<br/>            TextFrameForOverriding이 이미 초기화된 경우 텍스트만 변경합니다. |

### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)