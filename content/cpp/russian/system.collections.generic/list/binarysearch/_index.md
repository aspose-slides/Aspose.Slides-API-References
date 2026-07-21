---
title: BinarySearch()
second_title: Справочник API Aspose.Slides для C++
description: Ищет элемент в отсортированном списке.
type: docs
weight: 339
url: /ru/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const метод

Ищет элемент в отсортированном списке.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const T\& | Элемент для поиска. |

### Возвращаемое значение

Индекс элемента в отсортированном списке или дополнение к ближайшему индексу.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const метод

Ищет элемент в отсортированном списке.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const T\& | Элемент для поиска. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) для использования. |

### Возвращаемое значение

Индекс элемента в отсортированном списке или дополнение к ближайшему индексу.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const метод

Ищет элемент в отсортированном списке.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Начало диапазона. |
| count | int | Размер диапазона. |
| item | const T\& | Элемент для поиска. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) для использования. |

### Возвращаемое значение

Индекс элемента в отсортированном списке или дополнение к ближайшему индексу.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [List](../)
* Класс [IComparer](../../icomparer/)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)