---
title: AddBefore()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Element vor dem Knoten der Liste hinzu.
type: docs
weight: 66
url: /de/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) Methode


Fügt **element** vor **node** der Liste hinzu.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Knoten, vor dem eingefügt werden soll |
| element | const T\& | Element zum Hinzufügen |

### Rückgabewert

Neuer Knoten.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) Methode


Fügt **newNode** vor **node** der Liste hinzu.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Knoten, vor dem eingefügt werden soll |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Neuer Knoten zum Hinzufügen |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [LinkedListNode](../../linkedlistnode/)
* Klasse [LinkedList](../)
* Namensraum [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)