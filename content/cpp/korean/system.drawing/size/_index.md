---
title: Size
second_title: Aspose.Slides for C++ API 레퍼런스
description: "이미지의 너비와 높이를 나타내는 정수 값 쌍을 나타냅니다. 이 타입은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마십시오."
type: docs
weight: 274
url: /ko/system.drawing/size/
---
## Size 클래스

이미지의 너비와 높이를 나타내는 정수 값 한 쌍을 나타냅니다. 이 유형은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. [System::SmartPtr](../../system/smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마십시오.

```cpp
class Size
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | 지정된 [Size](./) 객체의 합인 새로운 [Size](./) 객체를 반환합니다. 즉, 해당 객체의 너비 값은 지정된 객체들의 너비 값들의 합과 같고 높이 값은 지정된 객체들의 높이 값들의 합과 같습니다. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | [SizeF](../sizef/) 객체를 지정하고, [SizeF](../sizef/) 객체의 너비와 높이 값을 다음보다 큰 정수 값으로 반올림하여 [Size](./) 객체를 생성합니다. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | 현재 객체와 지정된 객체가 동일한지, 즉 같은 너비와 높이 값을 가진 쌍을 나타내는지 판단합니다. |
| int [get_Height](./get_height/)() const | 현재 객체가 나타내는 높이 값을 반환합니다. |
| **bool** [get_IsEmpty](./get_isempty/)() const | 너비와 높이 값이 모두 0인지 판단합니다. |
| int [get_Width](./get_width/)() const | 현재 객체가 나타내는 너비 값을 반환합니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
|  [operator Point](./operator_point/)() const | [Point](../point/) 객체의 인스턴스를 생성하고, 현재 객체의 너비와 높이 값을 각각 X 및 Y 좌표에 초기화합니다. |
|  [operator SizeF](./operator_sizef/)() const | [SizeF](../sizef/) 객체의 인스턴스를 생성하고, 현재 [Size](./) 객체의 너비와 높이 값으로 초기화합니다. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | 지정된 [SizeF](../sizef/) 객체를 사용하여 [Size](./) 객체를 생성하고, [SizeF](../sizef/) 객체의 너비와 높이 값을 가장 가까운 정수로 반올림합니다. |
| void [set_Height](./set_height/)(int) | 현재 객체가 나타내는 높이 값을 설정합니다. |
| void [set_Width](./set_width/)(int) | 현재 객체가 나타내는 너비 값을 설정합니다. |
|  [Size](./size/)() | 새로운 [Size](./) 객체를 생성하고, 그 너비와 높이 값을 0으로 초기화합니다. |
|  [Size](./size/)(const [Point](../point/)\&) | 새로운 [Size](./) 객체를 생성하고, 지정된 점의 X 및 Y 좌표 값으로 각각 너비와 높이 값을 초기화합니다. |
|  [Size](./size/)(int, int) | 새로운 [Size](./) 객체를 생성하고, 지정된 값으로 초기화합니다. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | 새로운 [Size](./) 객체를 반환합니다. 이 객체는 **size1**에서 **size2**를 뺀 결과이며, 즉 너비 값은 **size1**의 너비에서 **size2**의 너비를 뺀 결과이고, 높이 값은 **size1**의 높이에서 **size2**의 높이를 뺀 결과입니다. |
| [String](../../system/string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 너비와 높이 값 쌍의 문자열 표현을 반환합니다. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | 지정된 [SizeF](../sizef/) 객체를 사용하여 [Size](./) 객체를 생성하고, [SizeF](../sizef/) 객체의 너비와 높이 값을 아래쪽 정수값으로 내림합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [Empty](./empty/) | [Size](./) 클래스의 빈 인스턴스로, 너비와 높이 값이 0입니다. |

## 참고

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)