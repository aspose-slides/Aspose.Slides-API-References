---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 참조
description: 부분 문자열 역방향 검색.
type: docs
weight: 651
url: /ko/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const method

하위 문자열을 역방향으로 조회합니다.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | 찾고자 하는 하위 문자열. |
| startIndex | int | 조회를 시작할 원본 문자열 내 위치. |

### 반환값

[Index](../../index/) 마지막으로 찾은 하위 문자열이며, 찾지 못하면 -1을 반환합니다. 조회 문자열이 비어있는 경우 항상 문자열 길이를 반환합니다.

## String::LastIndexOf(const String\&, System::StringComparison) const method

하위 문자열을 역방향으로 조회합니다.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | 찾고자 하는 하위 문자열. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환값

[Index](../../index/) 마지막으로 찾은 하위 문자열이며, 찾지 못하면 -1을 반환합니다. 조회 문자열이 비어있는 경우 항상 문자열 길이를 반환합니다.

## String::LastIndexOf(const String\&, int, System::StringComparison) const method

하위 문자열을 역방향으로 조회합니다.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | 찾고자 하는 하위 문자열. |
| startIndex | int | 조회를 시작할 원본 문자열 내 위치. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환값

[Index](../../index/) 마지막으로 찾은 하위 문자열이며, 찾지 못하면 -1을 반환합니다. 조회 문자열이 비어있는 경우 항상 문자열 길이를 반환합니다.

## String::LastIndexOf(const String\&, int, int, StringComparison) const method

하위 문자열을 역방향으로 조회합니다.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../)\& | 찾고자 하는 하위 문자열. |
| startIndex | int | 조회를 시작할 원본 문자열 내 위치. |
| count | int | 검색할 문자 수. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환값

[Index](../../index/) 마지막으로 찾은 하위 문자열이며, 찾지 못하면 -1을 반환합니다. 조회 문자열이 비어있는 경우 항상 startIndex+count를 반환합니다.

## String::LastIndexOf(char_t) const method

문자를 역방향으로 조회합니다.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char_t | 찾고자 하는 문자. |

### 반환값

[Index](../../index/) 마지막 문자 위치이며, 찾지 못하면 -1을 반환합니다.

## String::LastIndexOf(char_t, int32_t) const method

문자를 역방향으로 조회합니다.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char_t | 찾고자 하는 문자. |
| startIndex | **int32_t** | [Index](../../index/) 조회 시작 위치. |

### 반환값

[Index](../../index/) startIndex 이후의 마지막 문자 위치이며, 찾지 못하면 -1을 반환합니다.

## String::LastIndexOf(char_t, int32_t, int32_t) const method

문자를 역방향으로 조회합니다.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | char_t | 찾고자 하는 문자. |
| startIndex | **int32_t** | [Index](../../index/) 조회 시작 위치. |
| count | **int32_t** | 검색할 문자 수 |

### 반환값

[Index](../../index/) startIndex 이후의 마지막 문자 위치이며, 찾지 못하면 -1을 반환합니다.

## 참고

* 열거형 [StringComparison](../../stringcomparison/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)