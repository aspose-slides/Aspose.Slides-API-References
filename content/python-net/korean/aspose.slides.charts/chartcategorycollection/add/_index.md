---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
컬렉션에 카테고리가 존재하면 반환합니다. 그렇지 않으면 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)에서 새 차트 카테고리를 생성하고 컬렉션에 추가합니다.

### 반환값

추가된 또는 기존 카테고리.

```python
def add(self, chart_data_cell):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell) | 차트 카테고리를 만들 때 사용하는 셀. |

## add(self, value) {#any}
값으로부터 새로운 [`ChartCategory`](/slides/python-net/ko/aspose.slides.charts/chartcategory)를 생성하고 컬렉션에 추가합니다.

### 반환값

추가된 [`IChartCategory`](/slides/python-net/ko/aspose.slides.charts/ichartcategory).

```python
def add(self, value):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| value | **any** | 값. |

### 비고

이 메서드는 이름이 AUTO_DATA인 워크시트를 추가하고 모든 값을 그곳에 추가합니다.  [`ChartDataWorkbook`](/slides/python-net/ko/aspose.slides.charts/chartdataworkbook)를 사용하여 셀 값을 추가하거나 편집할 경우, 이 워크시트를 사용하지 않도록 하십시오.
            이 메서드를 사용하여 추가할 수 있는 값의 최대 수는 16711680을 초과해서는 안 됩니다

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 제한을 초과한 경우 |

### 참조
* 클래스 [`ChartCategory`](/slides/python-net/ko/aspose.slides.charts/chartcategory)
* 클래스 [`ChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/chartcategorycollection)
* 클래스 [`ChartDataWorkbook`](/slides/python-net/ko/aspose.slides.charts/chartdataworkbook)
* 클래스 [`IChartCategory`](/slides/python-net/ko/aspose.slides.charts/ichartcategory)
* 클래스 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)