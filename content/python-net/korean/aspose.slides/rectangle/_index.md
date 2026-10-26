---
title: Rectangle class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 직사각형의 위치와 크기를 나타내는 네 개의 정수를 저장합니다.
type: docs
url: /ko/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Rectangle 클래스

네 개의 정수를 저장하며, 이는 직사각형의 위치와 크기를 나타냅니다. .NET `System.Drawing.Rectangle`와 호환됩니다.

Rectangle 타입은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/ko/aspose.slides/rectangle/__init__/#int-int-int-int) | 지정된 위치와 크기로 직사각형을 생성합니다. 부동 소수점 값은 정수로 절단됩니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`x`](/slides/python-net/ko/aspose.slides/rectangle/x/) | 이 직사각형의 왼쪽 위 모서리의 x 좌표를 반환합니다.<br/>            읽기 전용 **int**. |
| [`y`](/slides/python-net/ko/aspose.slides/rectangle/y/) | 이 직사각형의 왼쪽 위 모서리의 y 좌표를 반환합니다.<br/>            읽기 전용 **int**. |
| [`width`](/slides/python-net/ko/aspose.slides/rectangle/width/) | 이 직사각형의 너비를 반환합니다.<br/>            읽기 전용 **int**. |
| [`height`](/slides/python-net/ko/aspose.slides/rectangle/height/) | 이 직사각형의 높이를 반환합니다.<br/>            읽기 전용 **int**. |
| [`left`](/slides/python-net/ko/aspose.slides/rectangle/left/) | 이 직사각형의 왼쪽 가장자리의 x 좌표를 반환합니다. `x`와 동일합니다.<br/>            읽기 전용 **int**. |
| [`top`](/slides/python-net/ko/aspose.slides/rectangle/top/) | 이 직사각형의 위쪽 가장자리의 y 좌표를 반환합니다. `y`와 동일합니다.<br/>            읽기 전용 **int**. |
| [`right`](/slides/python-net/ko/aspose.slides/rectangle/right/) | 이 직사각형의 `x`와 `width`의 합인 x 좌표를 반환합니다.<br/>            읽기 전용 **int**. |
| [`bottom`](/slides/python-net/ko/aspose.slides/rectangle/bottom/) | 이 직사각형의 `y`와 `height`의 합인 y 좌표를 반환합니다.<br/>            읽기 전용 **int**. |
| [`is_empty`](/slides/python-net/ko/aspose.slides/rectangle/is_empty/) | 이 직사각형의 모든 수치 속성이 0인지 여부를 지정합니다.<br/>            읽기 전용 **bool**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/ko/aspose.slides/rectangle/contains/#int-int) | 지정된 점이 이 직사각형 안에 포함되는지 확인합니다. |
| [`contains(self, point)`](/slides/python-net/ko/aspose.slides/rectangle/contains/#point) | 지정된 점이 이 직사각형 안에 포함되는지 확인합니다. |
| [`contains(self, rect)`](/slides/python-net/ko/aspose.slides/rectangle/contains/#rectangle) | `rect`가 나타내는 직사각형 영역이 이 직사각형 안에 완전히 포함되는지 확인합니다. |

### 참고

직사각형은 `==` 연산자로 위치와 크기로 비교되며, 사전 키 또는 집합 멤버로 사용할 수 있습니다.

### 참조
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)