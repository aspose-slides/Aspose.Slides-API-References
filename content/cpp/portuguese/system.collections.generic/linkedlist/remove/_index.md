---
title: Remove()
second_title: Aspose.Slides para C++ Referência da API
description: Remove a primeira ocorrência do elemento especificado da lista.
type: docs
weight: 196
url: /pt/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) método


Remove a primeira ocorrência do **element** especificado da lista.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | const T\& | Elemento a ser removido. |

### Valor de retorno

True se **element** foi encontrado e removido, false caso contrário.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) método


Remove o nó da lista.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nó a ser removido. |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [LinkedList](../)
* Classe [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)