---
title: TryParse()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 숫자의 문자열 표현을 포함하는 문자열을 동등한 32비트 부호 있는 정수로 변환합니다.
type: docs
weight: 14
url: /ko/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) 메서드

지정된 문자열(숫자의 문자열 표현을 포함)을 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| result | **int32_t**\& | 변환 결과가 저장되는 32비트 부호 있는 정수 변수에 대한 참조. |

### 반환값

변환이 성공하면 True, 그렇지 않으면 false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) 메서드

제공된 형식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현을 포함)을 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 열거형 값들의 비트 단위 조합으로, 숫자 문자열 표현의 허용되는 스타일을 지정합니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터. |
| result | **int32_t**\& | 변환 결과가 저장되는 32비트 부호 있는 정수 변수에 대한 참조. |

### 반환값

변환이 성공하면 True, 그렇지 않으면 false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) 메서드

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) 메서드

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) 메서드

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## 참조

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [Int32](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)