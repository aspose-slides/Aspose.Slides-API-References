---
title: GetInstance()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 포맷 제공자와 연결된 포맷터를 가져옵니다.
type: docs
weight: 846
url: /ko/system.globalization/datetimeformatinfo/getinstance/
---
## DateTimeFormatInfo::GetInstance(const IFormatProviderPtr\&) 메서드

포맷 제공자와 연결된 포맷터를 가져옵니다.

```cpp
static DateTimeFormatInfoPtr System::Globalization::DateTimeFormatInfo::GetInstance(const IFormatProviderPtr &provider)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| provider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | 형식을 가져올 제공자. |

### 반환값

포맷 제공자와 연결된 포맷터 또는 사용할 수 없는 경우 현재 스레드의 포맷을 반환합니다.

## 참조

* 타입 정의 [DateTimeFormatInfoPtr](../../datetimeformatinfoptr/)
* 타입 정의 [IFormatProviderPtr](../../../system/iformatproviderptr/)
* 클래스 [DateTimeFormatInfo](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)