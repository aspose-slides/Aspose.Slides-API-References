---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열(숫자의 문자열 표현을 포함)을 동일한 16비트 부호 있는 정수로 변환합니다.
type: docs
weight: 14
url: /ko/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함)을 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| result | **int16_t**\& | 변환 결과가 저장되는 16비트 부호 있는 정수 변수에 대한 참조. |

### 반환값

변환이 성공하면 true, 그렇지 않으면 false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함)을 제공된 형식 정보와 숫자 스타일을 사용하여 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 열거형 값들의 비트 결합으로, 숫자 문자열 표현에 허용되는 스타일을 지정합니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터. |
| result | **int16_t**\& | 변환 결과가 저장되는 16비트 부호 있는 정수 변수에 대한 참조. |

### 반환값

변환이 성공하면 true, 그렇지 않으면 false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) 메서드

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) 메서드

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) 메서드

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## 관련 항목

* 열거형 [NumberStyles](../../../system.globalization/numberstyles/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [Int16](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)