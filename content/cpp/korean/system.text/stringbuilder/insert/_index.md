---
title: Insert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열을 빌더의 고정 위치에 삽입합니다.
type: docs
weight: 183
url: /ko/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) 메서드

문자열을 빌더의 고정 위치에 삽입합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 문자를 삽입할 위치. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/)을 삽입합니다. |

### 반환값

이 포인터.

## StringBuilder::Insert(int32_t, const String\&, int32_t) 메서드

반복 문자열을 빌더의 고정 위치에 삽입합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 문자를 삽입할 위치. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/)을 삽입합니다. |
| count | **int32_t** | **value** 문자열을 반복할 횟수. |

### 반환값

이 포인터.

## StringBuilder::Insert(int, char_t) 메서드

문자를 빌더의 고정 위치에 삽입합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 문자를 삽입할 위치. |
| ch | char_t | 삽입할 문자. |

### 반환값

이 포인터.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) 메서드

문자들을 빌더의 고정 위치에 삽입합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 문자를 삽입할 위치. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/)에서 삽입할 슬라이스. |
| startIndex | int | [Array](../../../system/array/) 슬라이스 시작 인덱스. |
| charCount | int | [Array](../../../system/array/) 슬라이스 길이. |

### 반환값

이 포인터.

## StringBuilder::Insert(int, T) 메서드

값을 빌더의 고정 위치에 삽입합니다.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| 매개변수 | 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startIndex | int | 문자를 삽입할 위치. |
| value | T | 포맷하고 삽입할 값. |

### 반환값

이 포인터.

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [StringBuilder](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)