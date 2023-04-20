---
title: AddAfter()
second_title: Aspose.Slides for C++ API Reference
description: Adds element after node of the list.
type: docs
weight: 53
url: /cpp/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method


Adds **element** after **node** of the list.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node after which to insert |
| element | const T\& | Element to add |

### Return Value

New node.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method


Adds **newNode** after **node** of the list.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node after which to insert |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | New node to add |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)