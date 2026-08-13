---
title: GetCompareInfo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 문화와 지정된 어셈블리의 문자열 비교 메서드를 사용하여 CompareInfo를 가져옵니다.
type: docs
weight: 183
url: /ko/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) method

지정된 문화와 지정된 어셈블리의 문자열 비교 메서드를 사용하여 [CompareInfo](../)를 가져옵니다.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| culture | int | 문화 식별자 (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | 문자열 비교 메서드를 포함하는 어셈블리. |

### 반환 값

[CompareInfo](../) 객체.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) method

지정된 문화와 지정된 어셈블리의 문자열 비교 메서드를 사용하여 [CompareInfo](../)를 가져옵니다.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 문화 이름. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | 문자열 비교 메서드를 포함하는 어셈블리. |

### 반환 값

[CompareInfo](../) 객체.

## CompareInfo::GetCompareInfo(int) method

지정된 문화와 연관된 [CompareInfo](../)를 가져옵니다.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| culture | int | 문화 식별자 (LCID). |

### 반환 값

[CompareInfo](../) 객체.

## CompareInfo::GetCompareInfo(const String\&) method

지정된 문화와 연관된 [CompareInfo](../)를 가져옵니다.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 문화 이름. |

### 반환 값

[CompareInfo](../) 객체.

## 기타 보기

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Assembly](../../../system.reflection/assembly/)
* Class [CompareInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)