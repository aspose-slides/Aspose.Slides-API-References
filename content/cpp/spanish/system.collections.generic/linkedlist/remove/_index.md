---
title: Remove()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina la primera aparición del elemento especificado de la lista.
type: docs
weight: 196
url: /es/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) método

Elimina la primera aparición del **element** especificado de la lista.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | const T\& | Elemento a eliminar. |

### Valor de retorno

Verdadero si el **element** se encontró y eliminó, falso en caso contrario.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) método

Elimina el nodo de la lista.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nodo a eliminar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [LinkedList](../)
* Clase [LinkedListNode](../../linkedlistnode/)
* Espacio de nombres [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)