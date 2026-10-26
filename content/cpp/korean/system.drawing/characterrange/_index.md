---
title: CharacterRange
second_title: Aspose.Slides for C++ API 레퍼런스
description: "문자열에서 문자 위치 범위를 나타냅니다. 이 유형은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. 절대 System::SmartPtr 클래스를 사용하여 이 유형의 객체를 관리하지 마세요."
type: docs
weight: 40
url: /ko/system.drawing/characterrange/
---
## CharacterRange 클래스

문자열에서 문자 위치의 범위를 나타냅니다. 이 유형은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. 절대 [System::SmartPtr](../../system/smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마세요.

```cpp
class CharacterRange
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | 지정된 범위를 나타내는 [CharacterRange](./) 클래스의 새 인스턴스를 생성합니다. |
|  [CharacterRange](./characterrange/)() | [CharacterRange](./) 클래스의 빈 범위를 나타내는 새 인스턴스를 생성합니다. |
| **int32_t** [get_First](./get_first/)() const | 현재 객체가 나타내는 범위의 첫 번째 문자의 위치를 반환합니다. |
| **int32_t** [get_Length](./get_length/)() const | 현재 객체가 나타내는 범위의 문자 수를 반환합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | 현재 객체와 지정된 객체가 서로 다른 범위를 나타내는지 판단합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | 현재 객체와 지정된 객체가 동일한 범위를 나타내는지 판단합니다. |
| void [set_First](./set_first/)(**int32_t**) | 현재 객체가 나타내는 범위의 첫 번째 문자의 위치를 설정합니다. |
| void [set_Length](./set_length/)(**int32_t**) | 현재 객체가 나타내는 범위의 문자 수를 반환합니다. |

## 참고

* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)