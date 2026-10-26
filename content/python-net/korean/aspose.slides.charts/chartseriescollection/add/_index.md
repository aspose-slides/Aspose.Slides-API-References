---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
새 차트 시리즈를 만들고 컬렉션에 추가합니다.

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
[`ChartDataCell`](/slides/python-net/ko/aspose.slides.charts/chartdatacell)에서 새 차트 시리즈를 만들고 컬렉션에 추가합니다.

### 반환

컬렉션에 이미 있는 차트 시리즈 또는 추가된 차트 시리즈.

```python
def add(self, cell_with_series_name, type):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell) | 시리즈 이름을 포함하는 셀. |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 시리즈 유형을 설정하는 유형 |

### 비고

이미 컬렉션에 동일한 셀에서 만든 차트 시리즈가 있는 경우, 메서드는 아무 것도 추가하지 않고 해당 인덱스를 반환합니다.

## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
[`ChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/chartcellcollection)에서 새 차트 시리즈를 만들고 컬렉션에 추가합니다.

### 반환

컬렉션에 이미 있는 차트 시리즈 또는 추가된 차트 시리즈.

```python
def add(self, cells_with_series_name, type):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcellcollection) | 시리즈 이름을 포함하는 셀들. |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 시리즈 유형을 설정하는 유형 |

### 비고

이미 컬렉션에 동일한 셀에서 만든 차트 시리즈가 있는 경우, 메서드는 아무 것도 추가하지 않고 해당 인덱스를 반환합니다.

## add(self, name, type) {#str-charttype}
값에서 새 차트 시리즈를 만들고 컬렉션에 추가합니다.

### 반환

추가된 차트 시리즈.

```python
def add(self, name, type):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| name | **str** | 시리즈 이름. |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 시리즈 유형을 설정하는 유형 |

### 참고
* 클래스 [`ChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/chartcellcollection)
* 클래스 [`ChartDataCell`](/slides/python-net/ko/aspose.slides.charts/chartdatacell)
* 클래스 [`ChartSeriesCollection`](/slides/python-net/ko/aspose.slides.charts/chartseriescollection)
* 열거형 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype)
* 클래스 [`IChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcellcollection)
* 클래스 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)
* 클래스 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)