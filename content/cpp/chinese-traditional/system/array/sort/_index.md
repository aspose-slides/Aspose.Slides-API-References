---
title: Sort()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用預設比較器對指定陣列中的元素進行排序。
type: docs
weight: 742
url: /zh-hant/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) 方法

使用預設比較器對指定陣列中的元素進行排序。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 目標陣列 |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) 方法

使用預設比較器對指定陣列中一段範圍的元素進行排序。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 目標陣列 |
| startIndex | int | 表示排序範圍起始位置的索引 |
| count | int | 表示要排序的元素範圍之大小 |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) 方法

使用指定的比較器對指定陣列中的元素進行排序。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | 目標陣列 |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | 用於比較陣列元素的 IComparer<T> 物件 |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) 方法

未實作。

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) 方法

使用指定的比較對指定陣列中的元素進行排序。

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) 方法

對兩個陣列（其中一個包含鍵，另一個包含相應的項目）進行排序，排序依據是鍵陣列的值，該陣列的元素使用 operator< 進行比較。

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TKey | **keys** 陣列中元素的類型 |
| TValue | **items** 陣列中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) 包含鍵值 |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) 包含映射至 **keys** 陣列中鍵值的項目 |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) 方法

對兩個陣列（其中一個包含鍵，另一個包含相應的項目）進行排序，排序依據是鍵陣列的值，該陣列的元素使用預設比較器進行比較。

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| TKey | **keys** 陣列中元素的類型 |
| TValue | **items** 陣列中元素的類型 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) 包含鍵值 |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) 包含映射至 **keys** 陣列中鍵值的項目 |
| index | int | 表示要排序之範圍起始位置的索引 |
| length | int | 表示要排序之範圍內的元素數量 |

## 參見

* 型別別名 [ArrayPtr](../../arrayptr/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 方法 [Type](../../object/type/)
* 類別 [Array](../)
* 類別 [IComparer](../../../system.collections.generic/icomparer/)
* 類別 [Comparison](../../comparison/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)