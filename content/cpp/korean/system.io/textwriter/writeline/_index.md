---
title: WriteLine()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스트림에 줄 구분자 문자를 씁니다.
type: docs
weight: 118
url: /ko/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() 메서드

줄 구분자 문자를 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine()
```
## TextWriter::WriteLine(const SharedPtr\<Object\>\&) 메서드

지정된 객체의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 쓰여질 객체 |

## TextWriter::WriteLine(bool) 메서드

지정된 불리언 값의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **bool** | 쓰여질 값 |

## TextWriter::WriteLine(char_t) 메서드

지정된 문자를 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char_t | 쓰여질 값 |

## TextWriter::WriteLine(Decimal) 메서드

지정된 [Decimal](../../../system/decimal/) 객체의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | 쓰여질 객체 |

## TextWriter::WriteLine(double) 메서드

지정된 배정도 부동 소수점 값의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 쓰여질 값 |

## TextWriter::WriteLine(int) 메서드

지정된 32비트 정수 값의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int | 쓰여질 값 |

## TextWriter::WriteLine(int64_t) 메서드

지정된 64비트 정수 값의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **int64_t** | 쓰여질 값 |

## TextWriter::WriteLine(float) 메서드

지정된 단정도 부동 소수점 값의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **float** | 쓰여질 값 |

## TextWriter::WriteLine(const String\&) 메서드

지정된 문자열을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 쓰여질 문자열 |

## TextWriter::WriteLine(uint32_t) 메서드

지정된 부호 없는 32비트 정수 값의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint32_t** | 쓰여질 값 |

## TextWriter::WriteLine(uint64_t) 메서드

지정된 부호 없는 64비트 정수 값의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **uint64_t** | 쓰여질 값 |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) 메서드

지정된 배열의 모든 문자를 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 쓰여질 문자를 포함하는 배열 |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 메서드

지정된 문자 배열에서 지정된 UTF-16 문자 하위 범위를 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 쓰여질 문자를 포함하는 배열 |
| index | **int32_t** | 쓰기 하위 범위가 시작되는 **buffer** 내 0 기반 인덱스 |
| count | **int32_t** | 쓰기 하위 범위의 문자 수; -1은 하위 범위가 **buffer** 배열 끝에서 종료함을 의미합니다 |

## TextWriter::WriteLine(const char_t *) 메서드

지정된 C 문자열을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const char_t * | 쓰여질 C 문자열 |

## TextWriter::WriteLine(const TypeInfo\&) 메서드

지정된 [TypeInfo](../../../system/typeinfo/) 객체의 문자열 표현을 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | 쓰여질 객체 |

## TextWriter::WriteLine(const String\&, const TArgs\&...) 메서드

지정된 형식에 따라 지정된 값을 포맷하고 줄 종료 문자와 함께 스트림에 씁니다.

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TArgs | 쓰여질 값들의 타입 목록 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 문자열 형식 |
| args | const TArgs\&... | 쓰여질 값들 |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [TextWriter](../)
* 클래스 [Object](../../../system/object/)
* 클래스 [Decimal](../../../system/decimal/)
* 클래스 [String](../../../system/string/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)