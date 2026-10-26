---
title: IsLower()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자 버퍼에서 지정된 인덱스에 있는 문자가 소문자로 분류되는지 여부를 결정합니다.
type: docs
weight: 196
url: /ko/system/char/islower/
---
## Char::IsLower(const char_t *, int) 메서드

지정된 문자 버퍼에서 지정된 인덱스에 있는 문자가 소문자로 분류되는지 여부를 결정합니다.

```cpp
static bool System::Char::IsLower(const char_t *str, int idx)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const char_t * | 문자 버퍼의 시작을 가리키는 포인터 |
| idx | int | 테스트할 문자의 지정된 버퍼에서 0부터 시작하는 인덱스 |

### 반환 값

True if the character at the specified index is a lower case letter, otherwise - false

## Char::IsLower(char_t) 메서드

지정된 문자가 소문자로 분류되는지 여부를 결정합니다.

```cpp
static bool System::Char::IsLower(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 테스트할 문자 |

### 반환 값

True if the specified character is a lower case letter, otherwise - false

## Char::IsLower(const String\&, int) 메서드

지정된 문자열에서 지정된 인덱스에 있는 문자가 소문자로 분류되는지 여부를 결정합니다.

```cpp
static bool System::Char::IsLower(const String &str, int idx)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 문자열 |
| idx | int | 테스트할 문자열에서 0부터 시작하는 인덱스 |

### 반환 값

True if the character at the specified index is a lower case letter, otherwise - false

## 참고

* 클래스 [Char](../)
* 클래스 [String](../../string/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)