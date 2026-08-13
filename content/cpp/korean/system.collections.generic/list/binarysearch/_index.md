---
title: BinarySearch()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 정렬된 리스트에서 항목을 찾습니다.
type: docs
weight: 339
url: /ko/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const 메서드


정렬된 리스트에서 항목을 찾습니다.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const T\& | 찾을 항목. |

### 반환 값

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const 메서드


정렬된 리스트에서 항목을 찾습니다.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| item | const T\& | 찾을 항목. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) to use. |

### 반환 값

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const 메서드


정렬된 리스트에서 항목을 찾습니다.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) 시작 지점. |
| count | int | [Range](../../../system/range/) 크기. |
| item | const T\& | 찾을 항목. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) to use. |

### 반환 값

[Index](../../../system/index/) of the item in sorted list or complement of closest index.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [List](../)
* 클래스 [IComparer](../../icomparer/)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)