---
title: PointF
second_title: Aspose.Slides for C++ API 참조
description: "2차원 평면상의 점에 대한 단정밀도 부동소수점 X 및 Y 좌표 쌍을 나타냅니다. 이 유형은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. 이 유형의 객체를 관리하기 위해 System::SmartPtr 클래스를 절대 사용하지 마십시오."
type: docs
weight: 222
url: /ko/system.drawing/pointf/
---
## PointF 클래스

2차원 평면상의 점에 대한 단정밀도 부동 소수점 X 및 Y 좌표 쌍을 나타냅니다. 이 유형은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. 이 유형의 객체를 관리하기 위해 [System::SmartPtr](../../system/smartptr/) 클래스를 절대 사용하지 마십시오.

```cpp
class PointF
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | 지정된 [SizeF](../sizef/) 객체의 너비 및 높이 값을 지정된 [PointF](./) 객체의 X 및 Y 좌표 값에 각각 추가합니다. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | 지정된 [Size](../size/) 객체의 너비 및 높이 값을 지정된 [PointF](./) 객체의 X 및 Y 좌표 값에 각각 추가합니다. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | 현재 객체와 지정된 객체가 동일한지, 즉 같은 X 및 Y 좌표 쌍을 나타내는지 확인합니다. |
| **bool** [get_IsEmpty](./get_isempty/)() const | X와 Y 좌표 값이 모두 0인지 확인합니다. |
| **float** [get_X](./get_x/)() const | 현재 객체가 나타내는 X 좌표 값을 반환합니다. |
| **float** [get_Y](./get_y/)() const | 현재 객체가 나타내는 Y 좌표 값을 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
| **bool** [IsNull](./isnull/)() const | 항상 false를 반환합니다. |
| explicit  [operator bool](./operator_bool/)() | 항상 true를 반환합니다. |
|  [PointF](./pointf/)() | 새로운 [PointF](./) 객체를 생성하고 X와 Y 좌표 값을 0으로 초기화합니다. |
|  [PointF](./pointf/)(**float**, **float**) | 지정된 값으로 새로운 [PointF](./) 객체를 생성하고 초기화합니다. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | 새로운 [PointF](./) 객체를 생성하고 지정된 [SizeF](../sizef/) 객체의 너비와 높이 값을 각각 X 및 Y 좌표 값으로 초기화합니다. |
| void [set_X](./set_x/)(**float**) | 현재 객체가 나타내는 X 좌표 값을 설정합니다. |
| void [set_Y](./set_y/)(**float**) | 현재 객체가 나타내는 Y 좌표 값을 설정합니다. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | 지정된 [SizeF](../sizef/) 객체의 너비와 높이 값을 지정된 [PointF](./) 객체의 X 및 Y 좌표 값에서 각각 빼습니다. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | 지정된 [Size](../size/) 객체의 너비와 높이 값을 지정된 [PointF](./) 객체의 X 및 Y 좌표 값에서 각각 빼습니다. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 X와 Y 좌표 쌍의 문자열 표현을 반환합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [Empty](./empty/) | [PointF](./) 클래스의 빈 인스턴스로, X와 Y 좌표 값이 0입니다. |

## 참고

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)