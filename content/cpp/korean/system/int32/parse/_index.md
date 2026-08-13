---
title: Parse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열(숫자의 문자열 표현을 포함)을 32비트 부호 있는 정수와 동등한 값으로 변환합니다.
type: docs
weight: 1
url: /ko/system/int32/parse/
---
## Int32::Parse(const String\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함)을 32비트 부호 있는 정수와 동등한 값으로 변환합니다.

```cpp
static int32_t System::Int32::Parse(const String &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |

### 반환 값

지정된 문자열에 의해 표현된 숫자와 동일한 32비트 부호 있는 정수입니다.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보를 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 32비트 부호 있는 정수와 동등한 값으로 변환합니다.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터입니다. |

### 반환 값

지정된 문자열에 의해 표현된 숫자와 동일한 32비트 부호 있는 정수입니다.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) 메서드




```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 32비트 부호 있는 정수와 동등한 값으로 변환합니다.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트wise 조합입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터입니다. |

### 반환 값

지정된 문자열에 의해 표현된 숫자와 동일한 32비트 부호 있는 정수입니다.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) 메서드




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) 메서드




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## 참고

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [ReadOnlySpan](../../readonlyspan/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)