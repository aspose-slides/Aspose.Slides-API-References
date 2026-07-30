---
title: AddBefore()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge l'elemento prima del nodo della lista.
type: docs
weight: 66
url: /it/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method


Aggiunge **element** prima di **node** nella lista.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo prima del quale inserire |
| element | const T\& | Elemento da aggiungere |

### Valore di ritorno

Nuovo nodo.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method


Aggiunge **newNode** prima di **node** nella lista.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo prima del quale inserire |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nuovo nodo da aggiungere |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [LinkedListNode](../../linkedlistnode/)
* Classe [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)