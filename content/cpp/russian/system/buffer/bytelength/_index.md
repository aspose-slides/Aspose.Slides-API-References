---
title: ByteLength()
second_title: Справочник API Aspose.Slides для C++
description: Определяет количество байтов, занятых всеми элементами указанного массива.
type: docs
weight: 14
url: /ru/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) метод


Определяет количество байтов, занятых всеми элементами указанного массива.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Массив |

### Возвращаемое значение

Количество байтов, занятых всеми элементами указанного массива

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) метод


Определяет количество байтов, занятых всеми элементами указанного массива.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов представления массива |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Представление массива |

### Возвращаемое значение

Количество байтов, занятых всеми элементами указанного представления массива

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) метод


Определяет количество байтов, занятых всеми элементами указанного массива.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов стекового массива |
| N | Размер стекового массива |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Стековый массив |

### Возвращаемое значение

Количество байтов, занятых всеми элементами указанного стекового массива

## См. также

* Типовое определение [SharedPtr](../../sharedptr/)
* Класс [Array](../../array/)
* Класс [Buffer](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)