---
title: AddBefore()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till element före nod i listan.
type: docs
weight: 66
url: /sv/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) metod

Lägger till **element** före **node** i listan.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nod före vilken som ska infogas |
| element | const T\& | Element att lägga till |

### Returvärde

Ny nod.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) metod

Lägger till **newNode** före **node** i listan.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nod före vilken som ska infogas |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Ny nod att lägga till |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [LinkedListNode](../../linkedlistnode/)
* Klass [LinkedList](../)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)