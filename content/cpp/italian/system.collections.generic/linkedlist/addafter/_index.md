---
title: AddAfter()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge l'elemento dopo il nodo della lista.
type: docs
weight: 53
url: /it/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) metodo

Aggiunge **element** dopo **node** della lista.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo dopo il quale inserire |
| element | const T\& | Elemento da aggiungere |

### Valore di ritorno

Nuovo nodo.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) metodo

Aggiunge **newNode** dopo **node** della lista.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo dopo il quale inserire |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nuovo nodo da aggiungere |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [LinkedListNode](../../linkedlistnode/)
* Classe [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)