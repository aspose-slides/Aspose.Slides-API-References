---
title: delete_column method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
지정된 열을 삭제합니다


```python
def delete_column(self, column_index):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| column_index | **int** | 삭제할 열의 0부터 시작하는 인덱스. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 행렬에서 마지막 단일 열을 삭제하려고 할 때 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | columnIndex가 0보다 작거나 ColumnCount보다 크거나 같을 경우 |



### 참고
* 클래스 [`MathMatrix`](/slides/python-net/ko/aspose.slides.mathtext/mathmatrix)
* 모듈 [`aspose.slides.mathtext`](/slides/python-net/ko/aspose.slides.mathtext)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)