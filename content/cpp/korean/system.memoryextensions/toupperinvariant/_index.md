---
title: ToUpperInvariant()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 불변 문화 규칙을 사용하여 문자를 대문자로 변환합니다.
type: docs
weight: 482
url: /ko/system.memoryextensions/toupperinvariant/
---
## System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) 함수

불변 문화 규칙을 사용하여 문자를 대문자로 변환합니다.

```cpp
int32_t System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 변환할 원본 문자 스팬 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 변환된 문자를 저장할 대상 스팬 |

### 반환값

변환된 문자 수, 또는 대상이 너무 작으면 -1

## 관련 항목

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)