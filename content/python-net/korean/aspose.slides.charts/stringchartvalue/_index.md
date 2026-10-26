---
title: StringChartValue class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/stringchartvalue/
---
## StringChartValue 클래스

pptx 프레젠테이션 문서에 저장될 수 있는 문자열 값을 두 가지 방법으로 나타냅니다:
1) 차트와 연결된 워크북의 셀/셀들에;
2) 리터럴 값으로.

**Inheritance:**[`StringChartValue`](/slides/python-net/ko/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/ko/aspose.slides.charts/basechartvalue)

StringChartValue 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`data_source_type`](/slides/python-net/ko/aspose.slides.charts/stringchartvalue/data_source_type/) | 후손에서 AsCell, AsCells, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 Data 속성의 값 타입을 지정합니다. 읽기/쓰기 [`DataSourceType`](/slides/python-net/ko/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/ko/aspose.slides.charts/stringchartvalue/data/) | Data 객체를 반환하거나 설정합니다. 읽기/쓰기 **any**. |
| [`as_cells`](/slides/python-net/ko/aspose.slides.charts/stringchartvalue/as_cells/) | null 값 할당은 허용되지 않습니다. 반환 값은 항상 None이 아닙니다. 읽기/쓰기 [`IChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/ko/aspose.slides.charts/stringchartvalue/as_literal_string/) | 값을 리터럴 문자열로 반환하거나 설정합니다. 읽기/쓰기 **str**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/ko/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | 지정된 셀에서 값을 설정합니다. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/ko/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | DataSourceType 속성이 DataSourceType.Worksheet인 경우, 이 메서드는 문자열 데이터를 나타내는 워크북의 셀 주소를 반환합니다. 그렇지 않으면 빈 문자열을 반환합니다. |

### 참조
* 클래스 [`BaseChartValue`](/slides/python-net/ko/aspose.slides.charts/basechartvalue)
* 클래스 [`StringChartValue`](/slides/python-net/ko/aspose.slides.charts/stringchartvalue)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)