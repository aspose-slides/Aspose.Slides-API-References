---
title: ToInt32()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 부울 값을 동등한 32비트 부호 있는 정수로 변환합니다.
type: docs
weight: 157
url: /ko/system/convert/toint32/
---
## Convert::ToInt32(bool) 메서드

지정된 부울 값을 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) 메서드

지정된 8비트 부호 없는 정수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) 메서드

지정된 8비트 부호 있는 정수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) 메서드

지정된 16비트 부호 없는 정수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) 메서드

지정된 16비트 부호 있는 정수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) 메서드

지정된 32비트 부호 없는 정수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) 메서드

지정된 32비트 부호 있는 정수를 반환합니다.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) 메서드

지정된 64비트 부호 없는 정수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) 메서드

지정된 64비트 부호 있는 정수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) 메서드

지정된 부동 소수점 수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) 메서드

지정된 배정밀도 부동 소수점 수를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) 메서드

지정된 십진수 값을 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) 메서드

지정된 유니코드 문자를 동등한 32비트 부호 있는 정수로 변환합니다.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) 메서드

지정된 null 문자열을 동등한 32비트 정수값으로 변환합니다.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### 반환 값

0.

## Convert::ToInt32(const char_t *) 메서드

숫자의 문자열 표현을 포함하는 지정된 C 문자열을 동등한 32비트 정수값으로 변환합니다.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 C 문자열 |

### 반환 값

지정된 C 문자열이 나타내는 숫자와 같은 32비트 정수값

## Convert::ToInt32(const String\&) 메서드

숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 32비트 정수값으로 변환합니다.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 32비트 정수값

## Convert::ToInt32(const String\&, int) 메서드

지정된 진법의 숫자 문자열 표현을 포함하는 지정된 문자열을 동등한 32비트 정수값으로 변환합니다.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| from_base | int | 문자열이 나타내는 숫자의 진법 |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 32비트 정수값

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보를 사용하여 숫자 문자열 표현을 포함하는 지정된 문자열을 동등한 32비트 정수값으로 변환합니다.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 32비트 정수값

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) 메서드




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보와 숫자 스타일을 사용하여 숫자 문자열 표현을 포함하는 지정된 문자열을 동등한 32비트 정수값으로 변환합니다.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 열거형 값들의 비트 OR 조합으로, 문자열 표현에 허용되는 스타일을 지정 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

지정된 문자열이 나타내는 숫자와 같은 32비트 정수값

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드 




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드 




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) 메서드 




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 박싱된 값을 동등한 32비트 정수값으로 변환합니다.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱하는 객체에 대한 shared_ptr |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 타입이 [String](../../string/)인 경우 사용할 문자열 서식 |

### 반환 값

지정된 박싱된 값과 동등한 32비트 정수값

## 참고

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [Decimal](../../decimal/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 클래스 [Object](../../object/)
* 구조체 [Convert](../)
* 구조체 [Enum](../../enum/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)