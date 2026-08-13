---
title: IsUpper()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열에서 지정된 인덱스에 있는 문자가 대문자인지 여부를 결정합니다.
type: docs
weight: 183
url: /ko/system/char/isupper/
---
## Char::IsUpper(const String\&, int) 메서드

지정된 문자열에서 지정된 인덱스에 있는 문자가 대문자인지 여부를 결정합니다.

```cpp
static bool System::Char::IsUpper(const String &str, int idx)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 문자를 포함하는 문자열. |
| idx | int | 지정된 문자열에서 테스트할 문자에 대한 0부터 시작하는 인덱스 |

### 반환값

지정된 인덱스에 있는 문자가 대문자이면 true, 그렇지 않으면 false

## Char::IsUpper(const char_t *, int) 메서드

지정된 문자 버퍼에서 지정된 인덱스에 있는 문자가 대문자인지 여부를 결정합니다.

```cpp
static bool System::Char::IsUpper(const char_t *str, int idx)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const char_t * | 문자 버퍼 시작을 가리키는 포인터. |
| idx | int | 지정된 버퍼에서 테스트할 문자에 대한 0부터 시작하는 인덱스 |

### 반환값

지정된 인덱스에 있는 문자가 대문자이면 true, 그렇지 않으면 false

## Char::IsUpper(char_t) 메서드

지정된 문자가 대문자인지 여부를 결정합니다.

```cpp
static bool System::Char::IsUpper(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 테스트할 문자. |

### 반환값

지정된 문자가 대문자이면 true, 그렇지 않으면 false

## 참고

* 클래스 [String](../../string/)
* 클래스 [Char](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)