---
title: ToInt64()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 부울 값을 동등한 64비트 부호 있는 정수로 변환합니다.
type: docs
weight: 183
url: /ko/system/convert/toint64/
---
## Convert::ToInt64(bool) 메서드

지정된 부울 값을 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```
## Convert::ToInt64(uint8_t) 메서드

지정된 8비트 부호 없는 정수를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```
## Convert::ToInt64(int8_t) 메서드

지정된 8비트 부호 있는 정수를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```
## Convert::ToInt64(uint16_t) 메서드

지정된 16비트 부호 없는 정수를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```
## Convert::ToInt64(int16_t) 메서드

지정된 16비트 부호 있는 정수를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```
## Convert::ToInt64(uint32_t) 메서드

지정된 32비트 부호 없는 정수를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```
## Convert::ToInt64(int32_t) 메서드

지정된 32비트 부호 있는 정수를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```
## Convert::ToInt64(uint64_t) 메서드

지정된 64비트 부호 없는 정수를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```
## Convert::ToInt64(int64_t) 메서드

지정된 64비트 부호 있는 정수를 반환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```
## Convert::ToInt64(float) 메서드

지정된 부동소수점(float) 숫자를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(float value)
```
## Convert::ToInt64(double) 메서드

지정된 배정밀도(double) 숫자를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(double value)
```
## Convert::ToInt64(const Decimal\&) 메서드

지정된 십진수(decimal) 숫자를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```
## Convert::ToInt64(char_t) 메서드

지정된 유니코드 문자를 동등한 64비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```
## Convert::ToInt64(DateTime) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```
## Convert::ToInt64(std::nullptr_t) 메서드

지정된 널 문자열을 동등한 64비트 정수 값으로 변환합니다.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```

### Return Value

0.

## Convert::ToInt64(const char_t *) 메서드

숫자의 문자열 표현을 포함하는 지정된 C 문자열을 동등한 64비트 정수 값으로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 C 문자열 |

### Return Value

지정된 C 문자열이 나타내는 숫자와 같은 64비트 정수 값

## Convert::ToInt64(const String\&) 메서드

숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 64비트 정수 값으로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### Return Value

지정된 문자열이 나타내는 숫자와 같은 64비트 정수 값

## Convert::ToInt64(const String\&, int) 메서드

지정된 진수의 문자열 표현을 포함하는 지정된 문자열을 동등한 64비트 정수 값으로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| from_base | int | 문자열이 나타내는 숫자의 진수 |

### Return Value

지정된 문자열이 나타내는 숫자와 같은 64비트 정수 값

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보를 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 64비트 정수 값으로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### Return Value

지정된 문자열이 나타내는 숫자와 같은 64비트 정수 값

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) 메서드




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 64비트 정수 값으로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자의 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트별 조합 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### Return Value

지정된 문자열이 나타내는 숫자와 같은 64비트 정수 값

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) 메서드




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 박싱된 값을 동등한 64비트 정수 값으로 변환합니다.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱하는 객체에 대한 공유 포인터 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [String](../../string/) 유형의 박싱된 값을 사용할 경우 적용할 문자열 서식 |

### Return Value

지정된 박싱된 값과 동등한 64비트 정수 값

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