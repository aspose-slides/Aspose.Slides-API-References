---
title: IsLetterOrDigit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자 버퍼에서 지정된 인덱스에 있는 문자가 Unicode 문자 또는 십진수 숫자로 분류되는지 확인합니다.
type: docs
weight: 105
url: /ko/system/char/isletterordigit/
---
## Char::IsLetterOrDigit(const char_t *, int) 메서드

지정된 문자 버퍼에서 지정된 인덱스에 있는 문자가 Unicode 문자 또는 십진수 숫자로 분류되는지 확인합니다.

```cpp
static bool System::Char::IsLetterOrDigit(const char_t *str, int idx)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const char_t * | 문자 버퍼의 시작을 가리키는 포인터 |
| idx | int | 테스트할 문자의 지정된 버퍼에서 0부터 시작하는 인덱스 |

### 반환 값

지정된 인덱스에 있는 문자가 Unicode 문자 또는 십진수 숫자인 경우 true, 그렇지 않으면 false

## Char::IsLetterOrDigit(char_t) 메서드

지정된 문자가 Unicode 문자 또는 십진수 숫자로 분류되는지 확인합니다.

```cpp
static bool System::Char::IsLetterOrDigit(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 테스트할 문자 |

### 반환 값

지정된 문자가 Unicode 문자 또는 십진수 숫자인 경우 true, 그렇지 않으면 false

## 참고

* 클래스 [Char](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)