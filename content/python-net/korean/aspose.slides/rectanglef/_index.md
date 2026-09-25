---
title: RectangleF class
second_title: Aspose.Slides for Python via .NET API 참조
description: 사각형의 위치와 크기를 나타내는 네 개의 부동 소수점 숫자 집합을 저장합니다.
type: docs
url: /ko/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF 클래스

사각형의 위치와 크기를 나타내는 네 개의 부동 소수점 숫자 집합을 저장합니다. .NET `System.Drawing.RectangleF`와 호환됩니다.

**상속:**[`RectangleF`](/slides/python-net/ko/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/ko/aspose.slides/rectangle)

RectangleF 유형은 다음 멤버를 제공합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/ko/aspose.slides/rectanglef/__init__/#float-float-float-float) | 지정된 위치와 크기로 사각형을 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`x`](/slides/python-net/ko/aspose.slides/rectanglef/x/) | 이 사각형의 왼쪽 위 모서리의 x 좌표를 가져옵니다.<br/>            읽기 전용 **float**. |
| [`y`](/slides/python-net/ko/aspose.slides/rectanglef/y/) | 이 사각형의 왼쪽 위 모서리의 y 좌표를 가져옵니다.<br/>            읽기 전용 **float**. |
| [`width`](/slides/python-net/ko/aspose.slides/rectanglef/width/) | 이 사각형의 너비를 가져옵니다.<br/>            읽기 전용 **float**. |
| [`height`](/slides/python-net/ko/aspose.slides/rectanglef/height/) | 이 사각형의 높이를 가져옵니다.<br/>            읽기 전용 **float**. |
| [`left`](/slides/python-net/ko/aspose.slides/rectanglef/left/) | 이 사각형의 왼쪽 가장자리의 x 좌표를 가져옵니다. `x`와 같습니다.<br/>            읽기 전용 **float**. |
| [`top`](/slides/python-net/ko/aspose.slides/rectanglef/top/) | 이 사각형의 위쪽 가장자리의 y 좌표를 가져옵니다. `y`와 같습니다.<br/>            읽기 전용 **float**. |
| [`right`](/slides/python-net/ko/aspose.slides/rectanglef/right/) | 이 사각형의 `x`와 `width`를 합한 x 좌표를 가져옵니다.<br/>            읽기 전용 **float**. |
| [`bottom`](/slides/python-net/ko/aspose.slides/rectanglef/bottom/) | 이 사각형의 `y`와 `height`를 합한 y 좌표를 가져옵니다.<br/>            읽기 전용 **float**. |
| [`is_empty`](/slides/python-net/ko/aspose.slides/rectanglef/is_empty/) | 이 사각형의 모든 숫자 속성이 0인지를 지정합니다.<br/>            읽기 전용 **bool**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/ko/aspose.slides/rectanglef/contains/#float-float) | 지정된 점이 이 사각형 내에 포함되는지 확인합니다. |
| [`contains(self, point)`](/slides/python-net/ko/aspose.slides/rectanglef/contains/#pointf) | 지정된 점이 이 사각형 내에 포함되는지 확인합니다. |
| [`contains(self, rect)`](/slides/python-net/ko/aspose.slides/rectanglef/contains/#rectanglef) | `rect` 로 표시된 직사각형 영역이 이 사각형에 완전히 포함되는지 확인합니다. |


### 비고

사각형은 `==` 연산자를 사용하여 위치와 크기로 비교되며 사전 키 또는 집합 멤버로 사용할 수 있습니다.


### 참고
* 클래스 [`Rectangle`](/slides/python-net/ko/aspose.slides/rectangle)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)