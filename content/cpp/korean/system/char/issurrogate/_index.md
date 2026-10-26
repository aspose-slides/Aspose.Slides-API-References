---
title: IsSurrogate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자가 UTF-16 서러게이트 코드 유닛인지 여부를 확인합니다.
type: docs
weight: 14
url: /ko/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) 메서드

지정된 문자가 UTF-16 서러게이트 코드 유닛인지 여부를 확인합니다.

```cpp
static bool System::Char::IsSurrogate(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 문자 |

### 반환 값

지정된 문자가 UTF-16 서러게이트 코드 유닛이면 true이며, 그렇지 않으면 false입니다.

## Char::IsSurrogate(const String\&, int) 메서드

지정된 문자열에서 지정된 인덱스에 있는 문자가 UTF-16 서러게이트 코드 유닛인지 여부를 확인합니다.

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 문자열 |
| index | int | 지정된 문자열에서 문자의 인덱스 |

### 반환 값

지정된 인덱스에 있는 문자가 UTF-16 서러게이트 코드 유닛이면 true이며, 그렇지 않으면 false입니다.

## 참고

* 클래스 [Char](../)
* 클래스 [String](../../string/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)