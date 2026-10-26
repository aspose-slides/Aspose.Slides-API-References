---
title: get_cells method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.excel/exceldataworkbook/get_cells/
weight: 30
---
## get_cells(self, formula, skip_hidden_cells) {#str-bool}
지정된 수식과 일치하는 워크북의 셀 컬렉션을 검색합니다.

### 반환값

지정된 수식과 일치하는 셀의 읽기 전용 목록입니다.



```python
def get_cells(self, formula, skip_hidden_cells):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| formula | **str** | 대상 셀을 식별하기 위해 사용되는 수식 또는 범위 식(expression) (예: "Sheet1!A1:B3"). |
| skip_hidden_cells | **bool** | `true`인 경우, 숨김 셀(예: 숨김 행이나 열에 있는 셀)은 결과에서 제외됩니다. |



### 참고
* 클래스 [`ExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/exceldataworkbook)
* 모듈 [`aspose.slides.excel`](/slides/python-net/ko/aspose.slides.excel)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)