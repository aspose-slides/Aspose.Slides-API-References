---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 숫자의 문자열 표현을 포함하는 지정된 문자열을 동일한 16비트 부호 없는 정수로 변환합니다.
type: docs
weight: 14
url: /ko/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함함)을 16비트 부호 없는 정수와 동일한 값으로 변환합니다.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| result | **uint16_t**\& | 변환 결과가 저장되는 16비트 부호 없는 정수 변수에 대한 참조. |

### 반환 값

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함함)을 제공된 서식 정보와 숫자 스타일을 사용하여 16비트 부호 없는 정수와 동일한 값으로 변환합니다.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자의 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트별 조합. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터. |
| result | **uint16_t**\& | 변환 결과가 저장되는 16비트 부호 없는 정수 변수에 대한 참조. |

### 반환 값

True if the conversion succeeded, otherwise - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) 메서드

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) 메서드

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) 메서드

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## 참조

* 열거형 [NumberStyles](../../../system.globalization/numberstyles/)
* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 구조체 [UInt16](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)