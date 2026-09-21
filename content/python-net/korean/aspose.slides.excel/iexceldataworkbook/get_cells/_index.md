---
title: get_cells method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.excel/iexceldataworkbook/get_cells/
weight: 20
---
## get_cells(self, formula, skip_hidden_cells) {#str-bool}
지정된 수식과 일치하는 워크북의 셀 컬렉션을 검색합니다.

### 반환
지정된 수식과 일치하는 셀의 읽기 전용 목록입니다.



```python
def get_cells(self, formula, skip_hidden_cells):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| formula | **str** | 대상 셀을 식별하는 데 사용되는 수식 또는 범위 표현식(예: "Sheet1!A1:B3")입니다. |
| skip_hidden_cells | **bool** | `true`인 경우 숨겨진 셀(숨겨진 행이나 열에 있는 셀)은 결과에서 제외됩니다. |



### 참조
* 클래스 [`IExcelDataWorkbook`](/slides/python-net/ko/aspose.slides.excel/iexceldataworkbook)
* 모듈 [`aspose.slides.excel`](/slides/python-net/ko/aspose.slides.excel)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)