---
title: add method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

### 반환

새 차트 시리즈.



```python
def add(self, type):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 시리즈 유형 |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
[`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

### 반환

컬렉션에 이미 존재하는 시리즈이거나 새로 추가된 차트 시리즈.



```python
def add(self, cell_with_series_name, type):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell) | 시리즈 이름을 포함하는 셀. |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 시리즈 유형을 설정합니다. |

### 비고

같은 셀에서 생성된 차트 시리즈가 이미 컬렉션에 있는 경우, 메서드는 아무 것도 추가하지 않고 해당 인덱스를 반환합니다.



## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
[`IChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcellcollection)에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

### 반환

컬렉션에 이미 존재하는 시리즈이거나 새로 추가된 차트 시리즈.



```python
def add(self, cells_with_series_name, type):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcellcollection) | 시리즈 이름을 포함하는 셀들. |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 시리즈 유형을 설정합니다. |

### 비고

같은 셀에서 생성된 차트 시리즈가 이미 컬렉션에 있는 경우, 메서드는 아무 것도 추가하지 않고 해당 인덱스를 반환합니다.


## add(self, name, type) {#str-charttype}
값에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

### 반환

새 차트 시리즈.



```python
def add(self, name, type):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| name | **str** | 시리즈 이름. |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 시리즈 유형을 설정합니다. |



### 참고
* 열거형 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype)
* 클래스 [`IChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcellcollection)
* 클래스 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)
* 클래스 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries)
* 클래스 [`IChartSeriesCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriescollection)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)