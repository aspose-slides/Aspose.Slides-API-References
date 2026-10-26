---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 從列表中移除指定元素的首次出現。
type: docs
weight: 196
url: /zh-hant/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) 方法

從列表中移除指定 **element** 的首次出現。

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| element | const T\& | 要移除的元素。 |

### 回傳值

如果找到並移除 **element** 則返回 true，否則返回 false。

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) 方法

從列表中移除節點。

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要移除的節點。 |

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [LinkedList](../)
* 類別 [LinkedListNode](../../linkedlistnode/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)