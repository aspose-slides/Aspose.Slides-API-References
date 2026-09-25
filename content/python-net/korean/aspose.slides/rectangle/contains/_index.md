---
title: contains method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
지정된 점이 이 사각형 안에 포함되어 있는지 판단합니다.

### 반환

`True` if the point is contained within this rectangle; otherwise, `False`.

```python
def contains(self, point):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/ko/aspose.slides/point) | 테스트할 점. `x` 및 `y` 속성을 가진 모든 객체가 허용됩니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **TypeError** | 잘못된 인자 수. |

## contains(self, rect) {#rectangle}
`rect` 로 표현된 사각형 영역이 이 사각형 안에 완전히 포함되는지 판단합니다.

### 반환

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.

```python
def contains(self, rect):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/ko/aspose.slides/rectangle) | 테스트할 사각형. `x`, `y`, `width` 및 `height` 속성을 가진 모든 객체가 허용됩니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **TypeError** | 잘못된 인자 수. |

## contains(self, x, y) {#int-int}
지정된 점이 이 사각형 안에 포함되어 있는지 판단합니다.

### 반환

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.

```python
def contains(self, x, y):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **int** | 테스트할 점의 x좌표. |
| y | **int** | 테스트할 점의 y좌표. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **TypeError** | 잘못된 인자 수. |

### 참조
* 클래스 [`Point`](/slides/python-net/ko/aspose.slides/point)
* 클래스 [`Rectangle`](/slides/python-net/ko/aspose.slides/rectangle)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)