---
title: Sort()
second_title: C++용 Aspose.Slides API 참조
description: 지정된 배열의 요소를 기본 비교자를 사용하여 정렬합니다.
type: docs
weight: 742
url: /ko/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) 메서드

지정된 배열의 요소를 기본 비교자를 사용하여 정렬합니다.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 대상 배열 |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) 메서드

지정된 배열의 요소 범위를 기본 비교자를 사용하여 정렬합니다.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 대상 배열 |
| startIndex | int | 정렬할 요소 범위의 시작을 지정하는 인덱스 |
| count | int | 정렬할 요소 범위의 크기 |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) 메서드

지정된 배열의 요소를 지정된 비교자를 사용하여 정렬합니다.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 대상 배열 |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | 배열 요소를 비교하는 데 사용되는 IComparer<T> 객체 |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) 메서드

구현되지 않음.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) 메서드

지정된 배열의 요소를 지정된 비교를 사용하여 정렬합니다.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) 메서드

키를 포함하는 배열 하나와 해당 항목을 포함하는 다른 배열 두 개를 키 배열의 값에 따라 정렬하며, 해당 요소는 operator< 로 비교됩니다.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | **keys** 배열에 있는 요소의 형식 |
| TValue | **items** 배열에 있는 요소의 형식 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) 키 값을 포함하는 |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) **keys** 배열의 키 값에 매핑된 항목을 포함하는 |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) 메서드

키를 포함하는 배열 하나와 해당 항목을 포함하는 다른 배열 두 개를 키 배열의 값에 따라 정렬하며, 해당 요소는 기본 비교자를 사용하여 비교됩니다.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | **keys** 배열에 있는 요소의 형식 |
| TValue | **items** 배열에 있는 요소의 형식 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) 키 값을 포함하는 |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) **keys** 배열의 키 값에 매핑된 항목을 포함하는 |
| index | int | 정렬할 범위의 시작 인덱스 |
| length | int | 정렬할 범위의 요소 개수 |

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Comparison](../../comparison/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)