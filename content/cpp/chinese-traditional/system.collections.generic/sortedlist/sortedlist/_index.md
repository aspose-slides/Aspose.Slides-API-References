---
title: SortedList()
second_title: Aspose.Slides for C++ API 參考
description: 建立空列表。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() 建構函式

建立空列表。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) 建構函式

建立空列表。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) 供使用。 |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) 建構函式

複製建構函式。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) 用於複製資料。 |

## SortedList::SortedList(const map_t\&) 建構函式

複製建構函式。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | 要從其複製資料的映射。 |

## SortedList::SortedList(int) 建構函式

建立空列表。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| capacity | int | 預留的元素數量。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* 類別 [SortedList](../)
* 類別 [IComparer](../../icomparer/)
* 類別 [IDictionary](../../idictionary/)
* 命名空間 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)