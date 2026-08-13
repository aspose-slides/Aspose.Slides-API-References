---
title: IsSuffix()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비교 옵션을 사용하여 지정된 문자열이 지정된 접미사로 끝나는지 확인합니다.
type: docs
weight: 118
url: /ko/system.globalization/compareinfo/issuffix/
---
## CompareInfo::IsSuffix(const String\&, const String\&, CompareOptions) const method


지정된 문자열이 지정된 접미사로 끝나는지 지정된 비교 옵션을 사용하여 확인합니다.

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix, CompareOptions options) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 원본 문자열. |
| suffix | const [String](../../../system/string/)\& | 접미사 문자열. |
| options | [CompareOptions](../../compareoptions/) | 비교 옵션. |

### 반환 값

문자열이 접미사로 끝나면 True, 그렇지 않으면 false.

## CompareInfo::IsSuffix(const String\&, const String\&) const method


지정된 문자열이 지정된 접미사로 끝나는지 확인합니다.

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | 원본 문자열. |
| suffix | const [String](../../../system/string/)\& | 접미사 문자열. |

### 반환 값

문자열이 접미사로 끝나면 True, 그렇지 않으면 false.

## 참고

* 열거형 [CompareOptions](../../compareoptions/)
* 클래스 [String](../../../system/string/)
* 클래스 [CompareInfo](../)
* 네임스페이스 [System::Globalization](../../)
* 라이브러리 [Aspose.Slides](../../../)