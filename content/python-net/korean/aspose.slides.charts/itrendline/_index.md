---
title: ITrendline class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/itrendline/
---
## ITrendline 클래스

클래스는 차트 시리즈의 추세선을 나타냅니다.

ITrendline 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/ko/aspose.slides.charts/itrendline/trendline_name/) | 추세선의 이름을 가져오거나 설정합니다.<br/>            Read/write **str**. |
| [`trendline_type`](/slides/python-net/ko/aspose.slides.charts/itrendline/trendline_type/) | 추세선의 유형을 가져오거나 설정합니다.<br/>            Read/write [`ITrendline.trendline_type`](/slides/python-net/ko/aspose.slides.charts/itrendline/trendline_type). |
| [`format`](/slides/python-net/ko/aspose.slides.charts/itrendline/format/) | 추세선의 형식을 나타냅니다.<br/>            Read/write [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/ko/aspose.slides.charts/itrendline/backward/) | 추세선이 추세가 적용되는 시리즈의 데이터 이전에 연장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다.<br/>            값은 산점도 및 비산점도 차트 모두에서 0 이상의 값을 가져야 합니다.<br/>            Read/write **float**. |
| [`forward`](/slides/python-net/ko/aspose.slides.charts/itrendline/forward/) | 추세선이 추세가 적용되는 시리즈의 데이터 이후에 연장되는 카테고리(또는 산점도 차트의 단위) 수를 지정합니다.<br/>            산점도 및 비산점도 차트에서는 값이 0 이상의 값을 가져야 합니다.<br/>            Read/write **float**. |
| [`intercept`](/slides/python-net/ko/aspose.slides.charts/itrendline/intercept/) | 추세선이 y축을 교차하는 값을 지정합니다. 이 속성은 추세선 유형이 exp, linear 또는 poly인 경우에만 지원됩니다.<br/>            Read/write **float**. |
| [`display_equation`](/slides/python-net/ko/aspose.slides.charts/itrendline/display_equation/) | 추세선의 방정식이 차트에 표시되도록 지정합니다(R-squared value와 동일한 레이블에 표시).<br/>            Read/write **bool**. |
| [`order`](/slides/python-net/ko/aspose.slides.charts/itrendline/order/) | 다항식 추세선의 차수를 지정합니다. 다른 추세선 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다.<br/>            Read/write **int**. |
| [`period`](/slides/python-net/ko/aspose.slides.charts/itrendline/period/) | 이동 평균 추세선의 기간을 지정합니다. 다른 추세선 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다.<br/>            Read/write **int**. |
| [`display_r_squared_value`](/slides/python-net/ko/aspose.slides.charts/itrendline/display_r_squared_value/) | 추세선의 R-squared 값이 차트에 표시되도록 지정합니다(방정식과 동일한 레이블에).<br/>            Read/write **bool**. |
| [`related_legend_entry`](/slides/python-net/ko/aspose.slides.charts/itrendline/related_legend_entry/) | 이 추세선과 관련된 범례 항목을 나타냅니다.<br/>            Read-only [`ILegendEntryProperties`](/slides/python-net/ko/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/ko/aspose.slides.charts/itrendline/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/itrendline/text_format/) |  |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/itrendline/chart/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/itrendline/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/itrendline/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ko/aspose.slides.charts/itrendline/add_text_frame_for_overriding/#str) |  |

### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)