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

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/chart/) | 부모 차트를 반환합니다.<br/>            읽기 전용 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/is_visible/) | False는 데이터 레이블이 기본적으로 표시되지 않음을 의미합니다 (따라서 DefaultDataLabelFormat 속성의 모든 Show*-flags (ShowValue, ...)가 false입니다).<br/>            읽기 전용 **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | 컬렉션에서 표시되는 데이터 레이블 수를 가져옵니다.<br/>            읽기 전용 **int**. |
| [`count`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/count/) | 컬렉션의 모든 데이터 레이블 수를 가져옵니다.<br/>            읽기 전용 **int**. |
| [`default_data_label_format`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/default_data_label_format/) | 기본 데이터 레이블 형식을 가져옵니다.<br/>            읽기 전용 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/leader_lines_format/) | 데이터 레이블 리더 라인 형식을 나타냅니다.<br/>            읽기 전용 [`IChartLinesFormat`](/slides/python-net/ko/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/parent_series/) | 부모 시리즈를 가져옵니다.<br/>            읽기 전용 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries). |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/presentation/) |  |

지정된 인덱스를 가진 데이터 포인트의 데이터 레이블을 가져옵니다.

## 인덱서

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/hide/#) | DefaultDataLabelFormat 속성의 모든 Show*-flags (ShowValue, ...)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다.<br/>            이후 IsVisible는 false가 됩니다. |
| [`index_of(self, value)`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | 컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다. |

### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)