---
title: IsPrefix()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문자열이 지정된 접두사로 시작하는지 지정된 비교 옵션을 사용하여 확인합니다.
type: docs
weight: 105
url: /ko/system.globalization/compareinfo/isprefix/
---
## CompareInfo::IsPrefix(const String\&, const String\&, CompareOptions) const 메서드

지정된 문자열이 지정된 접두사로 시작하는지 지정된 비교 옵션을 사용하여 확인합니다.

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix, CompareOptions options) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 원본 문자열. |
| prefix | const [String](../../../system/string/)\& | 접두사 문자열. |
| options | [CompareOptions](../../compareoptions/) | 비교 옵션. |

### 반환값

True if string starts with prefix; otherwise false.

## CompareInfo::IsPrefix(const String\&, const String\&) const 메서드

지정된 문자열이 지정된 접두사로 시작하는지 확인합니다.

```cpp
virtual bool System::Globalization::CompareInfo::IsPrefix(const String &source, const String &prefix) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 원본 문자열. |
| prefix | const [String](../../../system/string/)\& | 접두사 문자열. |

### 반환값

True if string starts with prefix; otherwise false.

## 관련 항목

* 열거형 [CompareOptions](../../compareoptions/)
* 클래스 [String](../../../system/string/)
* 클래스 [CompareInfo](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)