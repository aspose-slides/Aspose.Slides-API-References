---
title: AddAfter()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega un elemento después del nodo de la lista.
type: docs
weight: 53
url: /es/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method

Agrega **element** después de **node** de la lista.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo después del cual insertar |
| element | const T\& | Elemento a agregar |

### Valor devuelto

Nuevo nodo.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method

Agrega **newNode** después de **node** de la lista.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo después del cual insertar |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nuevo nodo a agregar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [LinkedListNode](../../linkedlistnode/)
* Clase [LinkedList](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)