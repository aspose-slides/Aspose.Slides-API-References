---
title: AddAfter()
second_title: Aspose.Slides for C++ API-referencia
description: Elemet ad a lista csomópontja után.
type: docs
weight: 53
url: /hu/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) metódus


Az **element**-t a **node** után adja a listához.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Az node csomópont, amely után beilleszthető |
| element | const T\& | A element hozzáadandó elem |

### Visszatérési érték

Új csomópont.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) metódus


Az **newNode**-t a **node** után adja a listához.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Az node csomópont, amely után beilleszthető |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Az newNode új csomópont, amelyet hozzáad |

## Lásd még

* typedef [SharedPtr](../../../system/sharedptr/)
* osztály [LinkedListNode](../../linkedlistnode/)
* osztály [LinkedList](../)
* névtér [System::Collections::Generic](../../)
* könyvtár [Aspose.Slides](../../../)