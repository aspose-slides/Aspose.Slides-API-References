---
title: AddAfter()
second_title: Aspose.Slides C++ API 参考
description: 在列表的节点后添加元素。
type: docs
weight: 53
url: /zh/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method

在列表中 **node** 之后添加 **element**。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要在其后插入的节点 |
| element | const T\& | 要添加的元素 |

### 返回值

新节点。

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method

在列表中 **node** 之后添加 **newNode**。

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要在其后插入的节点 |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要添加的新节点 |

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [LinkedListNode](../../linkedlistnode/)
* 类 [LinkedList](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)