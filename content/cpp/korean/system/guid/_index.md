---
title: Guid
second_title: Aspose.Slides for C++ API 레퍼런스
description: "전역 고유 식별자를 나타냅니다. 이 유형은 스택에 할당하고 값을 전달하거나 참조로 함수를 호출해야 합니다. 이 유형의 객체를 관리하려면 System::SmartPtr 클래스를 절대 사용하지 마세요."
type: docs
weight: 885
url: /ko/system/guid/
---
## Guid 클래스

Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Guid
```

## 메서드

| Method | Description |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | 현재 객체와 지정된 객체가 나타내는 GUID를 산술적으로 비교합니다. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | 현재 객체와 지정된 객체가 나타내는 GUID가 동일한지 판단합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
| [Guid](./guid/)() | 모두 0인 GUID를 나타내는 객체를 생성합니다. |
| [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 부호 없는 8비트 정수 배열로 지정된 GUID를 나타내는 객체를 생성합니다. |
| [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 부호 없는 8비트 정수 값의 배열 뷰로 지정된 GUID를 나타내는 객체를 생성합니다. |
| [Guid](./guid/)(const [String](../string/)\&) | 문자열로 지정된 GUID를 나타내는 객체를 생성합니다. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Guid](./) 클래스의 인스턴스를 지정된 GUID 구성 요소로부터 생성합니다. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | [Guid](./) 클래스의 인스턴스를 지정된 GUID 구성 요소로부터 생성합니다. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | [Guid](./) 클래스의 인스턴스를 지정된 부호 없는 정수와 바이트로부터 생성합니다. |
| [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | [Guid](./) 클래스의 인스턴스를 지정된 부호 없는 정수와 바이트로부터 생성합니다. |
| [Guid](./guid/)(const [Guid](./)\&) | 지정된 객체와 동일한 GUID를 나타내는 객체를 생성합니다. |
| static [Guid](./) [NewGuid](./newguid/)() | 새 GUID를 생성하고 이를 나타내는 [Guid](./) 객체를 반환합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | 현재 객체와 지정된 객체가 나타내는 GUID가 동일하지 않은지 판단합니다. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | 현재 객체에 지정된 [Guid](./) 객체가 나타내는 GUID 값을 할당합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | 현재 객체와 지정된 객체가 나타내는 GUID가 동일한지 판단합니다. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | 지정된 GUID 문자열 표현을 동등한 [Guid](./) 객체로 변환합니다. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | 현재 객체가 나타내는 GUID를 바이트 배열로 변환합니다. |
| [String](../string/) [ToString](./tostring/)() const | 현재 객체가 나타내는 GUID를 문자열 표현으로 변환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 지정된 문자열 형식을 사용하여 현재 객체가 나타내는 GUID를 문자열 표현으로 변환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 지정된 문자열 형식과 Culture를 사용하여 현재 객체가 나타내는 GUID를 문자열 표현으로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | 지정된 문자열을 [Guid](./) 객체로 변환을 시도합니다. |
| [~Guid](./~guid/)() | 소멸자. |

## 필드

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | 값이 0인 GUID를 나타냅니다. |

## 관련 항목

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)