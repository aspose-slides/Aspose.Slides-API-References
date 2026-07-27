---
title: AddBefore()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona elemento antes do nó da lista.
type: docs
weight: 66
url: /pt/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) método

Adiciona **element** antes de **node** da lista.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nó antes do qual inserir |
| element | const T\& | Elemento a ser adicionado |

### Valor de Retorno

Novo nó.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) método

Adiciona **newNode** antes de **node** da lista.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nó antes do qual inserir |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Novo nó a ser adicionado |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [LinkedListNode](../../linkedlistnode/)
* Classe [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)