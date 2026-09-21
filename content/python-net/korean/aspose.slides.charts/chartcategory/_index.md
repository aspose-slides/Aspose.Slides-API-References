---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/chartcategory/
---
## ChartCategory 클래스

차트 카테고리를 나타냅니다.

ChartCategory 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`use_cell`](/slides/python-net/ko/aspose.slides.charts/chartcategory/use_cell/) | true이면 AsCell 속성이 실제입니다. 다시 말해, 워크시트를 사용하여 <br/>카테고리를 저장합니다(이 경우 다중 레벨 카테고리를 지원합니다).<br/>false이면 AsLiteral 속성이 실제입니다. 다시 말해, 워크시트를 사용하여 <br/>카테고리를 저장하지 않습니다(이 경우 다중 레벨 카테고리를 지원하지 않습니다).<br/>읽기 전용 **bool**. |
| [`as_cell`](/slides/python-net/ko/aspose.slides.charts/chartcategory/as_cell/) | IChartDataCell 개체를 반환하거나 설정합니다.<br/>카테고리가 다중 레벨이면 레벨 "0"에 IChartDataCell 개체를 사용합니다.<br/>읽기/쓰기 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ko/aspose.slides.charts/chartcategory/as_literal/) | AsLiteral 개체를 반환하거나 설정합니다.<br/>읽기/쓰기 **any**. |
| [`value`](/slides/python-net/ko/aspose.slides.charts/chartcategory/value/) | UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다.<br/>UseCell이 false이면 이 속성은 AsLiteral 속성을 나타냅니다.<br/>읽기/쓰기 **any**. |
| [`grouping_levels`](/slides/python-net/ko/aspose.slides.charts/chartcategory/grouping_levels/) | 차트 카테고리 그룹 수준 값들의 관리 컨테이너입니다.<br/>다중 레벨 카테고리는 하나 이상의 그룹 수준을 포함합니다.<br/>그룹 수준 인덱스는 0부터 시작합니다.<br/>읽기 전용 [`IChartCategoryLevelsManager`](/slides/python-net/ko/aspose.slides.charts/ichartcategorylevelsmanager). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides.charts/chartcategory/remove/#) | 차트에서 카테고리를 제거합니다. |

### 참조
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)