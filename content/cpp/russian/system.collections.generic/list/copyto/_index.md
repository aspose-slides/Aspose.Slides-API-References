---
title: CopyTo()
second_title: Справочник API Aspose.Slides для C++
description: Копирует элементы списка в существующие элементы массива.
type: docs
weight: 209
url: /ru/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) метод

Копирует элементы списка в существующие элементы массива.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Массив назначения. |
| arrayIndex | int | Начальный индекс массива назначения. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) метод

Копирует все элементы в существующие элементы массива.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) для копирования элементов в. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) метод

Копирует элементы, начиная с указанного индекса, в существующие элементы массива.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс, начинающийся с 0, элемента списка, представленного текущим объектом, с которого начинается копирование |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) для копирования элементов в. |
| arrayIndex | int | Начальная позиция в целевом массиве. |
| count | int | Количество элементов для копирования. |

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [List](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)