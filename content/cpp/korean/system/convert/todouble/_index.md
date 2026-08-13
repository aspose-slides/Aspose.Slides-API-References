---
title: ToDouble()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 부울 값을 동등한 배정밀도 부동소수점 숫자로 변환합니다.
type: docs
weight: 222
url: /ko/system/convert/todouble/
---
## Convert::ToDouble(bool) 메서드

지정된 부울 값을 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) 메서드

지정된 8비트 부호 없는 정수를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) 메서드

지정된 8비트 부호 있는 정수를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) 메서드

지정된 16비트 부호 없는 정수를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) 메서드

지정된 16비트 부호 있는 정수를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) 메서드

지정된 32비트 부호 없는 정수를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) 메서드

지정된 32비트 부호 있는 정수를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) 메서드

지정된 64비트 부호 없는 정수를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) 메서드

지정된 64비트 부호 있는 정수를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) 메서드

지정된 단정밀도 부동소수점 숫자를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) 메서드

지정된 double 값을 반환합니다.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) 메서드

지정된 decimal 숫자를 동등한 배정밀도 부동소수점 숫자로 변환합니다.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) 메서드

지정된 null 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### 반환값

0.

## Convert::ToDouble(const char_t *) 메서드

지정된 숫자 문자열 표현을 포함하는 c 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 c 문자열 |

### 반환값

지정된 c 문자열에 의해 표현된 숫자와 동일한 배정밀도 부동소수점 값

## Convert::ToDouble(const String\&) 메서드

지정된 숫자 문자열 표현을 포함하는 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### 반환값

지정된 문자열에 의해 표현된 숫자와 동일한 배정밀도 부동소수점 값

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 형식 정보를 사용하여 지정된 숫자 문자열 표현을 포함하는 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터 |

### 반환값

지정된 문자열에 의해 표현된 숫자와 동일한 배정밀도 부동소수점 값

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) 메서드




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 형식 정보와 숫자 스타일을 사용하여 지정된 숫자 문자열 표현을 포함하는 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트별 조합 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 형식 정보를 포함하는 객체에 대한 포인터 |

### 반환값

지정된 문자열에 의해 표현된 숫자와 동일한 배정밀도 부동소수점 값

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 박싱된 값을 배정밀도 부동소수점 값으로 변환합니다. 박싱된 값의 타입이 [String](../../string/)인 경우, 지정된 문자열 형식이 변환 중에 사용됩니다.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱하는 객체에 대한 공유 포인터 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [String](../../string/)인 경우 사용될 문자열 형식 |

### 반환값

지정된 박싱된 값과 동등한 배정밀도 부동소수점 값

## 참조

* 열거형 [NumberStyles](../../../system.globalization/numberstyles/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [Decimal](../../decimal/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 클래스 [Object](../../object/)
* 구조체 [Convert](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)