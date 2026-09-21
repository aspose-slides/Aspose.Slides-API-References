---
title: IDataLabelCollection class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection 클래스

시리즈 레이블을 나타냅니다.

IDataLabelCollection 타입은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | 컬렉션의 모든 데이터 레이블에 대한 기본 형식을 반환합니다.<br/>            읽기 전용 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | 데이터 레이블 리더 라인 형식을 나타냅니다.<br/>             읽기 전용 [`IChartLinesFormat`](/slides/python-net/ko/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/is_visible/) | False는 데이터 레이블이 기본적으로 보이지 않음을 의미합니다(따라서 <br/>            DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue, ...)가 false입니다).<br/>            읽기 전용 **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | 컬렉션에서 보이는 데이터 레이블 수를 가져옵니다.<br/>            읽기 전용 **int**. |
| [`count`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/count/) | 컬렉션의 모든 데이터 레이블 수를 가져옵니다.<br/>            읽기 전용 **int**. |
| [`parent_series`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/parent_series/) | 부모 차트 시리즈를 반환합니다.<br/>            읽기 전용 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/presentation/) |  |

지정된 인덱스를 가진 데이터 포인트에 대한 데이터 레이블을 가져옵니다.

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`hide(self)`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/hide/#) | DefaultDataLabelFormat 속성의 모든 Show*-플래그(ShowValue, ...)를 false 상태로 설정하여 데이터 레이블을 기본적으로 숨깁니다.<br/>            이후 IsVisible는 false가 됩니다. |
| [`index_of(self, value)`](/slides/python-net/ko/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | 컬렉션에서 지정된 DataLabel의 인덱스를 반환합니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)