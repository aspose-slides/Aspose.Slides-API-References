---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
지정된 워크시트에서 인덱스와 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 검색합니다.

### 반환값

지정된 위치에 있는 셀.



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| 매개변수 | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |


## get_cell(self, worksheet_name, cell_name) {#str-str}
지정된 워크시트에서 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 검색합니다.

### 반환값

지정된 위치에 있는 셀.



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| 매개변수 | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| cell_name | **str** | The Excel-style cell reference (e.g., "A1", "C5"). |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
지정된 워크시트에서 인덱스와 셀 좌표를 사용하여 셀을 검색합니다.

### 반환값

지정된 위치에 있는 셀.



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| 매개변수 | Type | Description |
| :- | :- | :- |
| worksheet_index | **int** | Zero-based index of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
지정된 워크시트에서 이름과 셀 좌표를 사용하여 셀을 검색합니다.

### 반환값

지정된 위치에 있는 셀.



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| 매개변수 | Type | Description |
| :- | :- | :- |
| worksheet_name | **str** | The name of the worksheet. |
| row | **int** | Zero-based row index of the cell. |
| column | **int** | Zero-based column index of the cell. |



### 참조
* 클래스 [`ExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/exceldataworkbook)
* 클래스 [`IExcelDataCell`](/slides/python-net/ko/aspose.slides.excel/iexceldatacell)
* 모듈 [`aspose.slides.excel`](/slides/python-net/ko/aspose.slides.excel)
* library [`Aspose.Slides`](/slides/python-net)