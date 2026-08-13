---
title: StartsWith()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열이 지정된 부분 문자열로 시작하는지 확인합니다.
type: docs
weight: 469
url: /ko/system/string/startswith/
---
## String::StartsWith(const String\&) const method

문자열이 지정된 부분 문자열로 시작하는지 확인합니다.

```cpp
bool System::String::StartsWith(const String &value) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../)\& | 검색 문자열. |

### 반환 값

문자열이 지정된 부분 문자열로 시작하면 true, 그렇지 않으면 false.

## String::StartsWith(const String\&, System::StringComparison) const method

문자열이 지정된 부분 문자열로 시작하는지 확인합니다.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../)\& | 검색 문자열. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드, 자세한 내용은 [System::StringComparison](../../stringcomparison/)를 참조하십시오. |

### 반환 값

문자열이 지정된 부분 문자열로 시작하면 true, 그렇지 않으면 false.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method

문자열이 지정된 부분 문자열로 시작하는지 확인합니다.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../)\& | 검색 문자열. |
| ignoreCase | **bool** | 비교가 대소문자를 구분하지 않는지 지정합니다. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 문자열 비교를 수행할 때 사용할 문화권. |

### 반환 값

문자열이 지정된 부분 문자열로 시작하면 true, 그렇지 않으면 false.

## 참조

* 열거형 [StringComparison](../../stringcomparison/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)