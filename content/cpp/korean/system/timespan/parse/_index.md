---
title: Parse()
second_title: Aspose.Slides for C++ API 참조
description: 문자열을 동등한 TimeSpan 개체로 변환합니다.
type: docs
weight: 534
url: /ko/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) 메서드

문자열을 동등한 [TimeSpan](../) 개체로 변환합니다.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 입력 문자열. |

### Return Value

문자열에 해당하는 시간 간격.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 형식 제공자를 사용하여 문자열을 동등한 [TimeSpan](../) 개체로 변환합니다.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 입력 문자열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 서식 정보를 제공하는 형식 제공자. |

### Return Value

문자열에 해당하는 시간 간격.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) 메서드




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) 메서드




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [TimeSpan](../)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)