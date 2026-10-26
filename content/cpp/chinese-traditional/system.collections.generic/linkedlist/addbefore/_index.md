---
title: AddBefore()
second_title: Aspose.Slides C++ API 參考
description: 在列表的節點之前加入元素。
type: docs
weight: 66
url: /zh-hant/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method


在列表的 **node** 之前加入 **element**。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要插入的節點 |
| element | const T\& | 要加入的元素 |

### 返回值

新節點。

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method


在列表的 **node** 之前加入 **newNode**。

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要插入的節點 |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要加入的新節點 |

## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [LinkedListNode](../../linkedlistnode/)
* 類別 [LinkedList](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)