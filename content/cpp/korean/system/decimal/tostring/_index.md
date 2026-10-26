---
title: ToString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 객체가 나타내는 값의 문자열 표현을 반환합니다.
type: docs
weight: 352
url: /ko/system/decimal/tostring/
---
## Decimal::ToString() const 메서드

객체가 나타내는 값의 문자열 표현을 반환합니다.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const 메서드

문화별 형식 정보를 사용하여 현재 객체를 문자열로 변환합니다.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 형식 정보를 제공하는 [IFormatProvider](../../iformatprovider/) 객체. |

### 반환값

현재 객체의 문자열 표현.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const 메서드




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const 메서드




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const 메서드




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const 메서드

지정된 문자열 형식과 지정된 [IFormatProvider](../../iformatprovider/) 객체가 제공하는 문화별 형식 정보를 사용하여 현재 객체를 문자열 표현으로 변환합니다.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 문자열 형식. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 형식 정보를 제공하는 [IFormatProvider](../../iformatprovider/) 객체. |

### 반환값

현재 객체의 문자열 표현.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const 메서드




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const 메서드




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const 메서드




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## 참고

* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [Decimal](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)