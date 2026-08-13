---
title: ToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 시간 간격의 문자열 표현을 반환합니다.
type: docs
weight: 261
url: /ko/system/timespan/tostring/
---
## TimeSpan::ToString() const 메서드

현재 객체가 나타내는 시간 간격의 문자열 표현을 반환합니다.

```cpp
String System::TimeSpan::ToString() const
```

## TimeSpan::ToString(const String\&) const 메서드

지정된 형식을 사용하여 현재 객체의 값을 동등한 문자열 표현으로 변환합니다.

```cpp
String System::TimeSpan::ToString(const String &format) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 메서드

지정된 형식 및 형식 공급자를 사용하여 현재 객체의 값을 동등한 문자열 표현으로 변환합니다.

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 메서드




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const 메서드




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## TimeSpan::ToString(const String\&, std::nullptr_t) const 메서드




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```

## 참조

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [TimeSpan](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)