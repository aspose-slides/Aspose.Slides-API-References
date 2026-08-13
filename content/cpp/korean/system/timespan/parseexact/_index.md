---
title: ParseExact()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 형식, 형식 공급자 및 스타일을 사용하여 문자열을 동등한 TimeSpan 객체로 변환합니다.
type: docs
weight: 547
url: /ko/system/timespan/parseexact/
---
## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

지정된 형식, 형식 공급자 및 스타일을 사용하여 문자열을 동등한 [TimeSpan](../) 객체로 변환합니다.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 입력 문자열입니다. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 포맷 문자열의 [Array](../../array/). |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 서식 정보를 제공하는 형식 공급자. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | 입력 문자열에 존재할 수 있는 요소를 정의합니다. |

### 반환값

문자열에 해당하는 시간 간격입니다.

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) method

지정된 형식, 형식 공급자 및 스타일을 사용하여 문자열을 동등한 [TimeSpan](../) 객체로 변환합니다.

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 입력 문자열입니다. |
| format | const [String](../../string/)\& | 표준 또는 사용자 지정 형식 문자열입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 서식 정보를 제공하는 형식 공급자. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | 입력 문자열에 존재할 수 있는 요소를 정의합니다. |

### 반환값

문자열에 해당하는 시간 간격입니다.

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## TimeSpan::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) method

```cpp
static TimeSpan System::TimeSpan::ParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles=Globalization::TimeSpanStyles::None)
```

## 참조

* 열거형 [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* 타입정의 [ArrayPtr](../../arrayptr/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [TimeSpan](../)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)