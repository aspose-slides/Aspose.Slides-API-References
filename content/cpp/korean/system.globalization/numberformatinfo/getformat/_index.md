---
title: GetFormat()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 특정 유형의 포맷터를 가져옵니다.
type: docs
weight: 742
url: /ko/system.globalization/numberformatinfo/getformat/
---
## NumberFormatInfo::GetFormat(const TypeInfo\&) 메서드

특정 유형의 포맷터를 가져옵니다.

```cpp
SharedPtr<Object> System::Globalization::NumberFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | 포맷터를 가져오기 위한 유형; 오직 [NumberFormatInfo](../) 유형만 지원됩니다. |

### 반환 값

Formatter 또는 사용 불가능한 경우 null.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [NumberFormatInfo](../)
* 네임스페이스 [System::Globalization](../../)
* Library [Aspose.Slides](../../../)