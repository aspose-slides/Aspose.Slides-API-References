---
title: Write()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 객체의 문자열 표현을 스트림에 씁니다.
type: docs
weight: 105
url: /ko/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) 메서드

지정된 객체의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 쓰기 위한 객체 |

## TextWriter::Write(bool) 메서드

지정된 부울 값의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **bool** | 쓰기 위한 값 |

## TextWriter::Write(char_t) 메서드

지정된 문자를 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char_t | 쓰기 위한 값 |

## TextWriter::Write(Decimal) 메서드

지정된 [Decimal](../../../system/decimal/) 객체의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | 쓰기 위한 객체 |

## TextWriter::Write(double) 메서드

지정된 배정밀도 부동 소수점 값의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 쓰기 위한 값 |

## TextWriter::Write(int) 메서드

지정된 32비트 정수 값의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int | 쓰기 위한 값 |

## TextWriter::Write(int64_t) 메서드

지정된 64비트 정수 값의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **int64_t** | 쓰기 위한 값 |

## TextWriter::Write(float) 메서드

지정된 단정밀도 부동 소수점 값의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **float** | 쓰기 위한 값 |

## TextWriter::Write(const String\&) 메서드

지정된 문자열을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 쓰기 위한 문자열 |

## TextWriter::Write(uint32_t) 메서드

지정된 부호없는 32비트 정수 값의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint32_t** | 쓰기 위한 값 |

## TextWriter::Write(uint64_t) 메서드

지정된 부호없는 64비트 정수 값의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint64_t** | 쓰기 위한 값 |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) 메서드

지정된 배열의 모든 문자를 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 쓰기 위한 문자들을 포함한 배열 |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 메서드

지정된 문자 배열에서 지정된 UTF-16 문자 부분 범위를 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 쓰기 위한 문자들을 포함한 배열 |
| index | **int32_t** | **buffer**에서 쓰기 부분 범위가 시작되는 0 기반 인덱스 |
| count | **int32_t** | 쓰기 부분 범위에 포함된 문자 수; **-1**은 **buffer** 배열이 끝나는 지점까지를 의미 |

## TextWriter::Write(const char_t *) 메서드

지정된 C 문자열을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 쓰기 위한 C 문자열 |

## TextWriter::Write(const TypeInfo\&) 메서드

지정된 [TypeInfo](../../../system/typeinfo/) 객체의 문자열 표현을 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | 쓰기 위한 객체 |

## TextWriter::Write(const String\&, const TArgs\&...) 메서드

지정된 형식에 따라 지정된 값을 형식화하여 스트림에 씁니다.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TArgs | 작성할 값들의 형식 목록 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 문자열 형식 |
| args | const TArgs\&... | 작성할 값들 |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TextWriter](../)
* 클래스 [Decimal](../../../system/decimal/)
* 클래스 [String](../../../system/string/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)