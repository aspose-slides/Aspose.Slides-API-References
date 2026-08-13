---
title: ToUInt64()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 부울 값을 동등한 64비트 부호 없는 정수로 변환합니다.
type: docs
weight: 196
url: /ko/system/convert/touint64/
---
## Convert::ToUInt64(bool) 메서드

지정된 부울 값을 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```
## Convert::ToUInt64(uint8_t) 메서드

지정된 8비트 부호 없는 정수를 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```
## Convert::ToUInt64(int8_t) 메서드

지정된 8비트 부호 있는 정수를 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```
## Convert::ToUInt64(uint16_t) 메서드

지정된 16비트 부호 없는 정수를 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```
## Convert::ToUInt64(int16_t) 메서드

지정된 16비트 부호 있는 정수를 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```
## Convert::ToUInt64(uint32_t) 메서드

지정된 32비트 부호 없는 정수를 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```
## Convert::ToUInt64(int32_t) 메서드

지정된 32비트 부호 있는 정수를 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```
## Convert::ToUInt64(uint64_t) 메서드

지정된 64비트 부호 없는 정수를 반환합니다.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```
## Convert::ToUInt64(int64_t) 메서드

지정된 64비트 부호 있는 정수를 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```
## Convert::ToUInt64(float) 메서드

지정된 float 값을 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```
## Convert::ToUInt64(double) 메서드

지정된 double 값을 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```
## Convert::ToUInt64(const Decimal\&) 메서드

지정된 Decimal 값을 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```
## Convert::ToUInt64(char_t) 메서드

지정된 유니코드 문자를 동등한 64비트 부호 없는 정수로 변환합니다.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```
## Convert::ToUInt64(DateTime) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```
## Convert::ToUInt64(std::nullptr_t) 메서드

지정된 null 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```

### Return Value

0.

## Convert::ToUInt64(const char_t *) 메서드

숫자의 문자열 표현을 포함하는 지정된 c-스트링을 동등한 부호 없는 64비트 정수 값으로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 c-스트링 |

### Return Value

지정된 c-스트링이 나타내는 숫자와 동일한 부호 없는 64비트 정수 값

## Convert::ToUInt64(const String\&) 메서드

숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### Return Value

지정된 문자열이 나타내는 숫자와 동일한 부호 없는 64비트 정수 값

## Convert::ToUInt64(const String\&, int) 메서드

숫자의 문자열 표현을 지정된 진법으로 포함하는 지정된 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| from_base | int | 문자열이 나타내는 숫자의 진법 |

### Return Value

지정된 문자열이 나타내는 숫자와 동일한 부호 없는 64비트 정수 값

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보를 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터 |

### Return Value

지정된 문자열이 나타내는 숫자와 동일한 부호 없는 64비트 정수 값

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) 메서드




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자의 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트 조합 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터 |

### Return Value

지정된 문자열이 나타내는 숫자와 동일한 부호 없는 64비트 정수 값

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) 메서드




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 박싱된 값을 동등한 부호 없는 64비트 정수 값으로 변환합니다.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱하는 객체에 대한 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 타입이 [String](../../string/)인 경우 사용할 문자열 형식 |

### Return Value

지정된 박싱된 값과 동일한 부호 없는 64비트 정수 값

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