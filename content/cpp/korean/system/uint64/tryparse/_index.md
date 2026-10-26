---
title: TryParse()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열(숫자의 문자열 표현을 포함함)을 64비트 부호 없는 정수와 동등한 값으로 변환합니다.
type: docs
weight: 14
url: /ko/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함함)을 64비트 부호 없는 정수와 동등한 값으로 변환합니다.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| result | **uint64_t**\& | 변환 결과가 저장되는 64비트 부호 없는 정수 변수에 대한 참조입니다. |

### 반환 값

변환이 성공하면 true, 그렇지 않으면 false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) 메서드

제공된 서식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 64비트 부호 없는 정수와 동등한 값으로 변환합니다.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자의 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트wise 조합입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터입니다. |
| result | **uint64_t**\& | 변환 결과가 저장되는 64비트 부호 없는 정수 변수에 대한 참조입니다. |

### 반환 값

변환이 성공하면 true, 그렇지 않으면 false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) 메서드




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) 메서드




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) 메서드




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## 참조

* 열거형 [NumberStyles](../../../system.globalization/numberstyles/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 구조체 [UInt64](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)