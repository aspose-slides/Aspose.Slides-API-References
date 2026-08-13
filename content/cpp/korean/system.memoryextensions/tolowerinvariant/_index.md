---
title: ToLowerInvariant()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 불변 문화권을 사용하여 문자를 소문자로 변환합니다.
type: docs
weight: 456
url: /ko/system.memoryextensions/tolowerinvariant/
---
## System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) 함수

불변 문화권을 사용하여 문자를 소문자로 변환합니다.

```cpp
int32_t System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 변환할 소스 문자 스팬 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 변환된 문자를 저장할 대상 스팬 |

### 반환 값

변환된 문자 수, 혹은 대상이 너무 작으면 -1

## 참조

* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)