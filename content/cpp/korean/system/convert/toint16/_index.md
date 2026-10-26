---
title: ToInt16()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 부울 값을 동일한 16비트 부호 있는 정수로 변환합니다.
type: docs
weight: 131
url: /ko/system/convert/toint16/
---
## Convert::ToInt16(bool) method

지정된 부울 값을 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) method

지정된 8비트 부호 없는 정수를 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) method

지정된 8비트 부호 있는 정수를 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) method

지정된 16비트 부호 없는 정수를 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) method

지정된 16비트 부호 있는 정수를 반환합니다.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) method

지정된 32비트 부호 없는 정수를 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) method

지정된 32비트 부호 있는 정수를 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) method

지정된 64비트 부호 없는 정수를 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) method

지정된 64비트 부호 있는 정수를 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) method

지정된 부동 소수점 값을 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) method

지정된 double 값을 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) method

지정된 decimal 값을 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) method

지정된 유니코드 문자를 동일한 16비트 부호 있는 정수로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) method

지정된 널 문자열을 동일한 16비트 정수 값으로 변환합니다.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```

### Return Value

0.

## Convert::ToInt16(const char_t *) method

지정된 c-문자열(숫자 문자열 표현 포함)을 동일한 16비트 정수 값으로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 c-문자열 |

### Return Value

지정된 c-문자열이 나타내는 숫자와 동일한 16비트 정수 값

## Convert::ToInt16(const String\&) method

지정된 문자열(숫자 문자열 표현 포함)을 동일한 16비트 정수 값으로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### Return Value

지정된 문자열이 나타내는 숫자와 동일한 16비트 정수 값

## Convert::ToInt16(const String\&, int) method

지정된 문자열(지정된 진법의 숫자 문자열 표현 포함)을 동일한 16비트 정수 값으로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| from_base | int | 문자열이 나타내는 숫자의 진법 |

### Return Value

지정된 문자열이 나타내는 숫자와 동일한 16비트 정수 값

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) method

제공된 서식 정보를 사용하여 지정된 문자열(숫자 문자열 표현 포함)을 동일한 16비트 정수 값으로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### Return Value

지정된 문자열이 나타내는 숫자와 동일한 16비트 정수 값

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) method

```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자 문자열 표현 포함)을 동일한 16비트 정수 값으로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트 연산 조합 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### Return Value

지정된 문자열이 나타내는 숫자와 동일한 16비트 정수 값

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) method

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) method

```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

지정된 박싱된 값을 동일한 16비트 정수 값으로 변환합니다.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 값을 변환하기 위해 박싱하는 객체에 대한 공유 포인터 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 형식이 [String](../../string/)인 경우 사용할 문자열 형식 |

### Return Value

지정된 박싱된 값과 동일한 16비트 정수 값

## 참조

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)