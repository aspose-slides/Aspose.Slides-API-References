---
title: AddFirst()
second_title: Aspose.Slides for C++ API 參考
description: 將元素加入列表的開頭。
type: docs
weight: 79
url: /zh-hant/system.collections.generic/linkedlist/addfirst/
---
## LinkedList::AddFirst(const T\&) 方法

將 **element** 加入列表的開頭。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddFirst(const T &element)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| element | const T\& | 要加入的元素。 |

### 返回值

新節點。

## LinkedList::AddFirst(const SharedPtr\<LinkedListNode\<T\>\>\&) 方法

將 **newNode** 加入列表的開頭。

```cpp
void System::Collections::Generic::LinkedList<T>::AddFirst(const SharedPtr<LinkedListNode<T>> &newNode)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要加入的新節點。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)