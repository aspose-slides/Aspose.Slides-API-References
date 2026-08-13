---
title: CompareOrdinal()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 서열 모드를 사용하여 두 문자열을 비교합니다.
type: docs
weight: 833
url: /ko/system/string/compareordinal/
---
## String::CompareOrdinal(const String&, const String&) 메서드

서열 모드(ordinal mode)를 사용하여 두 문자열을 비교합니다.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| strA | const [String](../)& | 비교할 첫 번째 문자열입니다. |
| strB | const [String](../)& | 비교할 두 번째 문자열입니다. |

### 반환 값

첫 번째 부분 문자열이 두 번째보다 작으면 음수, 일치하면 0, 그 외에는 양수입니다.

## String::CompareOrdinal(const String&, int, const String&, int, int) 메서드

서열 모드(ordinal mode)를 사용하여 두 문자열을 비교합니다.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| strA | const [String](../)& | 비교할 첫 번째 문자열입니다. |
| indexA | int | 첫 번째 문자열 부분 문자열의 시작 위치입니다. |
| strB | const [String](../)& | 비교할 두 번째 문자열입니다. |
| indexB | int | 두 번째 문자열 부분 문자열의 시작 위치입니다. |
| length | int | 비교할 문자 수입니다. |

### 반환 값

첫 번째 부분 문자열이 두 번째보다 작으면 음수, 일치하면 0, 그 외에는 양수입니다.

## 참조

* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)