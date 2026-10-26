---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 전체 문자열을 뒤에서부터 탐색하여 전달된 문자 중 하나를 찾습니다. 마지막 문자열 문자와 anyOf의 모든 문자를 비교한 뒤, 이전 문자와 비교를 계속합니다. 첫 번째 일치 항목의 인덱스를 반환합니다.
type: docs
weight: 664
url: /ko/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const 메서드


전체 문자열을 뒤에서부터 탐색하여 전달된 문자 중 하나를 찾습니다. 마지막 문자열 문자와 anyOf의 모든 문자를 비교한 뒤, 이전 문자와 비교를 계속합니다. 첫 번째 일치 항목의 인덱스를 반환합니다.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 찾고자 하는 문자. 순서는 중요하지 않음. |

### 반환값

[Index](../../index/) 마지막 일치 문자의 인덱스 또는 찾지 못하면 -1.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const 메서드


부분 문자열을 뒤에서부터 탐색하여 전달된 문자 중 하나를 찾습니다. 마지막 문자열 문자와 anyOf의 모든 문자를 비교한 뒤, 이전 문자와 비교를 계속합니다. 첫 번째 일치 항목의 인덱스를 반환합니다.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 찾고자 하는 문자. 순서는 중요하지 않음. |
| startindex | **int32_t** | [Index](../../index/) 탐색을 시작할 위치. |

### 반환값

[Index](../../index/) 마지막 일치 문자의 인덱스 또는 찾지 못하면 -1.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const 메서드


부분 문자열을 뒤에서부터 탐색하여 전달된 문자 중 하나를 찾습니다. 마지막 문자열 문자와 anyOf의 모든 문자를 비교한 뒤, 이전 문자와 비교를 계속합니다. 첫 번째 일치 항목의 인덱스를 반환합니다.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 찾고자 하는 문자. 순서는 중요하지 않음. |
| startindex | **int32_t** | [Index](../../index/) 탐색을 시작할 위치. |
| count | **int32_t** | 탐색할 문자 수. |

### 반환값

[Index](../../index/) 마지막 일치 문자의 인덱스 또는 찾지 못하면 -1.

## 또 보기

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)