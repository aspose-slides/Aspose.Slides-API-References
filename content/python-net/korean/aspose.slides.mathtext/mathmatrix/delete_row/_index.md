---
title: delete_row method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
지정된 행을 삭제합니다


```python
def delete_row(self, row_index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| row_index | **int** | 삭제할 행의 0부터 시작하는 인덱스입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 매트릭스에서 마지막 단일 행을 삭제하려고 할 때 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | rowIndex가 0보다 작거나 RowCount 이상인 경우 |



### 참조
* 클래스 [`MathMatrix`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)