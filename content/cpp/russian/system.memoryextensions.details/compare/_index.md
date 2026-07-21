---
title: Compare()
second_title: Aspose.Slides для C++ справочник API
description: Сравнивает два умных указателя.
type: docs
weight: 1
url: /ru/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) функция


Сравнивает два умных указателя.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип первого умного указателя |
| U | Тип второго умного указателя |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Первый умный указатель |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Второй умный указатель |

### Возвращаемое значение

[Comparison](../../system/comparison/) результат (0 если равны, -1 если a < b, 1 если a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) функция


Сравнивает два арифметических значения.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Арифметический тип |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const T\& | Первое значение |
| b | const T\& | Второе значение |

### Возвращаемое значение

[Comparison](../../system/comparison/) результат (0 если равны, -1 если a < b, 1 если a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) функция


Сравнивает умный указатель со значением.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, на который указывает умный указатель |
| U | Тип значения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Умный указатель |
| b | const U\& | Значение |

### Возвращаемое значение

[Comparison](../../system/comparison/) результат (0 если равны, -1 если a < b, 1 если a > b)

## См. также

* Типовое определение [SharedPtr](../../system/sharedptr/)
* Пространство имён [System::MemoryExtensions::Details](../)
* Библиотека [Aspose.Slides](../../)