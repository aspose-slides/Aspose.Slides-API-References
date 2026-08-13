---
title: Equals()
second_title: Aspose.Slides for C++ API 레퍼런스
description: StringComparison을 사용하여 두 ReadOnlySpan<char16_t>를 동일성으로 비교합니다.
type: docs
weight: 417
url: /ko/system.memoryextensions/equals/
---
## System::MemoryExtensions::Equals(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 함수


StringComparison을 사용하여 두 ReadOnlySpan<char16_t>의 동일성을 비교합니다.

```cpp
bool System::MemoryExtensions::Equals(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 비교할 첫 번째 span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 비교할 두 번째 span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 사용할 문자열 비교 유형 |

### 반환 값

span이 동일하면 true, 그렇지 않으면 false

## 참고

* 열거형 [StringComparison](../../system/stringcomparison/)
* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)