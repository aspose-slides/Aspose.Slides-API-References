---
title: ToByte()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 부울 값을 동등한 8비트 부호 없는 정수로 변환합니다.
type: docs
weight: 92
url: /ko/system/convert/tobyte/
---
## Convert::ToByte(bool) 메서드

지정된 부울 값을 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) 메서드

지정된 8비트 부호 없는 정수를 반환합니다.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) 메서드

지정된 8비트 부호 있는 정수를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) 메서드

지정된 16비트 부호 없는 정수를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) 메서드

지정된 16비트 부호 있는 정수를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) 메서드

지정된 32비트 부호 없는 정수를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) 메서드

지정된 32비트 부호 있는 정수를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) 메서드

지정된 64비트 부호 없는 정수를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) 메서드

지정된 64비트 부호 있는 정수를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) 메서드

지정된 부동 소수점 숫자를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) 메서드

지정된 배정밀도 부동 소수점 숫자를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) 메서드

지정된 십진수를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) 메서드

지정된 유니코드 문자를 동등한 8비트 부호 없는 정수로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) 메서드

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) 메서드

지정된 널 문자열을 동등한 부호 없는 8비트 정수값으로 변환합니다.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### 반환 값

0.

## Convert::ToByte(const char_t *) 메서드

숫자의 문자열 표현을 포함하는 지정된 c-문자열을 동등한 부호 없는 8비트 정수값으로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 c-문자열 |

### 반환 값

지정된 c-문자열에 의해 표현된 숫자와 동일한 부호 없는 8비트 정수값

## Convert::ToByte(const String\&) 메서드

숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 8비트 정수값으로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### 반환 값

지정된 문자열에 의해 표현된 숫자와 동일한 부호 없는 8비트 정수값

## Convert::ToByte(const String\&, int) 메서드

지정된 진법으로 표현된 숫자의 문자열을 동등한 부호 없는 8비트 정수값으로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| from_base | int | 문자열에 의해 표현된 숫자의 진법 |

### 반환 값

지정된 문자열에 의해 표현된 숫자와 동일한 부호 없는 8비트 정수값

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보를 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 8비트 정수값으로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

지정된 문자열에 의해 표현된 숫자와 동일한 부호 없는 8비트 정수값

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) 메서드

```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) 메서드

제공된 서식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 8비트 정수값으로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트별 조합 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터 |

### 반환 값

지정된 문자열에 의해 표현된 숫자와 동일한 부호 없는 8비트 정수값

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) 메서드

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) 메서드

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) 메서드

```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 박싱된 값을 동등한 부호 없는 8비트 정수값으로 변환합니다.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱하는 객체에 대한 공유 포인터 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 형식이 [String](../../string/)인 경우 사용될 문자열 서식 |

### 반환 값

지정된 박싱된 값에 해당하는 부호 없는 8비트 정수값

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
* 구조체 [Enum](../../enum/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)