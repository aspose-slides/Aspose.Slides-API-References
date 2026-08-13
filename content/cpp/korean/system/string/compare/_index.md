---
title: Compare()
second_title: Aspose.Slides for C++ API 참조
description: 두 부분 문자열을 비교하여 작음·같음·큼을 반환합니다.
type: docs
weight: 820
url: /ko/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) 메서드

두 부분 문자열을 비교하여 작음·같음·큼을 반환합니다.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strA | const [String](../)\& | 비교할 첫 번째 문자열. |
| indexA | int | 첫 번째 문자열 부분 문자열의 시작 위치. |
| strB | const [String](../)\& | 비교할 두 번째 문자열. |
| indexB | int | 두 번째 문자열 부분 문자열의 시작 위치. |
| length | int | 비교할 문자 수. |
| ignoreCase | **bool** | 비교가 대소문자를 구분하지 않는지 지정합니다. |

### 반환값

첫 번째 부분 문자열이 두 번째보다 작으면 음수, 일치하면 0, 그렇지 않으면 양수를 반환합니다.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) 메서드

두 부분 문자열을 비교하여 작음·같음·큼을 반환합니다.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strA | const [String](../)\& | 비교할 첫 번째 문자열. |
| indexA | int | 첫 번째 문자열 부분 문자열의 시작 위치. |
| strB | const [String](../)\& | 비교할 두 번째 문자열. |
| indexB | int | 두 번째 문자열 부분 문자열의 시작 위치. |
| length | int | 비교할 문자 수. |
| ignoreCase | **bool** | 비교가 대소문자를 구분하지 않는지 지정합니다. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 비교에 사용할 문화권. |

### 반환값

첫 번째 부분 문자열이 두 번째보다 작으면 음수, 일치하면 0, 그렇지 않으면 양수를 반환합니다.

## String::Compare(const String\&, const String\&, System::StringComparison) 메서드

두 문자열을 비교하여 작음·같음·큼을 반환합니다.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strA | const [String](../)\& | 비교할 첫 번째 문자열. |
| strB | const [String](../)\& | 비교할 두 번째 문자열. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환값

첫 번째 부분 문자열이 두 번째보다 작으면 음수, 일치하면 0, 그렇지 않으면 양수를 반환합니다.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) 메서드

두 문자열을 비교하여 작음·같음·큼을 반환합니다.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strA | const [String](../)\& | 비교할 첫 번째 문자열. |
| indexA | int | 첫 번째 문자열 부분 문자열의 시작 위치. |
| strB | const [String](../)\& | 비교할 두 번째 문자열. |
| indexB | int | 두 번째 문자열 부분 문자열의 시작 위치. |
| length | int | 비교할 문자 수. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환값

첫 번째 부분 문자열이 두 번째보다 작으면 음수, 일치하면 0, 그렇지 않으면 양수를 반환합니다.

## String::Compare(const String\&, const String\&, bool) 메서드

두 문자열을 비교하여 작음·같음·큼을 반환합니다.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strA | const [String](../)\& | 비교할 첫 번째 문자열. |
| strB | const [String](../)\& | 비교할 두 번째 문자열. |
| ignoreCase | **bool** | 비교가 대소문자를 구분하지 않는지 지정합니다. |

### 반환값

첫 번째 부분 문자열이 두 번째보다 작으면 음수, 일치하면 0, 그렇지 않으면 양수를 반환합니다.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) 메서드

두 문자열을 비교하여 작음·같음·큼을 반환합니다.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strA | const [String](../)\& | 비교할 첫 번째 문자열. |
| strB | const [String](../)\& | 비교할 두 번째 문자열. |
| ignoreCase | **bool** | 비교가 대소문자를 구분하지 않는지 지정합니다. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 비교에 사용할 문화권. |

### 반환값

첫 번째 부분 문자열이 두 번째보다 작으면 음수, 일치하면 0, 그렇지 않으면 양수를 반환합니다.

## 참조

* 열거형 [StringComparison](../../stringcomparison/)
* typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)