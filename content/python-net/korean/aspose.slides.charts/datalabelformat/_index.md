---
title: DataLabelFormat class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat 클래스

DataLabel에 대한 서식 옵션을 나타냅니다.

**상속:**[`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat) → [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)

DataLabelFormat 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_number_format_linked_to_source`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/) | 읽기/쓰기 **bool**. |
| [`number_format`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/number_format/) | DataLabels 객체의 형식 문자열을 나타냅니다.<br/>            읽기/쓰기 **str**. |
| [`format`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/format/) | 데이터 레이블의 형식을 나타냅니다.<br/>            읽기 전용 [`IFormat`](/slides/python-net/ko/aspose.slides.charts/iformat). |
| [`position`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/position/) | 데이터 레이블의 위치를 나타냅니다.<br/>            읽기/쓰기 [`LegendDataLabelPosition`](/slides/python-net/ko/aspose.slides.charts/legenddatalabelposition). |
| [`show_legend_key`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_legend_key/) | 지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다.<br/>            데이터 레이블 범례 키가 표시되는 경우 True.<br/>            읽기/쓰기 **bool**. |
| [`show_value`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_value/) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다.<br/>            True이면 백분율 값을 표시합니다. False이면 숨깁니다.<br/>            읽기/쓰기 **bool**. |
| [`show_category_name`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_category_name/) | 지정된 차트의 데이터 레이블 카테고리 이름 표시 동작을 나타냅니다.<br/>            True이면 차트의 데이터 레이블에 카테고리 이름을 표시합니다. False이면 숨깁니다.<br/>            읽기/쓰기 **bool**. |
| [`show_series_name`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_series_name/) | 차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 반환하거나 설정합니다.<br/>            True이면 시리즈 이름을 표시합니다. False이면 숨깁니다.<br/>            읽기/쓰기 **bool**. |
| [`show_percentage`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_percentage/) | 지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다.<br/>            True이면 백분율 값을 표시합니다. False이면 숨깁니다.<br/>            읽기/쓰기 **bool**. |
| [`show_bubble_size`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_bubble_size/) | 지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다.<br/>            True이면 버블 크기 값을 표시합니다. False이면 숨깁니다.<br/>            읽기/쓰기 **bool**. |
| [`show_leader_lines`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_leader_lines/) | 지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다.<br/>            True이면 리더 라인을 표시합니다. False이면 숨깁니다.<br/>            읽기/쓰기 **bool**. |
| [`show_label_value_from_cell`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_label_value_from_cell/) | 지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다.<br/>            True이면 셀 값을 표시합니다. False이면 숨깁니다.<br/>            읽기/쓰기 **bool**. |
| [`show_label_as_data_callout`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/show_label_as_data_callout/) | 지정된 차트의 데이터 레이블을 데이터 콜아웃으로 표시할지 데이터 레이블로 표시할지 결정합니다.<br/>            <br/>            이 DataLabelFormat 객체의 상위가 DataLabelCollection 데이터 레이블 컬렉션인 경우, 이<br/>            속성은 DataLabelCollection 컬렉션에 있는 새로운 데이터 레이블에 대한 ShowLabelAsDataCallout 속성의 기본값을 가져오거나 설정합니다.<br/>            이 속성에 값을 설정하면 DataLabelCollection 컬렉션에 있는 모든 데이터 레이블의 ShowLabelAsDataCallout 속성에도 해당 값이 설정됩니다.<br/>            (예: "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" 은 모든 DataLabels[i].ShowLabelAsDataCallout가 val과 동일하도록 합니다.) |
| [`separator`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/separator/) | 차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다.<br/>            읽기/쓰기 **str**. |
| [`text_format`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/text_format/) | 차트 텍스트 형식을 반환합니다.<br/>            읽기 전용 [`IChartTextFormat`](/slides/python-net/ko/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/chart/) | 차트를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/datalabelformat/presentation/) |  |


### 참조
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 클래스 [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)