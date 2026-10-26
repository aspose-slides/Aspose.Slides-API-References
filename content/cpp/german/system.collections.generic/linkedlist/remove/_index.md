---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das erste Vorkommen des angegebenen Elements aus der Liste.
type: docs
weight: 196
url: /de/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) Methode


Entfernt das erste Vorkommen des angegebenen **element** aus der Liste.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | const T\& | Element zum Entfernen. |

### Rückgabewert

True, wenn **element** gefunden und entfernt wurde, sonst false.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) Methode


Entfernt den node aus der Liste.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Zu entfernender node. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedList](../)
* Class [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)