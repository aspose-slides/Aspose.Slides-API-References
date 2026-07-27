---
title: AddAfter()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona elemento após nó da lista.
type: docs
weight: 53
url: /pt/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) método

Adiciona **element** após **node** da lista.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nó após o qual inserir |
| element | const T\& | Elemento a adicionar |

### Valor de Retorno

Novo nó.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) método

Adiciona **newNode** após **node** da lista.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nó após o qual inserir |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Novo nó a adicionar |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [LinkedListNode](../../linkedlistnode/)
* Classe [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)