---
title: AddAfter()
second_title: Aspose.Slides для C++ справочника API
description: Добавляет элемент после узла списка.
type: docs
weight: 53
url: /ru/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) метод


Добавляет **элемент** после **узла** в список.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Узел, после которого вставлять |
| element | const T\& | Добавляемый элемент |

### Возвращаемое значение

Новый узел.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) метод


Добавляет **newNode** после **node** в список.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Узел, после которого вставлять |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Новый узел для добавления |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [LinkedListNode](../../linkedlistnode/)
* Класс [LinkedList](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)