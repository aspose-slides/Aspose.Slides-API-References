---
title: ReadOnly()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문화에 대한 읽기 전용 버전을 가져옵니다.
type: docs
weight: 248
url: /ko/system.globalization/textinfo/readonly/
---
## TextInfo::ReadOnly(const TextInfoPtr\&) method

문화에 대한 읽기 전용 버전을 가져옵니다.

```cpp
static TextInfoPtr System::Globalization::TextInfo::ReadOnly(const TextInfoPtr &text_info)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text_info | const [TextInfoPtr](../../textinfoptr/)\& | [TextInfo](../)을(를) 읽기 전용으로 래핑합니다. |

### 반환 값

**text_info**가 읽기 전용이면 동일한 객체를 반환하고, 그렇지 않으면 읽기 전용 복사본을 생성합니다.

## 참고

* 타입 정의 [TextInfoPtr](../../textinfoptr/)
* 클래스 [TextInfo](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)