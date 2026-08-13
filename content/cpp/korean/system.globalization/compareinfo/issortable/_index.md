---
title: IsSortable()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자가 정렬 가능한지 확인합니다.
type: docs
weight: 196
url: /ko/system.globalization/compareinfo/issortable/
---
## CompareInfo::IsSortable(char16_t) 메서드

지정된 문자가 정렬 가능한지 확인합니다.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(char16_t ch)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ch | char16_t | Unicode 문자. |

### 반환 값

**ch**가 정렬 가능하면 true; 그렇지 않으면 false.

## CompareInfo::IsSortable(const String\&) 메서드

지정된 문자열이 정렬 가능한지 확인합니다.

```cpp
static bool System::Globalization::CompareInfo::IsSortable(const String &text)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | const [String](../../../system/string/)\& | 문자열. |

### 반환 값

**text**가 비어 있지 않고 **text**의 모든 문자가 정렬 가능하면 true; 그렇지 않으면 false.

## 참고

* 클래스 [CompareInfo](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)