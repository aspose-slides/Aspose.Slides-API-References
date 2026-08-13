---
title: WriteLine()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스트림에 줄 구분 문자를 씁니다.
type: docs
weight: 92
url: /ko/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() 메서드

스트림에 줄 구분 문자를 씁니다.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) 메서드

지정된 문자열을 줄 구분 문자와 함께 스트림에 씁니다.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 쓰기 위한 문자열 |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) 메서드

지정된 객체의 문자열 표현을 줄 구분 문자와 함께 스트림에 씁니다.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 쓰기 위한 객체 |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) 메서드

지정된 배열의 모든 문자를 줄 구분 문자와 함께 스트림에 씁니다.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 쓰기에 사용할 문자를 포함하는 배열 |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) 메서드

지정된 문자 배열에서 UTF-16 문자 지정 범위를 선택하여 줄 구분 문자와 함께 스트림에 씁니다.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 쓰기에 사용할 문자를 포함하는 배열 |
| index | **int32_t** | **buffer**에서 쓰기 하위 범위가 시작되는 0 기반 인덱스 |
| count | **int32_t** | 쓰기 하위 범위에 포함된 문자 수; -1은 하위 범위가 **buffer** 배열 끝까지임을 나타냅니다. |

## StreamWriter::WriteLine(const char_t *) 메서드

지정된 C 문자열을 줄 구분 문자와 함께 스트림에 씁니다.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | const char_t * | 쓰기 위한 C 문자열 |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) 메서드

지정된 객체의 문자열 표현을 줄 구분 문자와 함께 스트림에 씁니다.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 객체의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | 쓰기 위한 객체 |

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [StreamWriter](../)
* 클래스 [String](../../../system/string/)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)