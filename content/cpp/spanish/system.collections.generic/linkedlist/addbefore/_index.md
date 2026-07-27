---
title: AddBefore()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega un elemento antes del nodo de la lista.
type: docs
weight: 66
url: /es/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) método


Agrega **element** antes de **node** de la lista.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo antes del cual insertar |
| element | const T\& | element a agregar |

### Valor de retorno

Nuevo node.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) método


Agrega **newNode** antes de **node** de la lista.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo antes del cual insertar |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nuevo node a agregar |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [LinkedListNode](../../linkedlistnode/)
* Clase [LinkedList](../)
* Espacio de nombres [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)