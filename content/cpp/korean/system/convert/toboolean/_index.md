---
title: ToBoolean()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 부울 값을 반환합니다.
type: docs
weight: 79
url: /ko/system/convert/toboolean/
---
## Convert::ToBoolean(bool) method

지정된 부울 값을 반환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```
## Convert::ToBoolean(uint8_t) method

지정된 8비트 부호 없는 정수를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```
## Convert::ToBoolean(int8_t) method

지정된 8비트 부호 있는 정수를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```
## Convert::ToBoolean(uint16_t) method

지정된 16비트 부호 없는 정수를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```
## Convert::ToBoolean(int16_t) method

지정된 16비트 부호 있는 정수를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```
## Convert::ToBoolean(uint32_t) method

지정된 32비트 부호 없는 정수를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```
## Convert::ToBoolean(int32_t) method

지정된 32비트 부호 있는 정수를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```
## Convert::ToBoolean(uint64_t) method

지정된 64비트 부호 없는 정수를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```
## Convert::ToBoolean(int64_t) method

지정된 64비트 부호 있는 정수를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```
## Convert::ToBoolean(float) method

지정된 float 숫자를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```
## Convert::ToBoolean(double) method

지정된 double 숫자를 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```
## Convert::ToBoolean(const Decimal\&) method

지정된 decimal 숫자를 동등한 부울 값으로 변환합니다.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```
## Convert::ToBoolean(char_t) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```
## Convert::ToBoolean(DateTime) method

변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```
## Convert::ToBoolean(std::nullptr_t) method

지정된 null 문자열을 동등한 부울 값으로 변환합니다.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### Return Value

False.

## Convert::ToBoolean(const char_t *) method

지정된 c-string을 bool 형식 값으로 변환합니다.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 변환할 c-string |

### 반환값

지정된 c-string이 "True"와 같으면 True를, "False"와 같으면 false를 반환합니다.

## Convert::ToBoolean(const String\&) method

지정된 문자열을 bool 형식 값으로 변환합니다.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### 반환값

지정된 문자열이 "True"와 같으면 True를, "False"와 같으면 false를 반환합니다.

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) method

지정된 문자열을 bool 형식 값으로 변환합니다.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열 |

### 반환값

지정된 문자열이 "True"와 같으면 True를, "False"와 같으면 false를 반환합니다.

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

지정된 박싱된 값을 동등한 부울 값으로 변환합니다.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 변환할 값을 포함하는 객체에 대한 공유 포인터 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 박싱된 값의 타입이 [String](../../string/)인 경우 사용할 문자열 형식 |

### 반환값

지정된 박싱된 값에 해당하는 부울 값

## 참조

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)