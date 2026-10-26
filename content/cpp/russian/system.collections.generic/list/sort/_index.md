---
title: Sort()
second_title: Aspose.Slides для C++ – справка по API
description: Сортирует элементы в списке.
type: docs
weight: 521
url: /ru/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) метод

Сортирует элементы в списке.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Компаратор для использования. |

## List::Sort() метод

Сортирует элементы в списке, используя компаратор по умолчанию.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) метод

Сортирует элементы в части списка.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс начала части. |
| count | int | Размер части. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Компаратор для использования. |

## List::Sort(Comparison\<T\>, bool) метод

Сортирует элементы в списке.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) для использования. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IComparer](../../icomparer/)
* Класс [List](../)
* Класс [Comparison](../../../system/comparison/)
* Пространство имён [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)