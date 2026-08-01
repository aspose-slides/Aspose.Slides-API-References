---
title: AddAfter()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt element toe na node van de lijst.
type: docs
weight: 53
url: /nl/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) methode

Voegt **element** toe na **node** van de lijst.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node waarna ingevoegd moet worden |
| element | const T\& | Element om toe te voegen |

### Returnwaarde

Nieuwe node.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) methode

Voegt **newNode** toe na **node** van de lijst.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node waarna ingevoegd moet worden |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nieuwe node om toe te voegen |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [LinkedListNode](../../linkedlistnode/)
* Klasse [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)