---
title: Equals()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 문자열 동등 비교. StringComparison 열거형에서 제공하는 여러 모드가 지원됩니다.
type: docs
weight: 391
url: /ko/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const 메서드

[String](../) 동등 비교. StringComparison 열거형에서 제공하는 여러 모드가 지원됩니다.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 현재 문자열과 비교하기 위해. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드 (자세한 내용은 [System::StringComparison](../../stringcomparison/)를 참조). |

### 반환값

선택된 비교 유형을 사용하여 문자열이 일치하면 true, 그렇지 않으면 false.

## String::Equals(const String\&) const 메서드

[String](../) 동등 비교. [System::StringComparison::Ordinal](../../stringcomparison/) 비교 모드를 사용합니다.

```cpp
bool System::String::Equals(const String &str) const
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 현재 문자열과 비교하기 위해. |

### 반환값

선택된 비교 유형을 사용하여 문자열이 일치하면 true, 그렇지 않으면 false.

## String::Equals(const String\&, const String\&) 메서드

Ordinal 비교 모드를 사용하여 두 문자열을 동등 비교합니다.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strA | const [String](../)\& | 비교할 첫 번째 문자열. |
| strB | const [String](../)\& | 비교할 두 번째 문자열. |

### 반환값

두 문자열이 일치하면 true, 그렇지 않으면 false.

## String::Equals(const String\&, const String\&, System::StringComparison) 메서드

두 문자열을 동등 비교합니다.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| strA | const [String](../)\& | 비교할 첫 번째 문자열. |
| strB | const [String](../)\& | 비교할 두 번째 문자열. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환값

두 문자열이 일치하면 true, 그렇지 않으면 false.

## 참조

* 열거형 [StringComparison](../../stringcomparison/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)