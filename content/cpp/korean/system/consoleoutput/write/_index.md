---
title: Write()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 bool 값의 문자열 표현을 현재 객체가 나타내는 출력 스트림에 출력합니다.
type: docs
weight: 14
url: /ko/system/consoleoutput/write/
---
## ConsoleOutput::Write(bool) 메서드

현재 객체가 나타내는 출력 스트림에 지정된 bool 값의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(bool value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **bool** | 출력할 값 |

## ConsoleOutput::Write(const SharedPtr\<Object\>\&) 메서드

현재 객체가 나타내는 출력 스트림에 지정된 객체의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(const SharedPtr<Object> &value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 출력할 객체 |

## ConsoleOutput::Write(char_t) 메서드

현재 객체가 나타내는 출력 스트림에 지정된 문자 값을 출력합니다.

```cpp
void System::ConsoleOutput::Write(char_t value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char_t | 출력할 값 |

## ConsoleOutput::Write(Decimal) 메서드

현재 객체가 나타내는 출력 스트림에 [Decimal](../../decimal/) 값의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(Decimal value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | 출력할 값 |

## ConsoleOutput::Write(double) 메서드

현재 객체가 나타내는 출력 스트림에 배정밀도 부동소수점 값의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(double value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 출력할 값 |

## ConsoleOutput::Write(int32_t) 메서드

현재 객체가 나타내는 출력 스트림에 32비트 정수 값의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(int32_t value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **int32_t** | 출력할 값 |

## ConsoleOutput::Write(int64_t) 메서드

현재 객체가 나타내는 출력 스트림에 64비트 정수 값의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(int64_t value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **int64_t** | 출력할 값 |

## ConsoleOutput::Write(float) 메서드

현재 객체가 나타내는 출력 스트림에 단정밀도 부동소수점 값의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(float value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **float** | 출력할 값 |

## ConsoleOutput::Write(const String\&) 메서드

현재 객체가 나타내는 출력 스트림에 지정된 문자열 객체를 출력합니다.

```cpp
void System::ConsoleOutput::Write(const String &value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 출력할 문자열 객체 |

## ConsoleOutput::Write(uint32_t) 메서드

현재 객체가 나타내는 출력 스트림에 부호 없는 32비트 정수 값의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(uint32_t value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint32_t** | 출력할 값 |

## ConsoleOutput::Write(uint64_t) 메서드

현재 객체가 나타내는 출력 스트림에 부호 없는 64비트 정수 값의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(uint64_t value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint64_t** | 출력할 값 |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&) 메서드

현재 객체가 나타내는 출력 스트림에 지정된 문자 배열의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 출력할 배열 |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 메서드

현재 객체가 나타내는 출력 스트림에 지정된 문자 배열의 값 범위에 대한 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 출력할 값이 포함된 배열 |
| index | **int32_t** | 출력 범위가 시작되는 인덱스 |
| count | **int32_t** | 출력 범위에 포함되는 요소 수 |

## ConsoleOutput::Write(const char_t *) 메서드

현재 객체가 나타내는 출력 스트림에 지정된 C 문자열을 출력합니다.

```cpp
void System::ConsoleOutput::Write(const char_t *value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 출력할 C 문자열 |

## ConsoleOutput::Write(const TypeInfo\&) 메서드

현재 객체가 나타내는 출력 스트림에 지정된 [TypeInfo](../../typeinfo/) 객체의 문자열 표현을 출력합니다.

```cpp
void System::ConsoleOutput::Write(const TypeInfo &value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 출력할 [TypeInfo](../../typeinfo/) 객체 |

## ConsoleOutput::Write(const char *) 메서드




```cpp
void System::ConsoleOutput::Write(const char *)=delete
```

## 참고

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [ConsoleOutput](../)
* Class [Object](../../object/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)