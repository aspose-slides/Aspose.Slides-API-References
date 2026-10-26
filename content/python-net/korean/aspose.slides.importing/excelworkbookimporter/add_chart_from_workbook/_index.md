---
title: add_chart_from_workbook method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
지정된 Excel 워크북에서 차트를 검색하여 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

### 반환값

shape 컬렉션에 추가된 차트입니다.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection) | 차트가 추가될 shape 컬렉션입니다. |
| x | **float** | 차트를 배치하기 위한 X 좌표입니다. |
| y | **float** | 차트를 배치하기 위한 Y 좌표입니다. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook) | Excel 워크북입니다. |
| worksheet_name | **str** | 차트를 포함하는 워크시트의 이름입니다. |
| chart_index | **int** | 삽입할 차트 shape의 0부터 시작하는 인덱스입니다. <br/><br/>            이 인덱스는 **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** 메서드를 사용하여 얻을 수 있습니다. |
| embed_all_workbook | **bool** | `true`인 경우 전체 워크북이 차트에 포함됩니다; <br/><br/>            `false`인 경우 차트 데이터만 포함됩니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 필수 매개변수가 None이거나 비어 있거나, 워크북에서 차트를 찾을 수 없는 경우 발생합니다. |


## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
지정된 Excel 워크북에서 차트를 검색하여 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

### 반환값

shape 컬렉션에 추가된 차트입니다.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection) | 차트가 추가될 shape 컬렉션입니다. |
| x | **float** | 차트를 배치하기 위한 X 좌표입니다. |
| y | **float** | 차트를 배치하기 위한 Y 좌표입니다. |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook) | Excel 워크북입니다. |
| worksheet_name | **str** | 차트를 포함하는 워크시트의 이름입니다. |
| chart_name | **str** | 추가될 차트의 이름입니다. |
| embed_all_workbook | **bool** | `true`인 경우 전체 워크북이 차트에 포함됩니다; <br/><br/>            `false`인 경우 차트 데이터만 포함됩니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 필수 매개변수가 None이거나 비어 있거나, 워크북에서 차트를 찾을 수 없는 경우 발생합니다. |


## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
지정된 Excel 워크북에서 차트를 검색하여 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

### 반환값

shape 컬렉션에 추가된 차트입니다.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection) | 차트가 추가될 shape 컬렉션입니다. |
| x | **float** | 차트를 배치하기 위한 X 좌표입니다. |
| y | **float** | 차트를 배치하기 위한 Y 좌표입니다. |
| workbook_stream | **io.RawIOBase** | 워크북 데이터를 포함하는 스트림입니다. |
| worksheet_name | **str** | 차트를 포함하는 워크시트의 이름입니다. |
| chart_name | **str** | 추가될 차트의 이름입니다. |
| embed_all_workbook | **bool** | `true`인 경우 전체 워크북이 차트에 포함됩니다; <br/><br/>            `false`인 경우 차트 데이터만 포함됩니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 필수 매개변수가 None이거나 비어 있거나, 워크북에서 차트를 찾을 수 없는 경우 발생합니다. |
| **RuntimeError(Proxy error(InvalidOperationException))** | 입력 데이터가 지원되지 않는 형식인 경우 발생합니다. |


## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
지정된 Excel 워크북에서 차트를 검색하여 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

### 반환값

shape 컬렉션에 추가된 차트입니다.



```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection) | 차트가 추가될 shape 컬렉션입니다. |
| x | **float** | 차트를 배치하기 위한 X 좌표입니다. |
| y | **float** | 차트를 배치하기 위한 Y 좌표입니다. |
| workbook_path | **str** | 차트를 포함하는 워크북 파일의 경로입니다. |
| worksheet_name | **str** | 차트를 포함하는 워크시트의 이름입니다. |
| chart_name | **str** | 추가될 차트의 이름입니다. |
| embed_workbook | **bool** | `true`인 경우 워크북이 차트에 포함됩니다; <br/><br/>            `false`인 경우 차트가 외부 워크북을 링크합니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 필수 매개변수가 None이거나 비어 있거나, 워크북에서 차트를 찾을 수 없는 경우 발생합니다. |
| **RuntimeError(Proxy error(IOException))** | 파일에 접근하는 중 I/O 오류가 발생했습니다. |
| **RuntimeError(Proxy error(InvalidOperationException))** | 입력 데이터가 지원되지 않는 형식인 경우 발생합니다. |



### 참조
* 클래스 [`ExcelWorkbookImporter`](/slides/python-net/ko/aspose.slides.importing/excelworkbookimporter)
* 클래스 [`IExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides.importing`](/slides/python-net/ko/aspose.slides.importing)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)