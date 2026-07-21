---
title: Remove()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет первое вхождение указанного элемента из списка.
type: docs
weight: 196
url: /ru/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) метод

Удаляет первое вхождение указанного **элемент** из списка.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | const T\& | Элемент для удаления. |

### Возвращаемое значение

True если **элемент** найден и удалён, иначе false.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) метод

Удаляет узел из списка.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Узел для удаления. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedList](../)
* Class [LinkedListNode](../../linkedlistnode/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)