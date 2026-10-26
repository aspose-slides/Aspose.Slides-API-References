---
title: BinarySearch()
second_title: Aspose.Slides for C++ API 參考
description: 在已排序的陣列中執行二元搜尋。
type: docs
weight: 612
url: /zh-hant/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) 方法

對已排序的陣列執行二元搜尋。

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | 用於執行搜尋的已排序陣列 |
| item | const T\& | 要搜尋的項目 |

### 返回值

[Index](../../index/) 為搜尋項目的值（如果找到），否則為負整數，該負整數為大於搜尋項目的下一項索引的位元互補，或（若無更大的項目）為陣列元素數量的位元互補。

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) 方法

未實作。

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## 另見

* 型別別名 [ArrayPtr](../../arrayptr/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [Array](../)
* 類別 [IComparer](../../../system.collections.generic/icomparer/)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)