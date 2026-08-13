---
title: EndsWith()
second_title: Aspose.Slides for C++ API 참조
description: 문자열이 지정된 하위 문자열로 끝나는지 확인합니다.
type: docs
weight: 482
url: /ko/system/string/endswith/
---
## String::EndsWith(const String\&) const method

지정된 하위 문자열로 문자열이 끝나는지 확인합니다.

```cpp
bool System::String::EndsWith(const String &value) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../)\& | 검색 문자열. |

### 반환값

문자열이 지정된 하위 문자열로 끝나면 true, 그렇지 않으면 false.

## String::EndsWith(const String\&, System::StringComparison) const method

지정된 하위 문자열로 문자열이 끝나는지 확인합니다.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../)\& | 검색 문자열. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드, 자세한 내용은 [System::StringComparison](../../stringcomparison/)를 참조하십시오. |

### 반환값

문자열이 지정된 하위 문자열로 끝나면 true, 그렇지 않으면 false.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

지정된 하위 문자열로 문자열이 끝나는지 확인합니다.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../)\& | 검색 문자열. |
| ignoreCase | **bool** | 비교가 대소문자를 구분하지 않는지 지정합니다. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 문자열 비교를 수행할 때 사용할 문화 정보. |

### 반환값

문자열이 지정된 하위 문자열로 끝나면 true, 그렇지 않으면 false.

## 참조

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)