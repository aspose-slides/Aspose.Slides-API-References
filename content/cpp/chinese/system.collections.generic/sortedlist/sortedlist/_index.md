---
title: SortedList()
second_title: Aspose.Slides C++ API 参考
description: 构造空列表。
type: docs
weight: 1
url: /zh/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() 构造函数

构造空列表。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) 构造函数

构造空列表。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) to use. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) 构造函数

复制构造函数。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) to copy data from. |

## SortedList::SortedList(const map_t\&) 构造函数

复制构造函数。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | 用于复制数据的 Map。 |

## SortedList::SortedList(int) 构造函数

构造空列表。

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| capacity | int | 要预留的元素数量。 |

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* 类 [SortedList](../)
* 类 [IComparer](../../icomparer/)
* 类 [IDictionary](../../idictionary/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)