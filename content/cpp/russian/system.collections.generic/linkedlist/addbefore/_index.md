---
title: AddBefore()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет элемент перед узлом списка.
type: docs
weight: 66
url: /ru/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) метод

Добавляет **element** перед **node** в списке.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Узел, перед которым вставлять |
| element | const T\& | Элемент для добавления |

### Return Value

Новый узел.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) метод

Добавляет **newNode** перед **node** в списке.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Узел, перед которым вставлять |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Новый узел для добавления |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [LinkedListNode](../../linkedlistnode/)
* Класс [LinkedList](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)