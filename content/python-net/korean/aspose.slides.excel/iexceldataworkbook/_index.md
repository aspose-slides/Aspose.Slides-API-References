---
title: IExcelDataWorkbook class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.excel/iexceldataworkbook/
---
## IExcelDataWorkbook 클래스

일반적인 사용을 위해 Excel 데이터에 접근할 수 있는 워크북을 나타냅니다.

IExcelDataWorkbook 타입은 다음 멤버를 노출합니다:

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook/get_cell/#int-int-int) | 지정된 워크시트에서 인덱스와 셀 좌표를 사용하여 셀을 검색합니다. |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook/get_cell/#str-int-int) | 지정된 워크시트에서 이름과 셀 좌표를 사용하여 셀을 검색합니다. |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook/get_cell/#int-str) | 지정된 워크시트에서 인덱스와 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 검색합니다. |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook/get_cell/#str-str) | 지정된 워크시트에서 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 검색합니다. |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook/get_cells/#str-bool) | 지정된 수식과 일치하는 워크북의 셀 컬렉션을 검색합니다. |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook/get_charts_from_worksheet/#str) | Excel 워크북의 지정된 워크시트에 있는 모든 차트의 인덱스와 이름을 포함하는 사전을 검색합니다. |
| [`get_worksheet_names(self)`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook/get_worksheet_names/#) | Excel 워크북에 포함된 모든 워크시트의 이름을 검색합니다. |

### 참고
* 모듈 [`aspose.slides.excel`](/slides/python-net/ko/aspose.slides.excel)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)