---
title: IndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 배열에서 지정된 항목이 처음 나타나는 위치의 인덱스를 결정합니다.
type: docs
weight: 131
url: /ko/system/array/indexof/
---
## Array::IndexOf(const T\&) const 메서드


지정된 항목이 배열에 처음 나타나는 위치의 인덱스를 결정합니다.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const T\& | 인덱스를 결정해야 하는 항목 |

### 반환값

[Index](../../index/) 지정된 항목이 배열에 처음 나타나는 경우의 인덱스, 항목을 찾지 못하면 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) 메서드


배열에서 지정된 항목이 처음 나타나는 위치의 인덱스를 결정합니다.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ArrayType | 대상 배열의 요소 유형 |
| ValueType | 배열에서 검색할 항목의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 지정된 항목을 검색할 대상 |
| value | const [ValueType](../valuetype/)\& | 인덱스를 결정해야 하는 항목 |

### 반환값

[Index](../../index/) 지정된 항목이 배열에 처음 나타나는 경우의 인덱스, 항목을 찾지 못하면 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) 메서드


지정된 인덱스부터 시작하여 배열에서 지정된 항목이 처음 나타나는 위치의 인덱스를 결정합니다.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ArrayType | 대상 배열의 요소 유형 |
| ValueType | 배열에서 검색할 항목의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 지정된 항목을 검색할 대상 |
| value | const [ValueType](../valuetype/)\& | 인덱스를 결정해야 하는 항목 |
| startIndex | int | [Index](../../index/) 검색이 시작되는 인덱스 |

### 반환값

[Index](../../index/) 지정된 항목이 배열에 처음 나타나는 경우의 인덱스, 항목을 찾지 못하면 -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) 메서드


시작 인덱스와 범위 내 요소 수로 지정된 배열 구간에서 지정된 항목이 처음 나타나는 위치의 인덱스를 결정합니다.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| ArrayType | 대상 배열의 요소 유형 |
| ValueType | 배열에서 검색할 항목의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) 지정된 항목을 검색할 대상 |
| value | const [ValueType](../valuetype/)\& | 인덱스를 결정해야 하는 항목 |
| startIndex | int | [Index](../../index/) 검색이 시작되는 인덱스 |
| count | int | 검색할 구간의 요소 수 |

### 반환값

[Index](../../index/) 지정된 항목이 배열에 처음 나타나는 경우의 인덱스, 항목을 찾지 못하면 -1

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)