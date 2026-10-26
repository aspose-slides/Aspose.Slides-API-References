---
title: Remove()
second_title: Aspose.Slides for C++ API Referenciája
description: Eltávolítja a megadott elem első előfordulását a listából.
type: docs
weight: 196
url: /hu/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) metódus

Eltávolítja a megadott **element** első előfordulását a listából.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | const T\& | Eltávolítandó elem. |

### Visszatérési érték

True, ha a **element** megtalálásra és eltávolításra került, false egyébként.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) metódus

Eltávolítja a csomópontot a listából.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Eltávolítandó Node. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [LinkedList](../)
* Osztály [LinkedListNode](../../linkedlistnode/)
* Névterület [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)