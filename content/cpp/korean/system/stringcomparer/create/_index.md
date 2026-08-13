---
title: Create()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문화별 비교자를 생성합니다.
type: docs
weight: 79
url: /ko/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) 메서드

문화별 비교자를 생성합니다.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 비교자를 생성할 문화입니다. |
| ignoreCase | **bool** | 비교자가 대소문자를 무시해야 하는지 여부입니다. |

### 반환값

새로 생성된 비교자 객체에 대한 포인터입니다.

## 참조

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [StringComparer](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)