---
title: ToLower()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자를 소문자로 변환합니다.
type: docs
weight: 235
url: /ko/system/char/tolower/
---
## Char::ToLower(char_t) 메서드

Converts the specified character to lower case.

```cpp
static char_t System::Char::ToLower(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 변환할 문자 |

### 반환값

지정된 문자가 대문자일 경우 소문자로 변환된 문자, 그렇지 않으면 지정된 문자

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드

Converts the specified character to lower case.

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 변환할 문자 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 문화별 대소문자 규칙을 제공하는 객체 |

### 반환값

지정된 문자가 대문자일 경우 소문자로 변환된 문자, 그렇지 않으면 지정된 문자

## 참조

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [Char](../)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)