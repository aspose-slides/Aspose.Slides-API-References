---
title: Rectangle
second_title: Aspose.Slides for C++ API 레퍼런스
description: "이미지의 좌상단 코너의 정수 X 및 Y 좌표와 너비와 높이로 정의된 사각형 영역을 나타냅니다. 이 타입은 스택에 할당하고 값 혹은 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 절대 사용하지 마십시오."
type: docs
weight: 235
url: /ko/system.drawing/rectangle/
---
## Rectangle 클래스

Represents a rectangular area of an image defined as integer X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마십시오.

```cpp
class Rectangle
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | [Rectangle](./) 객체를 지정된 [RectangleF](../rectanglef/) 객체에서 만들며, [RectangleF](../rectanglef/) 객체의 위치와 크기 값을 다음보다 높은 정수 값으로 반올림합니다. |
| **bool** [Contains](./contains/)(int, int) const | 현재 객체가 나타내는 사각형 내에 지정된 점이 위치하는지 여부를 판단합니다. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | 현재 객체가 나타내는 사각형 내에 지정된 점이 위치하는지 여부를 판단합니다. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | 현재 객체가 나타내는 사각형 내에 지정된 사각형이 포함되는지 여부를 판단합니다. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | 현재 객체와 지정된 객체가 나타내는 사각형이 동일한지 여부를 판단합니다. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | 지정된 가장자리 위치를 사용하여 사각형을 나타내는 새로운 [Rectangle](./) 객체를 생성합니다. |
| int [get_Bottom](./get_bottom/)() const | 현재 객체가 나타내는 사각형의 하단 가장자리 y 좌표를 반환합니다. |
| int [get_Height](./get_height/)() const | 현재 객체가 나타내는 사각형의 높이를 반환합니다. |
| **bool** [get_IsEmpty](./get_isempty/)() const | 현재 객체가 나타내는 사각형의 좌상단 모서리 X 및 Y 좌표와 너비와 높이가 모두 0인지 여부를 판단합니다. |
| int [get_Left](./get_left/)() const | 현재 객체가 나타내는 사각형의 왼쪽 가장자리 X 좌표를 반환합니다. |
| [Point](../point/) [get_Location](./get_location/)() const | [Point](../point/) 클래스의 인스턴스를 반환하며, 이는 현재 객체가 나타내는 사각형의 좌상단 모서리 위치를 지정합니다. |
| int [get_Right](./get_right/)() const | 현재 객체가 나타내는 사각형의 오른쪽 가장자리 X 좌표를 반환합니다. |
| [Size](../size/) [get_Size](./get_size/)() const | [Size](../size/) 클래스의 인스턴스를 반환하며, 이는 현재 객체가 나타내는 사각형의 너비와 높이를 지정합니다. |
| int [get_Top](./get_top/)() const | 현재 객체가 나타내는 사각형의 상단 가장자리 Y 좌표를 반환합니다. |
| int [get_Width](./get_width/)() const | 현재 객체가 나타내는 사각형의 너비를 반환합니다. |
| int [get_X](./get_x/)() const | 현재 객체가 나타내는 사각형의 좌상단 모서리 X 좌표를 반환합니다. |
| int [get_Y](./get_y/)() const | 현재 객체가 나타내는 사각형의 좌상단 모서리 Y 좌표를 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체의 해시 코드를 반환합니다. |
| void [Inflate](./inflate/)(int, int) | 현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양쪽 방향으로 증가합니다. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | 현재 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 크기 객체의 너비와 높이 값에 따라 각각 해당 양만큼 양쪽 방향으로 증가합니다. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | 지정된 객체가 나타내는 사각형의 너비와 높이를 증가시키며, 사각형의 기하학적 중심 위치를 유지합니다. 너비와 높이는 지정된 양만큼 양쪽 방향으로 증가합니다. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | 현재 객체가 나타내는 사각형을 지정된 객체와의 교차 결과 사각형으로 교체합니다. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | 지정된 사각형들의 교차 결과인 사각형을 반환합니다. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | 현재 객체와 지정된 객체가 나타내는 사각형이 교차하는지 여부를 판단합니다. |
| void [Offset](./offset/)(const [Point](../point/)\&) | 현재 객체가 나타내는 사각형의 위치를 지정된 양만큼 오프셋합니다. |
| void [Offset](./offset/)(int, int) | 현재 객체가 나타내는 사각형의 위치를 지정된 양만큼 오프셋합니다. |
|  [operator RectangleF](./operator_rectanglef/)() const | [RectangleF](../rectanglef/) 객체를 반환하며, 이는 현재 객체가 나타내는 사각형과 동일한 사각형을 나타냅니다. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 항상 true를 반환합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 항상 false를 반환합니다. |
|  [Rectangle](./rectangle/)() | [Rectangle](./) 객체의 새 인스턴스를 생성하며, 이는 X 및 Y 좌표와 너비와 높이 값을 0으로 설정한 사각형을 나타냅니다. |
|  [Rectangle](./rectangle/)(int, int, int, int) | [Rectangle](./) 객체의 새 인스턴스를 생성하며, 지정된 좌상단 모서리 좌표와 너비 및 높이를 갖는 사각형을 나타냅니다. |
|  [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | [Rectangle](./) 객체의 새 인스턴스를 생성하며, 좌상단 모서리 좌표를 [Point](../point/) 클래스의 인스턴스로, 너비와 높이를 [Size](../size/) 클래스의 인스턴스로 지정한 사각형을 나타냅니다. |
|  [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | [Rectangle](./) 객체의 새 인스턴스를 생성하며, 지정된 것과 동일한 사각형을 나타냅니다. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | 지정된 [RectangleF](../rectanglef/) 객체를 사용하여 [Rectangle](./) 객체를 생성하고, [RectangleF](../rectanglef/) 객체의 위치와 크기 값을 가장 가까운 정수 값으로 반올림합니다. |
| void [set_Height](./set_height/)(int) | 현재 객체가 나타내는 사각형의 높이를 설정합니다. |
| void [set_Location](./set_location/)([Point](../point/)) | 현재 객체가 나타내는 사각형의 좌상단 모서리 위치를 설정합니다. |
| void [set_Size](./set_size/)([Size](../size/)) | 현재 객체가 나타내는 사각형의 너비와 높이를 설정합니다. |
| void [set_Width](./set_width/)(int) | 현재 객체가 나타내는 사각형의 너비를 설정합니다. |
| void [set_X](./set_x/)(int) | 현재 객체가 나타내는 사각형의 좌상단 모서리 X 좌표를 설정합니다. |
| void [set_Y](./set_y/)(int) | 현재 객체가 나타내는 사각형의 좌상단 모서리 Y 좌표를 설정합니다. |
| [String](../../system/string/) [ToString](./tostring/)() const | 현재 객체의 문자열 표현을 반환합니다. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | 지정된 [RectangleF](../rectanglef/) 객체를 사용하여 [Rectangle](./) 객체를 생성하고, [RectangleF](../rectanglef/) 객체의 위치와 크기 값을 다음보다 낮은 정수 값으로 내림합니다. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | 지정된 사각형들의 합집합 결과인 사각형을 반환합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [Empty](./empty/) | 위치와 크기 값이 모두 0인 빈 사각형, 즉 사각형을 의미합니다. |

## 참고

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)