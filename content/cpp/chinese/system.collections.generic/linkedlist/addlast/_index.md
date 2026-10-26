---
title: AddLast()
second_title: Aspose.Slides C++ API 参考
description: 将元素添加到列表的末尾。
type: docs
weight: 92
url: /zh/system.collections.generic/linkedlist/addlast/
---
## LinkedList::AddLast(const T\&) method

将 **element** 添加到列表的末尾。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddLast(const T &element)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | const T\& | 要添加的元素。 |

### 返回值

新节点。

## LinkedList::AddLast(const SharedPtr\<LinkedListNode\<T\>\>\&) method

将 **newNode** 添加到列表的末尾。

```cpp
void System::Collections::Generic::LinkedList<T>::AddLast(const SharedPtr<LinkedListNode<T>> &newNode)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | 要添加的新节点。 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [LinkedListNode](../../linkedlistnode/)
* 类 [LinkedList](../)
* 命名空间 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)