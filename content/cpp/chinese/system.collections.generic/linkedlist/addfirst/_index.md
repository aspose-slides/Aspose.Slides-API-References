---
title: AddFirst()
second_title: Aspose.Slides C++ API 参考
description: 在列表开头添加元素。
type: docs
weight: 79
url: /zh/system.collections.generic/linkedlist/addfirst/
---
## LinkedList::AddFirst(const T\&) 方法


将 **element** 添加到列表的开头。

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddFirst(const T &element)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | const T\& | Element to add. |

### 返回值

新节点。

## LinkedList::AddFirst(const SharedPtr\<LinkedListNode\<T\>\>\&) 方法


将 **newNode** 添加到列表的开头。

```cpp
void System::Collections::Generic::LinkedList<T>::AddFirst(const SharedPtr<LinkedListNode<T>> &newNode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | New node to add. |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)