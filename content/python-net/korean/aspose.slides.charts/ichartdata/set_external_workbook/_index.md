---
title: set_external_workbook method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
차트의 데이터 소스로 외부 워크북을 설정합니다. 차트 데이터는 대상 워크북에서 업데이트됩니다.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| workbook_path | **str** | 대상 워크북의 경로 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 외부 워크북을 사용할 수 없거나 로드할 수 없습니다. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
차트의 데이터 소스로 외부 워크북을 설정합니다.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| workbook_path | **str** | 대상 워크북의 경로 |
| update_chart_data | **bool** | 값이 false이면 워크북 경로만 업데이트됩니다. <br/><br/>             차트 데이터는 대상 워크북에서 로드 및 업데이트되지 않습니다. 대상 워크북이 존재하지 않거나 사용할 수 없을 때 사용할 수 있습니다.<br/><br/>             값이 true이면 차트 데이터가 대상 워크북에서 업데이트됩니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 외부 워크북을 사용할 수 없거나 로드할 수 없습니다. |



### 참고
* 클래스 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)