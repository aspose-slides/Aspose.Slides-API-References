---
title: ToSByte()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 부울 값을 동등한 8비트 부호 있는 정수로 변환합니다.
type: docs
weight: 105
url: /ko/system/convert/tosbyte/
---
## Convert::ToSByte(bool) 메서드

지정된 부울 값을 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) 메서드

지정된 8비트 부호 없는 정수를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) 메서드

지정된 8비트 부호 있는 정수를 반환합니다.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) 메서드

지정된 16비트 부호 없는 정수를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) 메서드

지정된 16비트 부호 있는 정수를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) 메서드

지정된 32비트 부호 없는 정수를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) 메서드

지정된 32비트 부호 있는 정수를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) 메서드

지정된 64비트 부호 없는 정수를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) 메서드

지정된 64비트 부호 있는 정수를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) 메서드

지정된 부동 소수점(float) 숫자를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) 메서드

지정된 double 숫자를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) 메서드

지정된 decimal 숫자를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) 메서드

지정된 유니코드 문자(char_t)를 동등한 8비트 부호 있는 정수로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### 반환 값

0.

## Convert::ToSByte(const char_t *) 메서드

지정된 숫자 문자열 표현을 포함하는 c-string을 동등한 8비트 정수 값으로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 c-string |

### 반환 값

지정된 c-string이 나타내는 숫자와 동일한 8비트 정수 값

## Convert::ToSByte(const String\&) 메서드

지정된 숫자 문자열 표현을 포함하는 문자열을 동등한 8비트 정수 값으로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 8비트 정수 값

## Convert::ToSByte(const String\&, int) 메서드

지정된 진수에서 숫자 문자열 표현을 포함하는 문자열을 동등한 8비트 정수 값으로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| from_base | int | 문자열이 나타내는 숫자의 진수 |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 8비트 정수 값

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 숫자 문자열 표현을 포함하는 문자열을 제공된 서식 정보를 사용하여 동등한 부호 없는 8비트 정수 값으로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 8비트 정수 값

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) 메서드

```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 숫자 문자열 표현을 포함하는 문자열을 제공된 서식 정보와 숫자 스타일을 사용하여 동등한 8비트 정수 값으로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트 단위 결합 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

지정된 문자열이 나타내는 숫자와 동일한 부호 없는 8비트 정수 값

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) 메서드

```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 박싱된 값을 동등한 8비트 정수 값으로 변환합니다.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱하는 객체에 대한 공유 포인터 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 유형이 [String](../../string/)인 경우 사용될 문자열 형식 |

### 반환 값

지정된 박싱된 값과 동등한 8비트 정수 값

## See Also

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