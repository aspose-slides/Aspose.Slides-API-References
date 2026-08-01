---
title: AddBefore()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt element toe vóór node van de lijst.
type: docs
weight: 66
url: /nl/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) methode


Voegt **element** toe vóór **node** van de lijst.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node before which to insert |
| element | const T\& | Element to add |

### Retourwaarde

Nieuwe knoop.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) methode


Voegt **newNode** toe vóór **node** van de lijst.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node before which to insert |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | New node to add |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [LinkedListNode](../../linkedlistnode/)
* Klasse [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)