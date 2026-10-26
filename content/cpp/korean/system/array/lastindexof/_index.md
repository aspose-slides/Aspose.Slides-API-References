---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시작 인덱스와 범위 내 요소 수에 의해 지정된 배열의 항목 범위에서 지정된 항목이 마지막으로 나타나는 인덱스를 결정합니다.
type: docs
weight: 703
url: /ko/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) 메서드


지정된 시작 인덱스와 범위 내 요소 수에 의해 정의된 배열에서 지정된 항목이 마지막으로 나타나는 위치의 인덱스를 반환합니다.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| ArrayType | 대상 배열의 요소 유형 |
| ValueType | 배열에서 검색할 항목의 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |
| startIndex | int | [Index](../../index/) at which the search is started |
| count | int | Number of elements of the range to search in |

### 반환 값

[Index](../../index/) of the last occurrence of the specified item if the item is found, otherwise -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) 메서드


지정된 인덱스부터 배열에서 지정된 항목이 마지막으로 나타나는 위치의 인덱스를 반환합니다.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| ArrayType | 대상 배열의 요소 유형 |
| ValueType | 배열에서 검색할 항목의 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |
| startIndex | int | [Index](../../index/) at which the search is started |

### 반환 값

[Index](../../index/) of the last occurrence of the specified item if the item is found, otherwise -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) 메서드


배열에서 지정된 항목이 마지막으로 나타나는 위치의 인덱스를 반환합니다.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```


### 템플릿 매개변수

| Parameter | Description |
| --- | --- |
| ArrayType | 대상 배열의 요소 유형 |
| ValueType | 배열에서 검색할 항목의 유형 |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) to search the specified item in |
| value | const [ValueType](../valuetype/)\& | Item index of which is to be determined |

### 반환 값

[Index](../../index/) of the last occurrence of the specified item if the item is found, otherwise -1

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)