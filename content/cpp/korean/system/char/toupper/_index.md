---
title: ToUpper()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자를 대문자로 변환합니다.
type: docs
weight: 222
url: /ko/system/char/toupper/
---
## Char::ToUpper(char_t) 메서드

지정된 문자를 대문자로 변환합니다.

```cpp
static char_t System::Char::ToUpper(char_t c)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 변환할 문자 |

### 반환 값

지정된 문자가 소문자이면 대문자로 변환한 문자, 그렇지 않으면 지정된 문자 그대로

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) 메서드

지정된 문자를 대문자로 변환합니다.

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 변환할 문자 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 문화별 대소문자 규칙을 제공하는 객체. |

### 반환 값

지정된 문자가 소문자이면 대문자로 변환한 문자, 그렇지 않으면 지정된 문자 그대로

## 참조

* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [Char](../)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)