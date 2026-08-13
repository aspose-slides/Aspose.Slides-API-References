---
title: GetFormat()
second_title: Aspose.Slides for C++ API 참조
description: 특정 유형의 포맷터를 가져옵니다.
type: docs
weight: 14
url: /ko/system.globalization/datetimeformatinfo/getformat/
---
## DateTimeFormatInfo::GetFormat(const TypeInfo\&) 메서드

특정 유형의 포맷터를 가져옵니다.

```cpp
SharedPtr<Object> System::Globalization::DateTimeFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | 가져올 포맷터의 타입; [DateTimeFormatInfo](../) 타입만 지원됩니다. |

### 반환 값

포맷터 또는 사용 불가능한 경우 null을 반환합니다.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [DateTimeFormatInfo](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)