---
title: SizeF
second_title: Aspose.Slides C++용 API 레퍼런스
description: "이미지의 너비와 높이를 나타내는 단정밀도 부동소수점 값 쌍을 나타냅니다. 이 타입은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. 절대 System::SmartPtr 클래스를 사용해 이 타입의 객체를 관리하지 마십시오."
type: docs
weight: 287
url: /ko/system.drawing/sizef/
---
## SizeF 클래스

이미지의 너비와 높이를 나타내는 단정도 부동소수점 값 쌍을 표현합니다. 이 타입은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. [System::SmartPtr](../../system/smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마십시오.

```cpp
class SizeF
```

## 메서드

| Method | Description |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | 지정된 [SizeF](./) 객체들의 합계인 새 [SizeF](./) 객체를 반환합니다. 즉, 그 너비 값은 지정된 객체들의 너비 값들의 합과 같으며 높이 값은 지정된 객체들의 높이 값들의 합과 같습니다. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | 현재 객체와 지정된 객체가 동일한지 판단합니다. 즉, 동일한 너비와 높이 값 쌍을 나타냅니다. |
| **float** [get_Height](./get_height/)() const | 현재 객체가 나타내는 높이 값을 반환합니다. |
| **bool** [get_IsEmpty](./get_isempty/)() const | 너비와 높이 값이 모두 0인지 판단합니다. |
| **float** [get_Width](./get_width/)() const | 현재 객체가 나타내는 너비 값을 반환합니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
|  [operator PointF](./operator_pointf/)() const | 현재 객체를 [Point](../point/) 객체 인스턴스로 변환합니다. 이때 X와 Y 좌표를 현재 객체의 너비와 높이 값으로 각각 초기화합니다. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | 지정된 [SizeF](./) 객체의 너비와 높이 값을 현재 [SizeF](./) 객체의 너비와 높이 값에 각각 더합니다. |
| void [set_Height](./set_height/)(**float**) | 현재 객체가 나타내는 높이 값을 설정합니다. |
| void [set_Width](./set_width/)(**float**) | 현재 객체가 나타내는 너비 값을 설정합니다. |
|  [SizeF](./sizef/)() | 새 [SizeF](./) 객체를 생성하고 그 너비와 높이 값을 0으로 초기화합니다. |
|  [SizeF](./sizef/)(const [PointF](../pointf/)\&) | 새 [SizeF](./) 객체를 생성하고, 지정된 점의 X와 Y 좌표 값을 각각 너비와 높이 값으로 초기화합니다. |
|  [SizeF](./sizef/)(**float**, **float**) | 새 [SizeF](./) 객체를 생성하고 지정된 값으로 초기화합니다. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | 새 [SizeF](./) 객체를 반환합니다. 이는 **size1**에서 **size2**를 뺀 결과이며, 그 너비 값은 **size1**의 너비 값에서 **size2**의 너비 값을 뺀 결과이고 높이 값은 **size1**의 높이 값에서 **size2**의 높이 값을 뺀 결과입니다. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | 현재 객체를 [Point](../point/) 객체 인스턴스로 변환합니다. X와 Y 좌표를 현재 객체의 너비와 높이 값으로 각각 초기화합니다. |
| [Size](../size/) [ToSize](./tosize/)() const | 현재 [SizeF](./) 객체를 기반으로 [Size](../size/) 객체를 생성합니다. 이때 [SizeF](./) 객체의 너비와 높이 값을 다음 낮은 정수값으로 내림합니다. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 너비와 높이 값 쌍의 문자열 표현을 반환합니다. |

## 필드

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | 너비와 높이 값이 0인 [SizeF](./) 클래스의 빈 인스턴스. |

## 참고

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)