---
title: ChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection 클래스

다음 [`ChartCategory`](/slides/python-net/ko/aspose.slides.charts/chartcategory)의 컬렉션을 나타냅니다.

ChartCategoryCollection 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`use_cells`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/use_cells/) | true이면 워크시트가 카테고리를 저장하는 데 사용됩니다(이 경우 다중 레벨 카테고리를 지원합니다).<br/>false이면 워크시트가 값을 저장하는 데 사용되지 않으며(그리고 이 경우 다중 레벨 카테고리를 지원하지 않습니다).<br/>읽기/쓰기 **bool**. |
| [`grouping_level_count`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | 사용된 카테고리 그룹화 수준의 개수를 반환합니다.<br/>다중 레벨 카테고리의 경우 1보다 큽니다.<br/>읽기 전용 **int**. |

지정된 인덱스에 있는 요소를 가져옵니다.

## 인덱서

| 이름 | 설명 |
| :- | :- |
| [`[index]`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | 카테고리가 컬렉션에 존재하면 반환합니다. 그렇지 않으면 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)에서 새 차트 카테고리를 생성하고 컬렉션에 추가합니다. |
| [`add(self, value)`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/add/#any) | 값에서 새 [`ChartCategory`](/slides/python-net/ko/aspose.slides.charts/chartcategory)를 생성하고 컬렉션에 추가합니다. |
| [`index_of(self, value)`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | 지정된 [`ChartCategory`](/slides/python-net/ko/aspose.slides.charts/chartcategory)를 검색하고 전체 컬렉션에서 첫 번째 발생 위치의 0부터 시작하는 인덱스를 반환합니다. |
| [`remove(self, value)`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | 지정된 값을 제거합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/remove_at/#int) | 주어진 인덱스에 있는 요소를 제거합니다. |
| [`clear(self)`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection/clear/#) | 컬렉션의 모든 요소를 제거합니다. |


### 또 보기
* 클래스 [`ChartCategory`](/slides/python-net/ko/aspose.slides.charts/chartcategory)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)