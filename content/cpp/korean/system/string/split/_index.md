---
title: Split()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자를 기준으로 문자열을 분할합니다.
type: docs
weight: 768
url: /ko/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const method

문자를 기준으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separator | char_t | 문자열을 구분할 문자. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## String::Split(char_t, int32_t, StringSplitOptions) const method

문자를 기준으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separator | char_t | 문자열을 구분할 문자. |
| count | **int32_t** | 반환할 최대 부분 문자열 수. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## String::Split(char_t, char_t, StringSplitOptions) const method

두 문자 중 하나를 기준으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separatorA | char_t | 문자열을 구분할 첫 번째 문자. |
| separatorB | char_t | 문자열을 구분할 두 번째 문자. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const method

지정된 문자 중 하나를 기준으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 구분 문자. 비어 있으면 모든 공백 문자를 구분자로 간주합니다. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const method

지정된 문자 중 하나를 기준으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 구분 문자. 비어 있으면 모든 공백 문자를 구분자로 간주합니다. |
| count | **int32_t** | 반환할 최대 부분 문자열 수. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## String::Split(const String\&, StringSplitOptions) const method

부분 문자열을 기준으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separator | const [String](../)\& | 구분자로 작용하는 부분 문자열. 비어 있으면 공백 문자를 구분자로 사용합니다. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## String::Split(const String\&, int, StringSplitOptions) const method

부분 문자열을 기준으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separator | const [String](../)\& | 구분자로 작용하는 부분 문자열. 비어 있으면 공백 문자를 구분자로 사용합니다. |
| count | int | 분할 배열의 최대 요소 수. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const method

부분 문자열을 기준으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) 구분 문자열. 비어 있으면 분할이 수행되지 않습니다. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const method

부분 문자열을 기준으로 문자열을 분할합니다. 현재는 구분자 배열이 0개 또는 1개 요소인 경우만 지원합니다.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) 구분 문자열. 비어 있으면 분할이 수행되지 않습니다. |
| count | int | 분할 배열의 최대 요소 수. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 분할 옵션. |

### 반환값

[Array](../../array/) 부분 문자열.

## 참고

* 열거형 [StringSplitOptions](../../stringsplitoptions/)
* 타입 정의 [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)