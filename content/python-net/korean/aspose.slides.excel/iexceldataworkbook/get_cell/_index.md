---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
지정된 워크시트에서 인덱스와 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 가져옵니다.

### 반환값

지정된 위치의 셀입니다.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| worksheet_index | **int** | 워크시트의 0 기반 인덱스입니다. |
| cell_name | **str** | Excel 스타일 셀 참조(예: "A1", "C5")입니다. |


## get_cell(self, worksheet_name, cell_name) {#str-str}
Excel 스타일 셀 이름(예: "B2")을 사용하여 지정된 워크시트에서 셀을 가져옵니다.

### 반환값

지정된 위치의 셀입니다.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| worksheet_name | **str** | 워크시트 이름입니다. |
| cell_name | **str** | Excel 스타일 셀 참조(예: "A1", "C5")입니다. |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
인덱스와 셀 좌표를 사용하여 지정된 워크시트에서 셀을 가져옵니다.

### 반환값

지정된 위치의 셀입니다.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| worksheet_index | **int** | 워크시트의 0 기반 인덱스입니다. |
| row | **int** | 셀의 0 기반 행 인덱스입니다. |
| column | **int** | 셀의 0 기반 열 인덱스입니다. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
이름과 셀 좌표를 사용하여 지정된 워크시트에서 셀을 가져옵니다.

### 반환값

지정된 위치의 셀입니다.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| worksheet_name | **str** | 워크시트 이름입니다. |
| row | **int** | 셀의 0 기반 행 인덱스입니다. |
| column | **int** | 셀의 0 기반 열 인덱스입니다. |



### 참고
* 클래스 [`IExcelDataCell`](/slides/python-net/ko/aspose.slides.excel/iexceldatacell)
* 클래스 [`IExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook)
* 모듈 [`aspose.slides.excel`](/slides/python-net/ko/aspose.slides.excel)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)