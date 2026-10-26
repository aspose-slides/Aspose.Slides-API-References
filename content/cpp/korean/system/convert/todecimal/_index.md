---
title: ToDecimal()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 부울 값을 동등한 십진수로 변환합니다.
type: docs
weight: 235
url: /ko/system/convert/todecimal/
---
## Convert::ToDecimal(bool) 메서드

지정된 부울 값을 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) 메서드

지정된 8비트 부호 없는 정수를 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) 메서드

지정된 8비트 부호 있는 정수를 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) 메서드

지정된 16비트 부호 없는 정수를 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) 메서드

지정된 16비트 부호 있는 정수를 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) 메서드

지정된 32비트 부호 없는 정수를 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) 메서드

지정된 32비트 부호 있는 정수를 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) 메서드

지정된 64비트 부호 없는 정수를 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) 메서드

지정된 64비트 부호 있는 정수를 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) 메서드

지정된 float 값을 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) 메서드

지정된 double 값을 동등한 십진수로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) 메서드

지정된 십진수 값을 반환합니다.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) 메서드

지정된 null 문자열을 동등한 [Decimal](../../decimal/) 값으로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### 반환 값

0.

## Convert::ToDecimal(const char_t *) 메서드

지정된 c 문자열에 포함된 숫자 문자열 표현을 동등한 [Decimal](../../decimal/) 값으로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 c 문자열 |

### 반환 값

지정된 c 문자열이 나타내는 숫자와 같은 [Decimal](../../decimal/) 값

## Convert::ToDecimal(const String\&) 메서드

지정된 문자열에 포함된 숫자 문자열 표현을 동등한 [Decimal](../../decimal/) 값으로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 [Decimal](../../decimal/) 값

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보를 사용하여 지정된 문자열에 포함된 숫자 문자열 표현을 동등한 [Decimal](../../decimal/) 값으로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 [Decimal](../../decimal/) 값

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 숫자 스타일 및 서식 정보를 사용하여 지정된 문자열에 포함된 숫자 문자열 표현을 동등한 [Decimal](../../decimal/) 값으로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트wise 조합 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 [Decimal](../../decimal/) 값

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 박싱된 값을 동등한 [Decimal](../../decimal/) 값으로 변환합니다.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱하고 있는 객체에 대한 SharedPtr |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 형식이 [String](../../string/)인 경우 사용할 문자열 서식 |

### 반환 값

지정된 박싱된 값에 해당하는 [Decimal](../../decimal/) 값

## 참조

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)