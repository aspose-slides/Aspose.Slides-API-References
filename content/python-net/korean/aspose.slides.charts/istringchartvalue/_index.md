---
title: IStringChartValue class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue 클래스

pptx 프레젠테이션 문서에 문자열 값을 두 가지 방법으로 저장할 수 있습니다:
1) 차트와 연결된 워크북의 셀/셀들에;
2) 리터럴 값으로.

IStringChartValue 타입은 다음 멤버들을 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`as_literal_string`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue/as_literal_string/) | DataSourceType 속성이 DataSourceType.StringLiterals인 경우 리터럴 문자열을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`as_cells`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue/data/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`to_string(self)`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue/to_string/#) | 문자열 표현을 반환합니다. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | 지정된 셀에서 값을 설정합니다. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/ko/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | DataSourceType 속성이 DataSourceType.Worksheet인 경우 이 메서드는 문자열 데이터를 나타내는 워크북의 셀 주소를 반환합니다.<br/>            그렇지 않으면 빈 문자열을 반환합니다. |

### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)