---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den första förekomsten av det specificerade elementet från listan.
type: docs
weight: 196
url: /sv/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) metod


Tar bort den första förekomsten av den specificerade **element** från listan.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | const T\& | Element att ta bort. |

### Returvärde

Sant om **element** hittades och togs bort, falskt annars.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) metod


Tar bort nod från listan.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node att ta bort. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedList](../)
* Class [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)