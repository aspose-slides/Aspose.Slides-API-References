---
title: CompareTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열 비교 규칙으로 두 문자 스팬을 비교합니다.
type: docs
weight: 404
url: /ko/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 함수

지정된 문자열 비교 규칙으로 두 문자 스팬을 비교합니다.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 첫 번째 문자 스팬 |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 두 번째 문자 스팬 |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 수행할 문자열 비교 유형 |

### 반환 값

span < other인 경우 음수, 같으면 0, span > other인 경우 양수

## 참조

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)