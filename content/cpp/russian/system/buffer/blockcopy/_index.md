---
title: BlockCopy()
second_title: Справочник API Aspose.Slides для C++
description: Копирует указанное количество байтов из исходного буфера в целевой буфер.
type: docs
weight: 1
url: /ru/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) метод

Копирует указанное количество байтов из исходного буфера в целевой буфер.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const **uint8_t** * | Указатель на исходный буфер |
| srcOffset | int | Смещение в байтах в исходном буфере, с которого начинается копирование |
| dst | **uint8_t** * | Указатель на целевой буфер |
| dstOffset | int | Смещение в байтах в целевом буфере, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) метод

Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSrc | Тип элементов исходного массива |
| TDst | Тип элементов целевого массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Исходный массив |
| srcOffset | int | Смещение в байтах в исходном массиве, с которого начинается копирование |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Целевой массив |
| dstOffset | int | Смещение в байтах в целевом массиве, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) метод

Интерпретирует два указанных массива как массивы необработанных байтов и копирует данные из одного в другой.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Исходный массив |
| srcOffset | int | Смещение в байтах в исходном массиве, с которого начинается копирование |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | Целевой массив |
| dstOffset | int | Смещение в байтах в целевом массиве, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) метод

Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSrc | Тип элементов представления исходного массива |
| TDst | Тип элементов представления целевого массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Исходное представление массива |
| srcOffset | int | Смещение в байтах в исходном представлении массива, с которого начинается копирование |
| dst | const System::Details::ArrayView\<TDst\>\& | Целевое представление массива |
| dstOffset | int | Смещение в байтах в целевом представлении массива, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) метод

Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSrc | Тип элементов исходного массива |
| TDst | Тип элементов целевого представления массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Исходный массив |
| srcOffset | int | Смещение в байтах в исходном массиве, с которого начинается копирование |
| dst | const System::Details::ArrayView\<TDst\>\& | Целевое представление массива |
| dstOffset | int | Смещение в байтах в целевом представлении массива, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) метод

Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSrc | Тип элементов представления исходного массива |
| TDst | Тип элементов целевого массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | Исходное представление массива |
| srcOffset | int | Смещение в байтах в исходном представлении массива, с которого начинается копирование |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Целевой массив |
| dstOffset | int | Смещение в байтах в целевом массиве, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) метод

Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSrc | Тип элементов исходного стекового массива |
| NS | Размер исходного стекового массива |
| TDst | Тип элементов целевого стекового массива |
| ND | Размер целевого стекового массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Исходный стековый массив |
| srcOffset | int | Смещение в байтах в исходном стековом массиве, с которого начинается копирование |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Целевой стековый массив |
| dstOffset | int | Смещение в байтах в целевом стековом массиве, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) метод

Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSrc | Тип элементов исходного массива |
| TDst | Тип элементов целевого стекового массива |
| ND | Размер целевого стекового массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | Исходный массив |
| srcOffset | int | Смещение в байтах в исходном массиве, с которого начинается копирование |
| dst | const System::Details::StackArray\<TDst, ND\>\& | Целевой стековый массив |
| dstOffset | int | Смещение в байтах в целевом стековом массиве, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) метод

Интерпретирует два указанных типизированных массива как массивы необработанных байтов и копирует данные из одного в другой.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TSrc | Тип элементов исходного стекового массива |
| NS | Размер исходного стекового массива |
| TDst | Тип элементов целевого массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | Исходный стековый массив |
| srcOffset | int | Смещение в байтах в исходном стековом массиве, с которого начинается копирование |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | Целевой массив |
| dstOffset | int | Смещение в байтах в целевом массиве, с которого начинать вставку данных |
| count | int | Количество байтов для копирования |

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [Buffer](../)
* Класс [Array](../../array/)
* Класс [ArrayBase](../../arraybase/)
* Пространство имён [System](../../)
* Library [Aspose.Slides](../../../)