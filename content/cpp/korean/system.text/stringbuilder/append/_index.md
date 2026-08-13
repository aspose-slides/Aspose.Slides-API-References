---
title: Append()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빌더에 문자를 추가합니다.
type: docs
weight: 118
url: /ko/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) 메서드

빌더에 문자를 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 문자 값. |

### 반환 값

이 포인터.

## StringBuilder::Append(char_t, int) 메서드

빌더에 문자를 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 문자 값. |
| count | int | 삽입할 문자를 반복할 횟수. |

### 반환 값

이 포인터.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) 메서드

빌더에 문자 배열을 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 추가할 문자들. |

### 반환 값

이 포인터.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) 메서드

빌더에 문자 배열 슬라이스를 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 추가할 문자들. |
| startIndex | int | 슬라이스 시작 인덱스. |
| charCount | int | 슬라이스 길이. |

### 반환 값

이 포인터.

## StringBuilder::Append(const String\&) 메서드

빌더에 문자열을 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 추가할 [String](../../../system/string/). |

### 반환 값

이 포인터.

## StringBuilder::Append(const String\&, int, int) 메서드

빌더에 문자열 슬라이스를 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | 추가할 [String](../../../system/string/). |
| startIndex | int | 슬라이스 시작 인덱스. |
| charCount | int | 슬라이스 길이. |

### 반환 값

이 포인터.

## StringBuilder::Append(const SharedPtr\<T\>\&) 메서드

빌더에 객체의 문자열 표현을 추가합니다.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Object](../../../system/object/) 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | 직렬화하여 추가할 [Object](../../../system/object/). |

### 반환 값

이 포인터.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) 메서드

빌더에 빌더의 내용을 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | 내용을 추가할 빌더. |

### 반환 값

이 포인터.

## StringBuilder::Append(float) 메서드

빌더에 부동 소수점 값을 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| f | **float** | 직렬화하여 추가할 값. |

### 반환 값

이 포인터.

## StringBuilder::Append(double) 메서드

빌더에 부동 소수점 값을 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| df | **double** | 직렬화하여 추가할 값. |

### 반환 값

이 포인터.

## StringBuilder::Append(int) 메서드

빌더에 정수 값을 추가합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | int | 직렬화하여 추가할 값. |

### 반환 값

이 포인터.

## StringBuilder::Append(T) 메서드

빌더에 산술 값을 추가합니다.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 산술 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | T | 직렬화하여 추가할 값. |

### 반환 값

이 포인터.

## StringBuilder::Append(E) 메서드

빌더에 열거형 값의 문자열 표현을 추가합니다.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| E | [Enum](../../../system/enum/) 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| e | E | 직렬화하여 추가할 값. |

### 반환 값

이 포인터.

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [StringBuilder](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)