---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes first occurance of the specified element from list.
type: docs
weight: 196
url: /system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) method


Removes first occurance of the specified **element** from list.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | const T\& | Element to remove. |

### Return Value

True if **element** was found and removed, false otherwise.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) method


Removes node from list.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node to remove. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedList](../)
* Class [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)