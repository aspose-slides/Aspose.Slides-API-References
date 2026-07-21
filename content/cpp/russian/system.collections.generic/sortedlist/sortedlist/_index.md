---
title: SortedList()
second_title: Aspose.Slides для C++: справочник API
description: Создает пустой список.
type: docs
weight: 1
url: /ru/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() конструктор

Создаёт пустой список.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) конструктор

Создаёт пустой список.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) для использования. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) конструктор

Конструктор копирования.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) для копирования данных из. |

## SortedList::SortedList(const map_t\&) конструктор

Конструктор копирования.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Карта для копирования данных из. |

## SortedList::SortedList(int) конструктор

Создаёт пустой список.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| capacity | int | Количество элементов для резервирования. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [map_t](../map_t/)
* Класс [SortedList](../)
* Класс [IComparer](../../icomparer/)
* Класс [IDictionary](../../idictionary/)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)