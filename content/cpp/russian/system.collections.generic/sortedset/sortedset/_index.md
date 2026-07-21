---
title: SortedSet()
second_title: Справочник API Aspose.Slides for C++
description: Создает пустой набор.
type: docs
weight: 1
url: /ru/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() конструктор

Создает пустой набор.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) конструктор

Создает пустой набор с указанной ёмкостью.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) конструктор

Создает пустой набор, использующий указанный сравниватель равенства.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) объект для связывания с [SortedSet](../). |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) конструктор

Создает [SortedSet](../) на основе перечислимых значений.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [SortedSet](../)
* Класс [IComparer](../../icomparer/)
* Класс [IEnumerable](../../ienumerable/)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)