---
title: ToLower()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문화권을 사용하여 문자를 소문자로 변환합니다.
type: docs
weight: 443
url: /ko/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) 함수

지정된 문화권을 사용하여 문자를 소문자로 변환합니다.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 변환할 소스 문자 스팬 |
| destination | [Span](../../system/span/)\<char16_t\>\& | 변환된 문자를 저장할 대상 스팬 |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | 변환에 사용할 문화권 (현재 문화권인 경우 nullptr) |

### 반환 값

변환된 문자 수, 또는 대상이 너무 작으면 -1

## 관련 항목

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)