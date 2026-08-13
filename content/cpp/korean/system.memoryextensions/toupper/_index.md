---
title: ToUpper()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문화권을 사용하여 문자를 대문자로 변환합니다.
type: docs
weight: 469
url: /ko/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) 함수


지정된 문화권을 사용하여 문자를 대문자로 변환합니다.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 변환할 원본 문자 span |
| destination | [Span](../../system/span/)\<char16_t\>\& | 변환된 문자를 저장할 대상 span |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | 변환에 사용할 문화권(현재 문화권의 경우 nullptr) |

### 반환값

변환된 문자 수, 대상이 너무 작으면 -1

## 참조

* 타입 정의 [SharedPtr](../../system/sharedptr/)
* 클래스 [ReadOnlySpan](../../system/readonlyspan/)
* 클래스 [Span](../../system/span/)
* 클래스 [CultureInfo](../../system.globalization/cultureinfo/)
* 네임스페이스 [System::MemoryExtensions](../)
* 라이브러리 [Aspose.Slides](../../)