---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
컬렉션에 새 셀을 추가합니다.


```python
def add(self, cell):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell) | 추가할 새 셀. |


## add(self, value) {#any}
지정된 값으로부터 [`ChartDataCell`](/slides/python-net/ko/aspose.slides.charts/chartdatacell)를 생성하고 컬렉션에 추가합니다.


```python
def add(self, value):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| value | **any** | 값. |

### 비고

이 메서드는 이름이 AUTO_DATA인 워크시트를 추가하고 그곳에 모든 값을 추가합니다.  [`ChartDataWorkbook`](/slides/python-net/ko/aspose.slides.charts/chartdataworkbook)를 사용하여 Cell 값을 추가하거나 편집하는 경우, 이 워크시트를 사용하지 않도록 하세요.
Maximum number of values added using this method must not exceed 16711680

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 제한을 초과한 경우 |



### 또 보기
* 클래스 [`ChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/chartcellcollection)
* 클래스 [`ChartDataCell`](/slides/python-net/ko/aspose.slides.charts/chartdatacell)
* 클래스 [`ChartDataWorkbook`](/slides/python-net/ko/aspose.slides.charts/chartdataworkbook)
* 클래스 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)