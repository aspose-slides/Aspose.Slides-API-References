---
title: IsDigit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 십진 숫자로 분류되는지 여부를 결정합니다.
type: docs
weight: 79
url: /ko/system/char/isdigit/
---
## Char::IsDigit(const char_t *, int) 메서드

지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 십진 숫자로 분류되는지 여부를 결정합니다.

```cpp
static bool System::Char::IsDigit(const char_t *str, int idx)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const char_t * | 문자 버퍼의 시작을 가리키는 포인터 |
| idx | int | 테스트할 문자의 지정된 버퍼 내에서 0부터 시작하는 인덱스 |

### 반환 값

문자가 지정된 인덱스에서 십진 숫자인 경우 True, 그렇지 않으면 false

## Char::IsDigit(const String\&, const int32_t) 메서드

지정된 문자열의 지정된 인덱스에 있는 문자가 십진 숫자로 분류되는지 여부를 결정합니다.

```cpp
static bool System::Char::IsDigit(const String &str, const int32_t idx)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 문자열 |
| idx | const **int32_t** | 테스트할 문자의 지정된 버퍼 내에서 0부터 시작하는 인덱스 |

### 반환 값

문자가 지정된 인덱스에서 십진 숫자인 경우 True, 그렇지 않으면 false

## Char::IsDigit(char_t) 메서드

지정된 문자가 십진 숫자로 분류되는지 여부를 결정합니다.

```cpp
static bool System::Char::IsDigit(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 테스트할 문자 |

### 반환 값

문자가 십진 숫자인 경우 True, 그렇지 않으면 false

## 관련 항목

* 클래스 [Char](../)
* 클래스 [String](../../string/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)