---
title: ConvertToUtf32()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 UTF-16 서러게이트 쌍을 UTF-32 코드 유닛으로 변환합니다.
type: docs
weight: 287
url: /ko/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) 메서드

UTF-16 서러게이트 쌍을 UTF-32 코드 유닛으로 변환합니다.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| highSurrogate | char_t | 변환할 UTF-16 서러게이트 쌍의 고위 서러게이트 |
| lowSurrogate | char_t | 변환할 UTF-16 서러게이트 쌍의 저위 서러게이트 |

### 반환 값

변환 결과인 UTF-32 코드 유닛

## Char::ConvertToUtf32(const String\&, int) 메서드

문자열 내 지정된 위치에 있는 UTF-16 인코딩 문자 또는 서러게이트 쌍을 UTF-32 코드 유닛으로 변환합니다.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 문자 또는 서러게이트 쌍을 포함하는 문자열 |
| index | int | 지정된 문자열에서 문자 또는 서러게이트 쌍의 인덱스 위치 |

### 반환 값

변환 결과인 UTF-32 코드 유닛

## 참고

* 클래스 [Char](../)
* 클래스 [String](../../string/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)