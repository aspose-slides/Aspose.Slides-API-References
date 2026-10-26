---
title: AddAfter()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein Element nach dem Knoten der Liste ein.
type: docs
weight: 53
url: /de/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) Methode

Fügt **element** nach **node** in der Liste ein.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Knoten, nach dem eingefügt werden soll |
| element | const T\& | Element zum Hinzufügen |

### Rückgabewert

Neuer Knoten.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) Methode

Fügt **newNode** nach **node** in der Liste ein.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Knoten, nach dem eingefügt werden soll |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Neuen Knoten, der hinzugefügt werden soll |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [LinkedListNode](../../linkedlistnode/)
* Klasse [LinkedList](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)