---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/ichartcategory/
---
## IChartCategory 클래스

차트 카테고리를 나타냅니다.

IChartCategory 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/ko/aspose.slides.charts/ichartcategory/use_cell/) | true이면 AsCell 속성이 실제값입니다.<br/> 다시 말해, worksheet는 <br/> 카테고리를 저장하는 데 사용됩니다 (이 경우 다중 레벨 카테고리를 지원합니다).<br/> false이면 AsLiteral 속성이 실제값입니다.<br/> 다시 말해, worksheet는 카테고리를 저장하는 데 사용되지 않습니다 <br/> (이 경우 다중 레벨 카테고리를 지원하지 않습니다).<br/> 읽기 전용 **bool**. |
| [`as_cell`](/slides/python-net/ko/aspose.slides.charts/ichartcategory/as_cell/) | IChartDataCell 객체를 반환하거나 설정합니다.<br/> 카테고리가 다중 레벨인 경우 레벨 "0"에 IChartDataCell 객체를 사용합니다.<br/> 읽기/쓰기 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ko/aspose.slides.charts/ichartcategory/as_literal/) | UseCell이 false인 경우 AsLiteral를 반환하거나 설정합니다.<br/> 읽기/쓰기 **any**. |
| [`value`](/slides/python-net/ko/aspose.slides.charts/ichartcategory/value/) | UseCell이 true이면 이 속성은 AsCell.Value 속성을 나타냅니다.<br/> UseCell이 false이면 이 속성은 AsLiteral 속성을 나타냅니다.<br/> 읽기/쓰기 **any**. |
| [`cached_value`](/slides/python-net/ko/aspose.slides.charts/ichartcategory/cached_value/) | 차트 카테고리의 캐시된 값을 가져옵니다.<br/> 읽기 전용 [`ICachedChartValue`](/slides/python-net/ko/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/ko/aspose.slides.charts/ichartcategory/grouping_levels/) | 차트 카테고리 그룹화 수준 값들의 관리되는 컨테이너입니다.<br/> 다중 레벨 카테고리는 하나 이상의 그룹화 수준을 포함합니다.<br/> 그룹화 수준 인덱스는 0부터 시작합니다.<br/> 읽기 전용 [`IChartCategoryLevelsManager`](/slides/python-net/ko/aspose.slides.charts/ichartcategorylevelsmanager). |

## 메서드

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ko/aspose.slides.charts/ichartcategory/remove/#) | 차트에서 카테고리를 제거합니다. |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)