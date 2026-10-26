---
title: ReadOnly()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문화의 읽기 전용 버전을 가져옵니다.
type: docs
weight: 625
url: /ko/system.globalization/cultureinfo/readonly/
---
## CultureInfo::ReadOnly(const CultureInfoPtr\&) 메서드

문화의 읽기 전용 버전을 가져옵니다.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::ReadOnly(const CultureInfoPtr &culture_info)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| culture_info | const [CultureInfoPtr](../../cultureinfoptr/)\& | 읽기 전용으로 래핑할 문화. |

### 반환 값

**culture_info**가 읽기 전용인 경우 동일한 객체를 반환하고, 그렇지 않으면 읽기 전용 복사본을 생성합니다.

## 관련 항목

* 타입 정의 [CultureInfoPtr](../../cultureinfoptr/)
* 클래스 [CultureInfo](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)