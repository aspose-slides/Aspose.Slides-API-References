---
title: Parse()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열이 숫자의 문자열 표현을 포함하는 경우 이를 동일한 16비트 부호 없는 정수로 변환합니다.
type: docs
weight: 1
url: /ko/system/uint16/parse/
---
## UInt16::Parse(const String\&) 메서드

지정된 문자열이 숫자의 문자열 표현을 포함하는 경우 이를 동일한 16비트 부호 없는 정수로 변환합니다.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 16비트 부호 없는 정수.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 문자열이 숫자의 문자열 표현을 포함하는 경우 제공된 서식 정보를 사용하여 이를 동일한 16비트 부호 없는 정수로 변환합니다.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터. |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 16비트 부호 없는 정수.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) 메서드




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열이 숫자의 문자열 표현을 포함하는 경우 이를 동일한 16비트 부호 없는 정수로 변환합니다.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현의 허용된 스타일을 지정하는 NumberStyles 열거형 값들의 비트별 조합. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터. |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 16비트 부호 없는 정수.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 참조

* 열거형 [NumberStyles](../../../system.globalization/numberstyles/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 구조체 [UInt16](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)