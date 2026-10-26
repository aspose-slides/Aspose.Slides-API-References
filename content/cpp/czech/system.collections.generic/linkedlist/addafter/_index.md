---
title: AddAfter()
second_title: Aspose.Slides pro C++ – reference API
description: Přidá prvek za uzel v seznamu.
type: docs
weight: 53
url: /cs/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method

Přidá **prvek** za **uzel** v seznamu.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Uzel, za který vložit |
| element | const T\& | Prvek k přidání |

### Návratová hodnota

Nový uzel.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method

Přidá **newNode** za **node** v seznamu.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Uzel, za který vložit |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nový uzel k přidání |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [LinkedListNode](../../linkedlistnode/)
* Třída [LinkedList](../)
* Obor názvů [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)