---
title: RectangleF
second_title: Aspose.Slides for C++ API 레퍼런스
description: "이미지의 사각형 영역을 나타내며, 좌상단 모서리의 X와 Y 좌표 및 너비와 높이를 단정밀도 부동소수점으로 정의합니다. 이 타입은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. 절대 System::SmartPtr 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오."
type: docs
weight: 248
url: /ko/system.drawing/rectanglef/
---
## RectangleF 클래스

이미지의 사각형 영역을 나타내며, 좌상단 모서리의 X와 Y 좌표 및 너비와 높이를 단정밀도 부동소수점으로 정의합니다. 이 유형은 스택에 할당하고 값 혹은 참조로 함수에 전달해야 합니다. 절대 [System::SmartPtr](../../system/smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마십시오.

```cpp
class RectangleF
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | 지정된 점이 현재 객체가 나타내는 사각형 내부에 있는지 확인합니다. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | 지정된 점이 현재 객체가 나타내는 사각형 내부에 있는지 확인합니다. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | 지정된 사각형이 현재 객체가 나타내는 사각형 내부에 있는지 확인합니다. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | 현재 객체와 지정된 객체가 나타내는 사각형이 동일한지 확인합니다. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | 지정된 가장자리 위치를 갖는 사각형을 나타내는 새로운 [RectangleF](./) 객체를 생성합니다. |
| **float** [get_Bottom](./get_bottom/)() const | 현재 객체가 나타내는 사각형의 아래쪽 가장자리 y 좌표를 반환합니다. |
| **float** [get_Height](./get_height/)() const | 현재 객체가 나타내는 사각형의 높이를 반환합니다. |
| **bool** [get_IsEmpty](./get_isempty/)() const | 현재 객체가 나타내는 사각형의 좌상단 모서리 X와 Y 좌표 및 너비와 높이가 0인지 확인합니다. |
| **float** [get_Left](./get_left/)() const | 현재 객체가 나타내는 사각형의 왼쪽 가장자리 X 좌표를 반환합니다. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | 현재 객체가 나타내는 사각형의 좌상단 모서리 위치를 지정하는 [PointF](../pointf/) 클래스의 인스턴스를 반환합니다. |
| **float** [get_Right](./get_right/)() const | 현재 객체가 나타내는 사각형의 오른쪽 가장자리 X 좌표를 반환합니다. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | 현재 객체가 나타내는 사각형의 너비와 높이를 지정하는 [SizeF](../sizef/) 클래스의 인스턴스를 반환합니다. |
| **float** [get_Top](./get_top/)() const | 현재 객체가 나타내는 사각형의 위쪽 가장자리 Y 좌표를 반환합니다. |
| **float** [get_Width](./get_width/)() const | 현재 객체가 나타내는 사각형의 너비를 반환합니다. |
| **float** [get_X](./get_x/)() const | 현재 객체가 나타내는 사각형의 좌상단 모서리 X 좌표를 반환합니다. |
| **float** [get_Y](./get_y/)() const | 현재 객체가 나타내는 사각형의 좌상단 모서리 Y 좌표를 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체의 해시 코드를 반환합니다. |
| void [Inflate](./inflate/)(**float**, **float**) | 현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양쪽 방향으로 증가합니다. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | 현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 크기 객체의 너비와 높이 값에 해당하는 양만큼 양쪽 방향으로 증가합니다. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | 지정된 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양쪽 방향으로 증가합니다. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | 현재 객체가 나타내는 사각형을 지정된 객체가 나타내는 사각형과의 교차 결과 사각형으로 교체합니다. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | 지정된 사각형들의 교차 결과인 사각형을 반환합니다. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | 현재 객체와 지정된 객체가 나타내는 사각형이 교차하는지 확인합니다. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | 현재 객체가 나타내는 사각형의 위치를 지정된 양만큼 이동시킵니다. |
| void [Offset](./offset/)(**float**, **float**) | 현재 객체가 나타내는 사각형의 위치를 지정된 양만큼 이동시킵니다. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 항상 true를 반환합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 항상 false를 반환합니다. |
| [RectangleF](./rectanglef/)() | X와 Y 좌표 및 너비와 높이 값을 0으로 설정한 사각형을 나타내는 새로운 [RectangleF](./) 객체 인스턴스를 생성합니다. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | 지정된 좌상단 모서리 좌표와 너비 및 높이를 갖는 사각형을 나타내는 새로운 [RectangleF](./) 객체 인스턴스를 생성합니다. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | [PointF](../pointf/) 클래스의 인스턴스로 지정된 좌상단 모서리 좌표와 [SizeF](../sizef/) 클래스의 인스턴스로 지정된 너비와 높이를 갖는 사각형을 나타내는 새로운 [RectangleF](./) 객체 인스턴스를 생성합니다. |
| explicit [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | 지정된 사각형과 동등한 사각형을 나타내는 새로운 [RectangleF](./) 객체 인스턴스를 생성합니다. |
| void [set_Height](./set_height/)(**float**) | 현재 객체가 나타내는 사각형의 높이를 설정합니다. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | 현재 객체가 나타내는 사각형의 좌상단 모서리 위치를 설정합니다. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | 현재 객체가 나타내는 사각형의 너비와 높이를 설정합니다. |
| void [set_Width](./set_width/)(**float**) | 현재 객체가 나타내는 사각형의 너비를 설정합니다. |
| void [set_X](./set_x/)(**float**) | 현재 객체가 나타내는 사각형의 좌상단 모서리 X 좌표를 설정합니다. |
| void [set_Y](./set_y/)(**float**) | 현재 객체가 나타내는 사각형의 좌상단 모서리 Y 좌표를 설정합니다. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 현재 객체의 문자열 표현을 반환합니다. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | 지정된 사각형들의 합집합 결과인 사각형을 반환합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [Empty](./empty/) | 위치와 크기 값이 모두 0인 빈 사각형입니다. |

## 참조

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)