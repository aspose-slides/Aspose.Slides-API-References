---
title: SortedSet()
second_title: Aspose.Slides for C++ API 參考手冊
description: 建立空集合。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() 建構子

建立空集合。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) 建構子

建立具有指定容量的空集合。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) 建構子

建立使用指定相等比較器的空集合。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) 物件與 [SortedSet](../) 相關聯。 |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) 建構子

根據可列舉的值建立 [SortedSet](../)。

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [SortedSet](../)
* 類別 [IComparer](../../icomparer/)
* 類別 [IEnumerable](../../ienumerable/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)