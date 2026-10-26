---
title: GetByte()
second_title: Aspose.Slides для C++ справочника API
description: Интерпретирует указанный типизированный массив как массив необработанных байтов и получает значение байта по заданному смещению в байтах.
type: docs
weight: 27
url: /ru/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) метод


Интерпретирует указанный типизированный массив как массив необработанных байтов и получает значение байта по заданному смещению в байтах.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | The target array |
| index | int | Zero-based offset of the byte to retrieve |

### Возвращаемое значение

The byte value at the specified index

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) метод


Интерпретирует указанный типизированный массив как массив необработанных байтов и получает значение байта по заданному смещению в байтах.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements of the array view |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | The target array view |
| index | int | Zero-based offset of the byte to retrieve |

### Возвращаемое значение

The byte value at the specified index

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) метод


Интерпретирует указанный типизированный массив как массив необработанных байтов и получает значение байта по заданному смещению в байтах.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | The type of elements of the stack array |
| N | The size of the stack array |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | The target stack array |
| index | int | Zero-based offset of the byte to retrieve |

### Возвращаемое значение

The byte value at the specified index

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)