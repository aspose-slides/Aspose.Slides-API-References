---
title: ToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 개체가 나타내는 날짜 및 시간 값의 문자열 표현을 현재 문화에서 정의된 서식 규칙을 사용하여 반환합니다.
type: docs
weight: 482
url: /ko/system/datetime/tostring/
---
## DateTime::ToString() const 메서드

현재 개체가 나타내는 날짜 및 시간 값의 문자열 표현을 현재 문화에서 정의된 서식 규칙을 사용하여 반환합니다.

```cpp
String System::DateTime::ToString() const
```

### 반환 값

현재 개체가 나타내는 값의 문자열 표현

## DateTime::ToString(const String\&) const 메서드

지정된 형식과 현재 문화에서 정의된 서식 규칙을 사용하여 현재 개체가 나타내는 날짜 및 시간 값의 문자열 표현을 반환합니다.

```cpp
String System::DateTime::ToString(const String &format) const
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 형식 문자열 |

### 반환 값

형식 **format** 및 현재 문화에 따라 정의된 서식에 따라 서식된 현재 개체가 나타내는 값의 문자열 표현

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const 메서드

지정된 형식 정보를 사용하여 현재 개체가 나타내는 날짜 및 시간 값의 문자열 표현을 반환합니다.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 정보를 나타내는 객체 |

### 반환 값

형식 제공자 **formatProvider**가 제공한 형식 정보에 따라 서식된 현재 개체가 나타내는 값의 문자열 표현

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const 메서드




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const 메서드




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const 메서드




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 메서드

지정된 형식 정보를 사용하여 현재 개체가 나타내는 날짜 및 시간 값의 문자열 표현을 반환합니다.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 형식 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 정보를 나타내는 객체 |

### 반환 값

제공자 **provider**가 제공한 형식 정보와 형식 문자열 **format**에 따라 서식된 현재 개체가 나타내는 값의 문자열 표현

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 메서드




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const 메서드




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const 메서드




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [DateTime](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)