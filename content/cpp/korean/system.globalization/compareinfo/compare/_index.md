---
title: Compare()
second_title: Aspose.Slides for C++ API 참조
description: 문자열을 비교합니다. 구현되지 않음.
type: docs
weight: 66
url: /ko/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const 메서드

문자열을 비교합니다. 구현되지 않음.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 좌변 문자열. |
| string2 | const [String](../../../system/string/)\& | 우변 문자열. |

### 반환값

좌변 문자열이 우변 문자열보다 앞서는 경우 음수, 일치하면 0, 그 외의 경우 양수.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const 메서드

문자열을 비교합니다. Ordinal 및 OrdinalIgnoreCase 모드만 지원됩니다.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | 좌변 문자열. |
| b | const [String](../../../system/string/)\& | 우변 문자열. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 비교 유형. |

### 반환값

좌변 문자열이 우변 문자열보다 앞서는 경우 음수, 일치하면 0, 그 외의 경우 양수.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const 메서드

하나의 문자열 부분을 다른 문자열 부분과 비교합니다. 구현되지 않음.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 첫 번째 문자열. |
| offset1 | int | **string1**에서 문자 시작 인덱스. |
| length1 | int | **string1**에서 비교할 문자 수. |
| string2 | const [String](../../../system/string/)\& | 두 번째 문자열. |
| offset2 | int | **string2**에서 문자 시작 인덱스. |
| length2 | int | **string2**에서 비교할 문자 수. |

### 반환값

첫 번째 문자열 부분이 두 번째 문자열 부분보다 앞서는 경우 음수, 일치하면 0, 그 외의 경우 양수.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const 메서드

하나의 문자열 끝 부분을 다른 문자열 끝 부분과 문자열 비교 메서드를 사용해 비교합니다. 구현되지 않음.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 첫 번째 문자열. |
| offset1 | int | **string1**에서 문자 시작 인덱스. |
| string2 | const [String](../../../system/string/)\& | 두 번째 문자열. |
| offset2 | int | **string2**에서 문자 시작 인덱스. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 비교 옵션. |

### 반환값

첫 번째 문자열 부분이 두 번째 문자열 부분보다 앞서는 경우 음수, 일치하면 0, 그 외의 경우 양수.

## CompareInfo::Compare(const String\&, int, const String\&, int) const 메서드

하나의 문자열 끝 부분을 다른 문자열 끝 부분과 비교합니다. 구현되지 않음.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 첫 번째 문자열. |
| offset1 | int | **string1**에서 문자 시작 인덱스. |
| string2 | const [String](../../../system/string/)\& | 두 번째 문자열. |
| offset2 | int | **string2**에서 문자 시작 인덱스. |

### 반환값

첫 번째 문자열 부분이 두 번째 문자열 부분보다 앞서는 경우 음수, 일치하면 0, 그 외의 경우 양수.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const 메서드

하나의 문자열 부분을 다른 문자열 부분을 문자열 비교 메서드를 사용해 비교합니다. 구현되지 않음.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | 첫 번째 문자열. |
| offset1 | int | **string1**에서 문자 시작 인덱스. |
| length1 | int | **string1**에서 비교할 문자 수. |
| string2 | const [String](../../../system/string/)\& | 두 번째 문자열. |
| offset2 | int | **string2**에서 문자 시작 인덱스. |
| length2 | int | **string2**에서 비교할 문자 수. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 비교 옵션. |

### 반환값

첫 번째 문자열 부분이 두 번째 문자열 부분보다 앞서는 경우 음수, 일치하면 0, 그 외의 경우 양수.

## See Also

* Enum [CompareOptions](../../compareoptions/)
* Class [String](../../../system/string/)
* Class [CompareInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)