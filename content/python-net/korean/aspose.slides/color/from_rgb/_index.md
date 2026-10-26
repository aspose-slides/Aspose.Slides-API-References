---
title: from_rgb method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/color/from_rgb/
weight: 50
---
## from_rgb(r, g, b) {#int-int-int}
지정된 빨간색, 녹색 및 파란색 값으로부터 불투명 색상(alpha는 255)을 생성합니다.

### 반환

지정된 값으로부터 생성된 색상입니다.



```python
@staticmethod
def from_rgb(r, g, b):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| r | **int** | 빨간색 구성 요소 값입니다. 유효값은 0부터 255까지입니다. |
| g | **int** | 녹색 구성 요소 값입니다. 유효값은 0부터 255까지입니다. |
| b | **int** | 파란색 구성 요소 값입니다. 유효값은 0부터 255까지입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **ValueError** | 구성 요소 값이 0보다 작거나 255보다 큽니다. |



### 참조
* 클래스 [`Color`](/slides/python-net/ko/aspose.slides/color)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)