---
title: ToChar()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 변환은 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.
type: docs
weight: 118
url: /ko/system/convert/tochar/
---
## Convert::ToChar(bool) 메서드

변환은 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) 메서드

지정된 8비트 부호 없는 정수를 동등한 유니코드 문자로 변환합니다.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) 메서드

지정된 8비트 부호 있는 정수를 동등한 유니코드 문자로 변환합니다.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) 메서드

지정된 16비트 부호 없는 정수를 동등한 유니코드 문자로 변환합니다.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) 메서드

지정된 16비트 부호 있는 정수를 동등한 유니코드 문자로 변환합니다.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) 메서드

지정된 32비트 부호 없는 정수를 동등한 유니코드 문자로 변환합니다.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) 메서드

지정된 32비트 부호 있는 정수를 동등한 유니코드 문자로 변환합니다.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) 메서드

지정된 64비트 부호 없는 정수를 동등한 유니코드 문자로 변환합니다.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) 메서드

지정된 64비트 부호 있는 정수를 동등한 유니코드 문자로 변환합니다.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) 메서드

변환은 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) 메서드

변환은 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) 메서드

변환은 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) 메서드

지정된 유니코드 문자를 반환합니다.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) 메서드

변환은 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) 메서드

지정된 c-문자열의 첫 번째이자 유일한 문자를 char_t 값으로 변환합니다.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 c-문자열; c-문자열은 정확히 1 문자 길이여야 합니다. |

### 반환 값

지정된 c-문자열이 정확히 1 문자인 경우 첫 번째이자 유일한 문자를 반환하고, 그렇지 않으면 0을 반환합니다.

## Convert::ToChar(const String\&) 메서드

지정된 문자열의 첫 번째이자 유일한 문자를 char_t 값으로 변환합니다.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열; 문자열은 정확히 1 문자 길이여야 합니다. |

### 반환 값

지정된 문자열이 정확히 1 문자인 경우 첫 번째이자 유일한 문자를 반환하고, 그렇지 않으면 0을 반환합니다.

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 문자열의 첫 번째이자 유일한 문자를 char_t 값으로 변환합니다.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열; 문자열은 정확히 1 문자 길이여야 합니다. |

### 반환 값

지정된 문자열이 정확히 1 문자인 경우 첫 번째이자 유일한 문자를 반환하고, 그렇지 않으면 0을 반환합니다.

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 메서드

지정된 박싱된 값을 동등한 유니코드 문자로 변환합니다.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 박싱하는 객체에 대한 공유 포인터 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 유형이 [String](../../string/)인 경우 사용할 문자열 형식 |

### 반환 값

지정된 박싱된 값에 해당하는 유니코드 문자

## 참고

* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [Decimal](../../decimal/)
* 클래스 [DateTime](../../datetime/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [Object](../../object/)
* 구조체 [Convert](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)