---
title: GetSortKey()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열에 지정된 비교 옵션을 사용하여 SortKey 객체를 가져옵니다.
type: docs
weight: 79
url: /ko/system.globalization/compareinfo/getsortkey/
---
## CompareInfo::GetSortKey(const String\&, CompareOptions) const 메서드

지정된 문자열에 지정된 비교 옵션을 사용하여 [SortKey](../../sortkey/) 객체를 가져옵니다.

```cpp
virtual SortKeyPtr System::Globalization::CompareInfo::GetSortKey(const String &value, CompareOptions options) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 입력 문자열. |
| options | [CompareOptions](../../compareoptions/) | 비교 옵션. |

### 반환 값

[SortKey](../../sortkey/) 객체.

## CompareInfo::GetSortKey(const String\&) const 메서드

지정된 문자열에 대해 [SortKey](../../sortkey/) 객체를 가져옵니다.

```cpp
virtual SortKeyPtr System::Globalization::CompareInfo::GetSortKey(const String &value) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 입력 문자열. |

### 반환 값

[SortKey](../../sortkey/) 객체.

## 참고

* Enum [CompareOptions](../../compareoptions/)
* Typedef [SortKeyPtr](../../sortkeyptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [CompareInfo](../)
* 네임스페이스 [System::Globalization](../../)
* Library [Aspose.Slides](../../../)