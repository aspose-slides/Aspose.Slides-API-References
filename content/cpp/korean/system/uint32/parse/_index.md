---
title: Parse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열(숫자의 문자열 표현을 포함함)을 32비트 부호 없는 정수로 변환합니다.
type: docs
weight: 1
url: /ko/system/uint32/parse/
---
## UInt32::Parse(const String\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함함)을 32비트 부호 없는 정수로 변환합니다.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |

### 반환값

지정된 문자열이 나타내는 숫자와 동일한 32비트 부호 없는 정수입니다.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 형식 정보를 사용하여 지정된 문자열(숫자의 문자열 표현)을 32비트 부호 없는 정수로 변환합니다.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터입니다. |

### 반환값

지정된 문자열이 나타내는 숫자와 동일한 32비트 부호 없는 정수입니다.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) 메서드




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 형식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현)을 32비트 부호 없는 정수로 변환합니다.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 열거형 값들의 비트 조합으로, 숫자 문자열 표현에 허용되는 스타일을 지정합니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터입니다. |

### 반환값

지정된 문자열이 나타내는 숫자와 동일한 32비트 부호 없는 정수입니다.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 참고

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)