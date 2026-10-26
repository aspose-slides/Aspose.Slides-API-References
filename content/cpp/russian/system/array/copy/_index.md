---
title: Copy()
second_title: Справочник API Aspose.Slides для C++
description: Копирует указанное количество элементов из исходного массива в массив назначения.
type: docs
weight: 729
url: /ru/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) метод


Копирует указанное количество элементов из исходного массива в массив назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Исходный массив |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Массив назначения |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) метод


Копирует указанное количество элементов из исходного массива представления в массив назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Исходный массив представления |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Массив назначения |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) метод


Копирует указанное количество элементов из исходного массива в массив назначения представления.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Исходный массив |
| dstArray | System::Details::ArrayView\<DstType\> | Массив назначения представления |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) метод


Копирует указанное количество элементов из исходного массива представления в массив назначения представления.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Исходный массив представления |
| dstArray | System::Details::ArrayView\<DstType\> | Массив назначения представления |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) метод


Копирует указанное количество элементов из исходного массива в стеке в массив назначения.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Исходный массив в стеке |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Массив назначения |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) метод


Копирует указанное количество элементов из исходного массива в массив назначения в стеке.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Исходный массив |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Массив назначения в стеке |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) метод


Копирует указанное количество элементов из исходного массива в стеке в массив назначения в стеке.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Исходный массив в стеке |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Массив назначения в стеке |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) метод


Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию массива назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве |
| DstType | Тип элементов в массиве назначения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Исходный массив |
| srcIndex | **int64_t** | Индекс в исходном массиве, обозначающий начало диапазона элементов для копирования |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Массив назначения |
| dstIndex | **int64_t** | Индекс в массиве назначения, с которого начинать вставку скопированных элементов |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) метод


Копирует указанное количество элементов из исходного массива представления, начиная с указанного индекса, в указанную позицию массива назначения.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве представления |
| DstType | Тип элементов в массиве назначения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Исходный массив представления |
| srcIndex | **int64_t** | Индекс в исходном массиве представления, обозначающий начало диапазона элементов для копирования |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Массив назначения |
| dstIndex | **int64_t** | Индекс в массиве назначения, с которого начинать вставку скопированных элементов |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) метод


Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию массива назначения представления.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве |
| DstType | Тип элементов в массиве назначения представления |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Исходный массив |
| srcIndex | **int64_t** | Индекс в исходном массиве, обозначающий начало диапазона элементов для копирования |
| dstArray | System::Details::ArrayView\<DstType\> | Массив назначения представления |
| dstIndex | **int64_t** | Индекс в массиве назначения представления, с которого начинать вставку скопированных элементов |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) метод


Копирует указанное количество элементов из исходного массива представления, начиная с указанного индекса, в указанную позицию массива назначения представления.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве представления |
| DstType | Тип элементов в массиве назначения представления |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | Исходный массив представления |
| srcIndex | **int64_t** | Индекс в исходном массиве представления, обозначающий начало диапазона элементов для копирования |
| dstArray | System::Details::ArrayView\<DstType\> | Массив назначения представления |
| dstIndex | **int64_t** | Индекс в массиве назначения представления, с которого начинать вставку скопированных элементов |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) метод


Копирует указанное количество элементов из исходного массива в стеке, начиная с указанного индекса, в указанную позицию массива назначения.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве в стеке |
| DstType | Тип элементов в массиве назначения |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | Исходный массив в стеке |
| srcIndex | **int64_t** | Индекс в исходном массиве в стеке, обозначающий начало диапазона элементов для копирования |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Массив назначения |
| dstIndex | **int64_t** | Индекс в массиве назначения, с которого начинать вставку скопированных элементов |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) метод


Копирует указанное количество элементов из исходного массива, начиная с указанного индекса, в указанную позицию массива назначения в стеке.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве |
| DstType | Тип элементов в массиве назначения в стеке |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Исходный массив |
| srcIndex | **int64_t** | Индекс в исходном массиве, обозначающий начало диапазона элементов для копирования |
| dstArray | System::Details::StackArray\<DstType, N\>\& | Массив назначения в стеке |
| dstIndex | **int64_t** | Индекс в массиве назначения в стеке, с которого начинать вставку скопированных элементов |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) метод


Копирует указанное количество элементов из исходного массива в стеке, начиная с указанного индекса, в указанную позицию массива назначения в стеке.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве в стеке |
| DstType | Тип элементов в массиве назначения в стеке |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | Исходный массив в стеке |
| srcIndex | **int64_t** | Индекс в исходном массиве в стеке, обозначающий начало диапазона элементов для копирования |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Массив назначения в стеке |
| dstIndex | **int64_t** | Индекс в массиве назначения в стеке, с которого начинать вставку скопированных элементов |
| count | **int64_t** | Количество элементов для копирования |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) метод


Копирует указанное количество элементов из исходного массива представления, начиная с указанного индекса, в указанную позицию массива назначения в стеке.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Тип элементов в исходном массиве представления |
| DstType | Тип элементов в массиве назначения в стеке |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | Исходный массив представления |
| srcIndex | **int64_t** | Индекс в исходном массиве представления, обозначающий начало диапазона элементов для копирования |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | Массив назначения в стеке |
| dstIndex | **int64_t** | Индекс в массиве назначения в стеке, с которого начинать вставку скопированных элементов |
| count | **int64_t** | Количество элементов для копирования |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)