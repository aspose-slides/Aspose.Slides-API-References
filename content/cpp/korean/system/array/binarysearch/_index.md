---
title: BinarySearch()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 정렬된 배열에서 이진 검색을 수행합니다.
type: docs
weight: 612
url: /ko/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) 메서드

정렬된 배열에서 이진 검색을 수행합니다.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | 검색을 수행할 정렬된 배열 |
| item | const T\& | 검색할 항목 |

### 반환값

[Index](../../index/)는 검색된 항목이 있으면 해당 항목을 반환하고, 없으면 음수 정수를 반환합니다. 이 정수는 검색된 항목보다 큰 다음 항목의 인덱스의 비트 보수이거나, 더 큰 항목이 없을 경우 배열의 요소 개수의 비트 보수입니다.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) 메서드

구현되지 않음.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)