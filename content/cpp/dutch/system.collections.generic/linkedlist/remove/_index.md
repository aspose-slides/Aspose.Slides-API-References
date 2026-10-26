---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de eerste verschijning van het opgegeven element uit de lijst.
type: docs
weight: 196
url: /nl/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) methode

Verwijdert de eerste verschijning van het opgegeven **element** uit de lijst.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| element | const T\& | Element om te verwijderen. |

### Retourwaarde

True als **element** werd gevonden en verwijderd, anders false.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) methode

Verwijdert knoop uit de lijst.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Knoop om te verwijderen. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [LinkedList](../)
* Klasse [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)