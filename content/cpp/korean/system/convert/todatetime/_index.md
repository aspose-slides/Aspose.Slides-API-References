---
title: ToDateTime()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.
type: docs
weight: 248
url: /ko/system/convert/todatetime/
---
## Convert::ToDateTime(bool) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) method

지정된 날짜와 시간을 반환합니다.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) method

지정된 문자열을 [DateTime](../../datetime/) 클래스의 인스턴스로 변환합니다.

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### 반환 값

[DateTime](../../datetime/) 클래스의 인스턴스로, 지정된 문자열이 나타내는 날짜 및 시간 정보를 포함합니다.

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) method

제공된 서식 정보를 사용하여 지정된 문자열을 [DateTime](../../datetime/) 클래스의 인스턴스로 변환합니다.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

[DateTime](../../datetime/) 클래스의 인스턴스로, 지정된 문자열이 나타내는 날짜 및 시간 정보를 포함합니다.

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) method




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) method




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

지정된 박싱된 값을 동등한 [DateTime](../../datetime/) 값으로 변환합니다.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱한 객체에 대한 SharedPtr |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 유형이 [String](../../string/)인 경우 사용할 문자열 서식 |

### 반환 값

[DateTime](../../datetime/) 값은 지정된 박싱된 값과 동등합니다.

## 관련 항목

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../../datetime/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)