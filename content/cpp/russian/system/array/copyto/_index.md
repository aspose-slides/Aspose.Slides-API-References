---
title: CopyTo()
second_title: Справочник API Aspose.Slides для C++
description: Копирует все элементы текущего массива в указанный массив назначения. Элементы вставляются в массив назначения, начиная с индекса, указанного аргументом arrayIndex.
type: docs
weight: 118
url: /ru/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) метод

Копирует все элементы текущего массива в указанный массив назначения. Элементы вставляются в массив назначения, начиная с индекса, указанного аргументом arrayIndex.

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | Массив назначения |
| arrayIndex | int | Индекс в массиве назначения, с которого начинается вставка скопированных элементов |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const метод

Копирует все элементы текущего массива в указанный массив назначения. Элементы вставляются в массив назначения, начиная с индекса, указанного аргументом dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| DstType | Тип элементов в массиве назначения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Массив назначения |
| dstIndex | **int64_t** | Индекс в массиве назначения, с которого начинается вставка скопированных элементов |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const метод


Копирует все элементы текущего массива в указанное представление массива-назначения. Элементы вставляются в представление массива-назначения, начиная с индекса, указанного аргументом dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| DstType | Тип элементов в представлении массива-назначения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Представление массива назначения |
| dstIndex | **int64_t** | Индекс в представлении массива назначения, с которого начинается вставка скопированных элементов |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const метод


Копирует заданное количество элементов из текущего массива, начиная с указанной позиции, в указанный массив назначения. Элементы вставляются в массив назначения, начиная с индекса, указанного аргументом dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| DstType | Тип элементов в массиве назначения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Массив назначения |
| srcIndex | **int64_t** | Индекс в исходном массиве, с которого начинается копирование элементов |
| dstIndex | **int64_t** | Индекс в массиве назначения, с которого начинается вставка скопированных элементов |
| count | **int64_t** | Количество копируемых элементов |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const метод


Копирует заданное количество элементов из текущего массива, начиная с указанной позиции, в указанное представление массива-назначения. Элементы вставляются в представление массива-назначения, начиная с индекса, указанного аргументом dstIndex.

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| DstType | Тип элементов в представлении массива-назначения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | Предstavление массива назначения |
| srcIndex | **int64_t** | Индекс в исходном массиве, с которого начинается копирование элементов |
| dstIndex | **int64_t** | Индекс в представлении массива назначения, с которого начинается вставка скопированных элементов |
| count | **int64_t** | Количество копируемых элементов |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)