---
title: Remove()
second_title: Riferimento API Aspose.Slides per C++
description: Rimuove la prima occorrenza dell'elemento specificato dalla lista.
type: docs
weight: 196
url: /it/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) metodo


Rimuove la prima occorrenza dell'**element** specificato dalla lista.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | const T\& | Elemento da rimuovere. |

### Valore di ritorno

True se **element** è stato trovato e rimosso, false altrimenti.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) metodo


Rimuove il nodo dalla lista.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo da rimuovere. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedList](../)
* Class [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)