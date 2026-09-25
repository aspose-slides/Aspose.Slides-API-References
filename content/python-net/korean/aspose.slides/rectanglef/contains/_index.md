---
title: contains method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
지정된 point가 이 사각형 안에 포함되는지 판단합니다.

### 반환값

`True`이면 point가 이 사각형 안에 포함되고, 그렇지 않으면 `False`입니다.



```python
def contains(self, point):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ko/aspose.slides/pointf) | 테스트할 point. `x`와 `y` 속성을 가진 모든 객체가 허용됩니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **TypeError** | 잘못된 인수 개수입니다. |


## contains(self, rect) {#rectanglef}
`rect`으로 표시된 사각형 영역이 이 사각형 안에 완전히 포함되는지 판단합니다.

### 반환값

`True`이면 `rect`으로 표시된 사각형 영역이 이 사각형 안에 완전히 포함되고, 그렇지 않으면 `False`입니다.



```python
def contains(self, rect):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef) | 테스트할 사각형. `x`, `y`, `width` 및 `height` 속성을 가진 모든 객체가 허용됩니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **TypeError** | 잘못된 인수 개수입니다. |


## contains(self, x, y) {#float-float}
지정된 점이 이 사각형 안에 포함되는지 판단합니다.

### 반환값

`True`이면 `x`와 `y`로 정의된 점이 이 사각형 안에 포함되고, 그렇지 않으면 `False`입니다.



```python
def contains(self, x, y):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 테스트할 점의 x 좌표. |
| y | **float** | 테스트할 점의 y 좌표. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **TypeError** | 잘못된 인수 개수입니다. |



### 참고
* 클래스 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)
* 클래스 [`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)