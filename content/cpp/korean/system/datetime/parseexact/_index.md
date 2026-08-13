---
title: ParseExact()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열 표현을 지정된 형식 및 문화별 형식 정보를 사용하여 동등한 DateTime 객체로 변환합니다. 문자열 표현의 형식은 지정된 형식과 정확히 일치해야 합니다. 변환이 실패하면 예외가 발생합니다.
type: docs
weight: 872
url: /ko/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 메서드

지정된 날짜 및 시간 값의 문자열 표현을 지정된 형식 및 문화별 형식 정보를 사용하여 동등한 [DateTime](../) 객체로 변환합니다. 문자열 표현의 형식은 지정된 형식과 정확히 일치해야 합니다. 변환에 실패하면 예외가 발생합니다.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 날짜 및 시간 값의 문자열 표현. |
| format | const [String](../../string/)\& | 문자열 형식. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 형식 정보를 제공하는 [IFormatProvider](../../iformatprovider/) 객체. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s**에 대한 추가 정보, **s**에 존재할 수 있는 스타일 요소, 또는 **s**를 [DateTime](../) 객체로 변환하는 과정에 대한 추가 정보를 제공하는 열거형 값들의 비트 연산 조합. |

### 반환 값

지정된 문자열이 나타내는 날짜 및 시간 값과 동일한 [DateTime](../) 클래스의 새 인스턴스입니다.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) 메서드

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) 메서드

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) 메서드

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 메서드

지정된 날짜 및 시간 값의 문자열 표현을 지정된 형식들, 문화별 형식 정보 및 스타일을 사용하여 동등한 [DateTime](../) 객체로 변환합니다. 문자열 표현의 형식은 지정된 형식 중 하나와 정확히 일치해야 합니다. 변환에 실패하면 예외가 발생합니다.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 날짜 및 시간 값의 문자열 표현. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 문자열 형식들의 배열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 형식 정보를 제공하는 [IFormatProvider](../../iformatprovider/) 객체. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s**에 대한 추가 정보, **s**에 존재할 수 있는 스타일 요소, 또는 **s**를 [DateTime](../) 객체로 변환하는 과정에 대한 추가 정보를 제공하는 열거형 값들의 비트 연산 조합. |

### 반환 값

지정된 문자열이 나타내는 날짜 및 시간 값과 동일한 [DateTime](../) 클래스의 새 인스턴스입니다.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) 메서드

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) 메서드

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) 메서드

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## 참고

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)