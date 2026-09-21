---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
컬렉션에 새 셀을 추가합니다.

```python
def add(self, chart_data_cell):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell) | 추가할 새 셀. |

## add(self, value) {#any}
지정된 값으로 [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)을(를) 생성하고 컬렉션에 추가합니다.

```python
def add(self, value):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| value | **any** | 값. |

### 비고

이 메서드는 이름이 AUTO_DATA인 워크시트를 추가하고 모든 값을 그곳에 삽입합니다.  [`IChartDataWorkbook`](/slides/python-net/ko/aspose.slides.charts/ichartdataworkbook)를 사용하여 셀 값을 추가하거나 편집하는 경우, 이 워크시트를 사용하지 않도록 하십시오
            이 메서드를 사용하여 추가되는 값의 최대 수는 16711680을 초과해서는 안 됩니다

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 제한을 초과한 경우 |

### 참조
* class [`IChartCellCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcellcollection)
* class [`IChartDataCell`](/slides/python-net/ko/aspose.slides.charts/ichartdatacell)
* class [`IChartDataWorkbook`](/slides/python-net/ko/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)