---
title: IndexOf()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 부분 문자열 앞에서 검색합니다.
type: docs
weight: 625
url: /ko/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const method

부분 문자열을 앞에서 검색합니다.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | 검색할 부분 문자열. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환 값

[Index](../../index/) 첫 번째 발견된 부분 문자열의 인덱스이며, 찾지 못하면 -1을 반환합니다. 빈 검색 문자열인 경우 항상 0을 반환합니다.

## String::IndexOf(char_t, int) const method

문자를 앞에서 검색합니다.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | 검색할 문자. |
| startIndex | int | [Index](../../index/) 시작 검색 위치. |

### 반환 값

[Index](../../index/) startIndex 이후 첫 번째 문자 위치이며, 찾지 못하면 -1입니다.

## String::IndexOf(char_t, int, int) const method

부분 문자열에서 문자를 앞에서 검색합니다.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | 검색할 문자. |
| startIndex | int | [Index](../../index/) 시작 검색 위치. |
| count | int | 검색할 문자 수. |

### 반환 값

[Index](../../index/) startIndex 이후 첫 번째 문자 위치이며, 찾지 못하면 -1입니다.

## String::IndexOf(const String\&, int) const method

부분 문자열을 앞에서 검색합니다.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | 검색할 부분 문자열. |
| startIndex | int | 원본 문자열에서 검색을 시작할 위치. |

### 반환 값

[Index](../../index/) 첫 번째 발견된 부분 문자열의 인덱스이며, 찾지 못하면 -1을 반환합니다. 빈 검색 문자열인 경우 항상 startIndex을 반환합니다.

## String::IndexOf(const String\&, int, System::StringComparison) const method

부분 문자열을 앞에서 검색합니다.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | 검색할 부분 문자열. |
| startIndex | int | 원본 문자열에서 검색을 시작할 위치. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환 값

[Index](../../index/) 첫 번째 발견된 부분 문자열의 인덱스이며, 찾지 못하면 -1을 반환합니다. 빈 검색 문자열인 경우 항상 startIndex을 반환합니다.

## String::IndexOf(const String\&, int, int, System::StringComparison) const method

부분 문자열을 앞에서 검색합니다.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | 검색할 부분 문자열. |
| startIndex | int | 원본 문자열에서 검색을 시작할 위치. |
| count | int | 검색할 문자 수. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) 모드. |

### 반환 값

[Index](../../index/) 첫 번째 발견된 부분 문자열의 인덱스이며, 찾지 못하면 -1을 반환합니다. 빈 검색 문자열인 경우 항상 startIndex을 반환합니다.

## String::IndexOf(const String\&, int, int) const method

부분 문자열을 앞에서 검색합니다.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | 검색할 부분 문자열. |
| startIndex | int | 원본 문자열에서 검색을 시작할 위치. |
| count | int | 검색할 문자 수. |

### 반환 값

[Index](../../index/) 첫 번째 발견된 부분 문자열의 인덱스이며, 찾지 못하면 -1을 반환합니다. 빈 검색 문자열인 경우 항상 startIndex을 반환합니다.

## 관련 내용

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)