---
title: Point
second_title: Aspose.Slides for C++ API 레퍼런스
description: "2차원 평면에서 점의 정수 X 및 Y 좌표 쌍을 나타냅니다. 이 유형은 스택에 할당하고 값 또는 참조에 의해 함수에 전달해야 합니다. 절대로 System::SmartPtr 클래스를 사용하여 이 유형의 객체를 관리하지 마십시오."
type: docs
weight: 209
url: /ko/system.drawing/point/
---
## Point 클래스

Represents a pair of integer X and Y coordinates of a point on a 2-dimensional plane. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) 클래스를 manage objects of this type.

```cpp
class Point
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | [Size](../size/) 객체의 너비와 높이 값을 지정된 [Point](./) 객체의 X 및 Y 좌표 값에 각각 추가합니다. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | [PointF](../pointf/) 객체를 [PointF](../pointf/) 객체의 X 및 Y 좌표 값을 다음 높은 정수값으로 반올림하여 [Point](./) 객체로 생성합니다. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | 현재 객체와 지정된 객체가 동일한 X 및 Y 좌표 쌍을 나타내는지, 즉 같은지 판단합니다. |
| **bool** [get_IsEmpty](./get_isempty/)() const | X와 Y 좌표 값이 모두 0인지 판단합니다. |
| int [get_X](./get_x/)() const | 현재 객체가 나타내는 X 좌표 값을 반환합니다. |
| int [get_Y](./get_y/)() const | 현재 객체가 나타내는 Y 좌표 값을 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
| size_t [getStdHash](./getstdhash/)() const | 현재 객체에 대한 해시 값을 반환합니다. |
| **bool** [IsNull](./isnull/)() const | 항상 false를 반환합니다. |
| void [Offset](./offset/)(int, int) | 현재 객체가 나타내는 X 및 Y 좌표 값을 지정된 값만큼 오프셋합니다. |
| void [Offset](./offset/)([Point](./)) | 현재 객체가 나타내는 X 및 Y 좌표를 지정된 [Point](./) 객체가 나타내는 X 및 Y 좌표 값에 각각 오프셋합니다. |
|  [operator PointF](./operator_pointf/)() const | [PointF](../pointf/) 객체 인스턴스를 생성하고 현재 [Point](./) 객체의 X 및 Y 좌표 값으로 초기화합니다. |
|  [operator Size](./operator_size/)() const | [Size](../size/) 객체 인스턴스를 생성하고 현재 객체가 나타내는 X 및 Y 좌표 값으로 너비와 높이 값을 각각 초기화합니다. |
|  [Point](./point/)() | 새로운 [Point](./) 객체를 생성하고 X 및 Y 좌표 값을 0으로 초기화합니다. |
|  [Point](./point/)(int, int) | 새로운 [Point](./) 객체를 생성하고 지정된 값으로 초기화합니다. |
|  [Point](./point/)(const [Size](../size/)\&) | 새로운 [Point](./) 객체를 생성하고 지정된 [SizeF](../sizef/) 객체의 너비와 높이 값을 각각 X 및 Y 좌표 값으로 초기화합니다. |
|  [Point](./point/)(int) | 새로운 [Point](./) 객체를 생성하고 지정된 32비트 정수의 상위 16비트로 X 좌표 값을, 하위 16비트로 Y 좌표 값을 형성하여 초기화합니다. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | 지정된 [PointF](../pointf/) 객체의 [PointF](../pointf/) 객체의 X 및 Y 좌표 값을 가장 가까운 정수값으로 반올림하여 [Point](./) 객체를 생성합니다. |
| void [set_X](./set_x/)(int) | 현재 객체가 나타내는 X 좌표 값을 설정합니다. |
| void [set_Y](./set_y/)(int) | 현재 객체가 나타내는 Y 좌표 값을 설정합니다. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | 지정된 [Point](./) 객체의 X 및 Y 좌표 값에서 지정된 [Size](../size/) 객체의 너비와 높이 값을 각각 빼서 반환합니다. |
| [String](../../system/string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 X 및 Y 좌표 쌍의 문자열 표현을 반환합니다. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | 지정된 [PointF](../pointf/) 객체의 [PointF](../pointf/) 객체의 X 및 Y 좌표 값을 다음 낮은 정수값으로 잘라서 [Point](./) 객체를 생성합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [Empty](./empty/) | [Point](./) 클래스의 X 및 Y 좌표 값이 0인 빈 인스턴스입니다. |

## 참고

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)