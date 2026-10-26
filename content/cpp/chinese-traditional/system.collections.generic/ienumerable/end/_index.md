---
title: end()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得指向集合最後一個元素之後（如果有）的迭代器。此迭代器無法用來變更所參考的物件，因為 GetEnumerator() 會傳回 T 的副本物件。
type: docs
weight: 391
url: /zh-hant/system.collections.generic/ienumerable/end/
---
## IEnumerable::end() 方法

取得指向集合最後一個元素之後（如果有）的迭代器。此迭代器無法用來變更所參考的物件，因為 [GetEnumerator()](../getenumerator/) 會傳回 T 的副本物件。

```cpp
iterator System::Collections::Generic::IEnumerable<T>::end()
```

### 返回值

An iterator pointing right after the last element (if any) of the collection

## IEnumerable::end() const 方法

取得指向集合之 const 限定實例的最後一個元素之後（如果有）的迭代器。

```cpp
const_iterator System::Collections::Generic::IEnumerable<T>::end() const
```

### 返回值

An iterator pointing right after the last element (if any) of the const-qualified instance of the collection

## 參見

* 類型別名 [iterator](../iterator/)
* 類型別名 [const_iterator](../const_iterator/)
* 類別 [IEnumerable](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)