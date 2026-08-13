---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자 전방 조회.
type: docs
weight: 638
url: /ko/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const 메서드

문자 전방 조회.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| c | char_t | 찾을 문자. |
| startIndex | int | [Index](../../index/) 시작 위치. |

### 반환 값

[Index](../../index/) 시작 인덱스(startIndex) 이후 첫 문자 위치이며, 찾지 못하면 -1을 반환합니다.

## String::IndexOfAny(const String\&, int) const 메서드

결과적으로 이 문자열에서 str의 모든 문자를 찾습니다. 첫 번째 문자를 찾으면 그 위치를 반환하고, 그렇지 않으면 두 번째 문자를 찾아 계속합니다.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 찾을 문자. 문자 순서가 중요합니다. |
| startIndex | int | 조회 시작 위치. |

### 반환 값

[Index](../../index/) 첫 번째 찾은 문자의 위치이며, 찾지 못하면 -1을 반환합니다.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const 메서드

전체 문자열에서 전달된 문자 중 하나를 찾습니다. 첫 번째 문자열 문자를 anyOf의 모든 문자와 비교하고, 두 번째 문자도 동일하게 비교합니다. 대상 문자 중 일치하는 첫 번째 문자의 인덱스를 반환합니다.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 찾을 문자. 순서는 중요하지 않습니다. |

### 반환 값

[Index](../../index/) 일치하는 첫 번째 문자이며, 찾지 못하면 -1을 반환합니다.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const 메서드

부분 문자열에서 전달된 문자 중 하나를 찾습니다. 첫 번째 문자열 문자를 anyOf의 모든 문자와 비교하고, 두 번째 문자도 동일하게 비교합니다. 대상 문자 중 일치하는 첫 번째 문자의 인덱스를 반환합니다.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 찾을 문자. 순서는 중요하지 않습니다. |
| startindex | **int32_t** | [Index](../../index/) 조회 시작 위치. |

### 반환 값

[Index](../../index/) 일치하는 첫 번째 문자이며, 찾지 못하면 -1을 반환합니다.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const 메서드

부분 문자열에서 전달된 문자 중 하나를 찾습니다. 첫 번째 문자열 문자를 anyOf의 모든 문자와 비교하고, 두 번째 문자도 동일하게 비교합니다. 대상 문자 중 일치하는 첫 번째 문자의 인덱스를 반환합니다.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 찾을 문자. 순서는 중요하지 않습니다. |
| startindex | **int32_t** | [Index](../../index/) 조회 시작 위치. |
| count | **int32_t** | 조회할 문자 수. |

### 반환 값

[Index](../../index/) 일치하는 첫 번째 문자이며, 찾지 못하면 -1을 반환합니다.

## 참조

* 타입정의 [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)