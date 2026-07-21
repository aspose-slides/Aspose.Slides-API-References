---
title: Sort()
second_title: Aspose.Slides для C++ справочник API
description: Сортирует Span, используя пользовательский сравниватель.
type: docs
weight: 339
url: /ru/system.memoryextensions/sort/
---
## System::MemoryExtensions::Sort(const Span\<T\>\&, const SharedPtr\<TComparer\>\&) функция


Сортирует [Span](../../system/span/) с использованием пользовательского сравнивателя.

```cpp
template<typename T,typename TComparer> void System::MemoryExtensions::Sort(const Span<T> &span, const SharedPtr<TComparer> &comparer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |
| TComparer | Тип объекта сравнивателя |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Span для сортировки |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Умный указатель на объект сравнивателя для сравнения элементов |

## System::MemoryExtensions::Sort(Span\<T\>\&) функция


Сортирует [Span](../../system/span/) с использованием сравнения по умолчанию.

```cpp
template<typename T> void System::MemoryExtensions::Sort(Span<T> &span)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span для сортировки |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, const SharedPtr\<TComparer\>\&) функция


Сортирует пары ключ-значение с использованием пользовательского сравнивателя (ключи и значения сортируются совместно)

```cpp
template<typename TKey,typename TValue,typename TComparer> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, const SharedPtr<TComparer> &comparer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключей |
| TValue | Тип значений |
| TComparer | Тип объекта сравнивателя |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Span ключей для сортировки |
| values | [Span](../../system/span/)\<TValue\>\& | Span значений для сортировки (с сохранением соответствия с ключами) |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | Умный указатель на объект сравнивателя для сравнения ключей |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&, System::Comparison\<TKey\>) функция


Сортирует пары ключ-значение с использованием делегата сравнения.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values, System::Comparison<TKey> comparer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключей |
| TValue | Тип значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Span ключей для сортировки |
| values | [Span](../../system/span/)\<TValue\>\& | Span значений для сортировки |
| comparer | [System::Comparison](../../system/comparison/)\<TKey\> | [Comparison](../../system/comparison/) делегат для сравнения ключей |

## System::MemoryExtensions::Sort(Span\<TKey\>\&, Span\<TValue\>\&) функция


Сортирует пары ключ-значение с использованием сравнения по умолчанию.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Sort(Span<TKey> &keys, Span<TValue> &values)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключей |
| TValue | Тип значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Span ключей для сортировки |
| values | [Span](../../system/span/)\<TValue\>\& | Span значений для сортировки |

## См. также

* Тип определения [SharedPtr](../../system/sharedptr/)
* Класс [Span](../../system/span/)
* Класс [Comparison](../../system/comparison/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)