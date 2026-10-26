---
title: Replace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빌더를 통해 하위 문자열을 교체합니다.
type: docs
weight: 196
url: /ko/system.text/stringbuilder/replace/
---
## StringBuilder::Replace(const String&, const String&) 메서드

빌더를 통해 하위 문자열을 교체합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) 교체 대상. |
| newString | const [String](../../../system/string/)\& | 교체 문자열. |

### 반환 값

This pointer.

## StringBuilder::Replace(const String&, const String&, int, int) 메서드

빌더의 범위를 통해 하위 문자열을 교체합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Replace(const String &oldString, const String &newString, int position, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldString | const [String](../../../system/string/)\& | [String](../../../system/string/) 교체 대상. |
| newString | const [String](../../../system/string/)\& | 교체 문자열. |
| position | int | 빌더 교체 범위 시작 위치. |
| count | int | 빌더 교체 범위 길이. |

### 반환 값

This pointer.

## StringBuilder::Replace(char_t, char_t) 메서드

빌더를 통해 문자를 교체합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldChar | char_t | 교체할 문자. |
| newChar | char_t | 교체 문자. |

### 반환 값

This pointer.

## StringBuilder::Replace(char_t, char_t, int, int) 메서드

빌더의 범위를 통해 문자를 교체합니다.

```cpp
StringBuilder * System::Text::StringBuilder::Replace(char_t oldChar, char_t newChar, int startIndex, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldChar | char_t | 교체할 문자. |
| newChar | char_t | 교체 문자. |
| startIndex | int | 빌더 교체 범위 시작 위치. |
| count | int | 빌더 교체 범위 길이. |

### 반환 값

This pointer.

## 참고

* 클래스 [StringBuilder](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Text](../../)
* Library [Aspose.Slides](../../../)