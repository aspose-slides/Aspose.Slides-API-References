---
title: Remove()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Usuwa pierwsze wystąpienie określonego elementu z listy.
type: docs
weight: 196
url: /pl/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) metoda


Usuwa pierwsze wystąpienie określonego **elementu** z listy.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | const T\& | Element do usunięcia. |

### Wartość zwracana

True, jeśli **element** został znaleziony i usunięty, false w przeciwnym razie.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) metoda


Usuwa węzeł z listy.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Węzeł do usunięcia. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [LinkedList](../)
* Klasa [LinkedListNode](../../linkedlistnode/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)