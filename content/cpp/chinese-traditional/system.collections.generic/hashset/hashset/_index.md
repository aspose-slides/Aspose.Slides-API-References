---
title: HashSet()
second_title: Aspose.Slides 的 C++ API 參考
description: RTTI 資訊。
type: docs
weight: 1
url: /zh-hant/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() 建構函式

RTTI 資訊。

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## 備註

建立空集合。

## HashSet::HashSet(int) 建構函式

建立具有指定容量的空集合。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) 建構函式

建立使用指定相等比較器的空集合。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) 用於關聯 hashset 的物件。 |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) 建構函式

建立基於可列舉值的 hashset。

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashSet](../)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)