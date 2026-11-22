---
title: DataLabelCollection class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection 클래스

시리즈 레이블을 나타냅니다.

DataLabelCollection 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/chart/) | 상위 차트를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/is_visible/) | False는 데이터 레이블이 기본적으로 표시되지 않음을 의미합니다(따라서 DefaultDataLabelFormat 속성의 모든 <br/>            Show*-플래그(ShowValue, ...)가 false가 됩니다).<br/>            읽기 전용 **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | 컬렉션에서 표시되는 데이터 레이블의 수를 가져옵니다.<br/>            읽기 전용 **int**. |
| [`count`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/count/) | 컬렉션에 있는 모든 데이터 레이블의 수를 가져옵니다.<br/>            읽기 전용 **int**. |
| [`default_data_label_format`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/default_data_label_format/) | 기본 데이터 레이블 형식을 가져옵니다.<br/>            읽기 전용 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/leader_lines_format/) | 데이터 레이블 리더 라인 형식을 나타냅니다.<br/>             읽기 전용 [`IChartLinesFormat`](/slides/python-net/ko/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/parent_series/) | 상위 시리즈를 가져옵니다.<br/>            읽기 전용 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | 데이터 레이블에 대한 기본 도형 유형을 가져오거나 설정합니다.<br/>             정의된 도형이 없으면 [`ShapeType.NOT_DEFINED`](/slides/python-net/ko/aspose.slides/shapetype/NOT_DEFINED)를 반환합니다. |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/presentation/) |  |

지정된 인덱스를 가진 데이터 포인트에 대한 데이터 레이블을 가져옵니다.

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`hide(self)`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/hide/#) | 기본적으로 모든 Show*-플래그(ShowValue, ...)를 <br/>            DefaultDataLabelFormat 속성에서 false 상태로 설정하여 데이터 레이블을 숨깁니다.<br/>            IsVisible는 이후 false가 됩니다. |
| [`index_of(self, value)`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | 컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다. |


### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)