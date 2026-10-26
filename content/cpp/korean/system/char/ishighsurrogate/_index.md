---
title: IsHighSurrogate()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열의 지정된 인덱스에 있는 문자가 UTF-16 상위 서러게이트 코드 유닛인지 확인합니다.
type: docs
weight: 40
url: /ko/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) 메서드

지정된 문자열의 지정된 인덱스에 있는 문자가 UTF-16 상위 서러게이트 코드 유닛인지 확인합니다.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 문자열 |
| index | int | 테스트할 문자가 있는 지정된 문자열 내의 인덱스 |

### 반환값

지정된 인덱스에 있는 문자가 UTF-16 상위 서러게이트 코드 유닛이면 True, 그렇지 않으면 - false

## Char::IsHighSurrogate(const char_t *, int) 메서드

지정된 문자 버퍼의 지정된 인덱스에 있는 문자가 상위 서러게이트인지 확인합니다.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const char_t * | 문자 버퍼 시작을 가리키는 포인터 |
| idx | int | 테스트할 문자가 있는 지정된 버퍼 내의 0부터 시작하는 인덱스 |

### 반환값

지정된 인덱스에 있는 문자가 상위 서러게이트이면 True, 그렇지 않으면 - false

## Char::IsHighSurrogate(char_t) 메서드

지정된 문자가 상위 서러게이트인지 확인합니다.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 테스트할 문자 |

### 반환값

지정된 문자가 상위 서러게이트이면 True, 그렇지 않으면 - false

## 참고

* 클래스 [String](../../string/)
* 클래스 [Char](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)