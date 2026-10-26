---
title: from_argb method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
32비트 ARGB 값으로부터 색상을 생성합니다.

### 반환

지정된 값으로부터 생성된 색상입니다.



```python
@staticmethod
def from_argb(argb):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| argb | **int** | 32비트 ARGB 값(부호형 또는 부호 없음)을 지정하는 값. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **ValueError** | 구성 요소 값이 0보다 작거나 255보다 큽니다. |
| **TypeError** | 인수의 개수 또는 유형이 잘못되었습니다. |


## from_argb(alpha, base_color) {#int-color}
지정된 알파 값과 기본 색상으로부터 색상을 생성합니다.

### 반환

지정된 값들로부터 생성된 색상입니다.



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| alpha | **int** | 알파 구성 요소 값입니다. 유효한 값은 0에서 255까지입니다. |
| base_color | [`Color`](/slides/python-net/ko/aspose.slides/color) | 새 색상을 만들기 위한 기준 색상입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **ValueError** | 구성 요소 값이 0보다 작거나 255보다 큽니다. |
| **TypeError** | 인수의 개수 또는 유형이 잘못되었습니다. |


## from_argb(red, green, blue) {#int-int-int}
지정된 빨강, 초록 및 파랑 값으로부터 불투명 색상(알파는 255)을 생성합니다.

### 반환

지정된 값들로부터 생성된 색상입니다.



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| red | **int** | 빨강 구성 요소 값입니다. 유효한 값은 0에서 255까지입니다. |
| green | **int** | 초록 구성 요소 값입니다. 유효한 값은 0에서 255까지입니다. |
| blue | **int** | 파랑 구성 요소 값입니다. 유효한 값은 0에서 255까지입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **ValueError** | 구성 요소 값이 0보다 작거나 255보다 큽니다. |
| **TypeError** | 인수의 개수 또는 유형이 잘못되었습니다. |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
네 개의 ARGB 구성 요소(알파, 빨강, 초록, 파랑) 값으로부터 색상을 생성합니다.

### 반환

지정된 값들로부터 생성된 색상입니다.



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| 매개변수 | 타입 | 설명 |
| :- | :- | :- |
| alpha | **int** | 알파 구성 요소 값입니다. 유효한 값은 0에서 255까지입니다. |
| red | **int** | 빨강 구성 요소 값입니다. 유효한 값은 0에서 255까지입니다. |
| green | **int** | 초록 구성 요소 값입니다. 유효한 값은 0에서 255까지입니다. |
| blue | **int** | 파랑 구성 요소 값입니다. 유효한 값은 0에서 255까지입니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **ValueError** | 구성 요소 값이 0보다 작거나 255보다 큽니다. |
| **TypeError** | 인수의 개수 또는 유형이 잘못되었습니다. |



### 참고
* 클래스 [`Color`](/slides/python-net/ko/aspose.slides/color)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)