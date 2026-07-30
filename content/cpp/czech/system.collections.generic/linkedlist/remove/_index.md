---
title: Remove()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje první výskyt zadaného elementu ze seznamu.
type: docs
weight: 196
url: /cs/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) metoda


Odstraní první výskyt zadaného **elementu** ze seznamu.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | const T\& | Element k odstranění. |

### Návratová hodnota

True pokud byl **element** nalezen a odstraněn, false jinak.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) metoda


Odstraní uzel ze seznamu.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Uzel k odstranění. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [LinkedList](../)
* třída [LinkedListNode](../../linkedlistnode/)
* jmenný prostor [System::Collections::Generic](../../)
* knihovna [Aspose.Slides](../../../)