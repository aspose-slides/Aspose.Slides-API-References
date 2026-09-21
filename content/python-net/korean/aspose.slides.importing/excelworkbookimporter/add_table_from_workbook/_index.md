---
title: add_table_from_workbook method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
지정된 Excel 워크북에서 테이블을 검색하고 지정된 좌표에서 해당 shape 컬렉션 끝에 추가합니다.

### 반환값

shape 컬렉션에 추가된 테이블입니다.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection) | 테이블이 추가될 shape 컬렉션입니다. |
| x | **float** | 테이블 위치 지정에 사용되는 X 좌표입니다. |
| y | **float** | 테이블 위치 지정에 사용되는 Y 좌표입니다. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook) | Excel 워크북입니다. |
| worksheet_name | **str** | 테이블이 포함된 워크시트의 이름입니다. |
| cell_range | **str** | 테이블을 정의하는 셀 범위입니다(예: "A1:D10"). |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 필수 매개변수가 None이거나 비어 있거나, 지정된 워크시트 또는 셀 범위가 유효하지 않을 때 발생합니다. |
| **RuntimeError(Proxy error(InvalidOperationException))** | 입력 데이터가 지원되지 않는 형식일 때 발생합니다. |


## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
지정된 Excel 워크북 파일에서 테이블을 검색하고 지정된 좌표에서 해당 shape 컬렉션 끝에 추가합니다.

### 반환값

shape 컬렉션에 추가된 테이블입니다.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection) | 테이블이 추가될 shape 컬렉션입니다. |
| x | **float** | 테이블 위치 지정에 사용되는 X 좌표입니다. |
| y | **float** | 테이블 위치 지정에 사용되는 Y 좌표입니다. |
| workbook_path | **str** | Excel 워크북 파일의 경로입니다. |
| worksheet_name | **str** | 테이블이 포함된 워크시트의 이름입니다. |
| cell_range | **str** | 테이블을 정의하는 셀 범위입니다(예: "A1:D10"). |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 필수 매개변수가 None이거나 비어 있거나, 지정된 워크시트 또는 셀 범위가 유효하지 않을 때 발생합니다. |
| **RuntimeError(Proxy error(IOException))** | 워크북 파일에 접근하는 동안 I/O 오류가 발생했을 때 발생합니다. |
| **RuntimeError(Proxy error(InvalidOperationException))** | 입력 데이터가 지원되지 않는 형식일 때 발생합니다. |


## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
지정된 Excel 워크북 파일에서 테이블을 검색하고 지정된 좌표에서 해당 shape 컬렉션 끝에 추가합니다.

### 반환값

shape 컬렉션에 추가된 테이블입니다.



```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection) | 테이블이 추가될 shape 컬렉션입니다. |
| x | **float** | 테이블 위치 지정에 사용되는 X 좌표입니다. |
| y | **float** | 테이블 위치 지정에 사용되는 Y 좌표입니다. |
| workbook_stream | **io.RawIOBase** | 워크북 데이터를 포함하는 스트림입니다. |
| worksheet_name | **str** | 테이블이 포함된 워크시트의 이름입니다. |
| cell_range | **str** | 테이블을 정의하는 셀 범위입니다(예: "A1:D10"). |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 필수 매개변수가 None이거나 비어 있거나, 지정된 워크시트 또는 셀 범위가 유효하지 않을 때 발생합니다. |
| **RuntimeError(Proxy error(InvalidOperationException))** | 입력 데이터가 지원되지 않는 형식일 때 발생합니다. |



### 참고
* 클래스 [`ExcelWorkbookImporter`](/slides/python-net/ko/aspose.slides.importing/excelworkbookimporter)
* 클래스 [`IExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 클래스 [`ITable`](/slides/python-net/ko/aspose.slides/itable)
* 모듈 [`aspose.slides.importing`](/slides/python-net/ko/aspose.slides.importing)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)