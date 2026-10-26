---
title: FindIndex()
second_title: Справочник API Aspose.Slides для C++
description: Ищет элемент, соответствующий заданному предикату.
type: docs
weight: 404
url: /ru/system.collections.generic/list/findindex/
---
## List::FindIndex(System::Predicate\<T\>) метод

Ищет элемент, соответствующий заданному предикату.

```cpp
int System::Collections::Generic::List<T>::FindIndex(System::Predicate<T> match)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Предикат для проверки элементов. |

### Возвращаемое значение

Индекс найденного элемента или -1, если не найден.

## List::FindIndex(int, System::Predicate\<T\>) метод

Ищет элемент, соответствующий заданному предикату.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, System::Predicate<T> match)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс, с которого начинать поиск. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Предикат для проверки элементов. |

### Возвращаемое значение

Индекс найденного элемента или -1, если не найден.

## List::FindIndex(int, int, System::Predicate\<T\>) метод

Ищет элемент, соответствующий заданному предикату.

```cpp
int System::Collections::Generic::List<T>::FindIndex(int startIndex, int count, System::Predicate<T> match)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс, с которого начинать поиск. |
| count | int | Количество элементов для просмотра. |
| match | [System::Predicate](../../../system/predicate/)\<T\> | Предикат для проверки элементов. |

### Возвращаемое значение

Индекс найденного элемента или -1, если не найден.

## См. также

* Тип [Predicate](../../../system/predicate/)
* Класс [List](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)