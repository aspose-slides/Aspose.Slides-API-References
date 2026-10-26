---
title: SetByte()
second_title: Справочник API Aspose.Slides для C++
description: Интерпретирует указанный типизированный массив как массив необработанных байтов и устанавливает заданное значение байта по указанному смещению.
type: docs
weight: 40
url: /ru/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) метод

Интерпретирует указанный типизированный массив как массив необработанных байтов и устанавливает заданное значение байта по указанному смещению.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Целевой массив |
| index | int | Смещение байта, начиная с нуля |
| value | **uint8_t** | Значение байта для установки |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) метод

Интерпретирует указанный типизированный массив как массив необработанных байтов и устанавливает заданное значение байта по указанному смещению.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Целевой массив-вид |
| index | int | Смещение байта, начиная с нуля |
| value | **uint8_t** | Значение байта для установки |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) метод

Интерпретирует указанный типизированный массив как массив необработанных байтов и устанавливает заданное значение байта по указанному смещению.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива |
| N | Размер стекового массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Целевой стековый массив |
| index | int | Смещение байта, начиная с нуля |
| value | **uint8_t** | Значение байта для установки |

## См. также

* Тип [SharedPtr](../../sharedptr/)
* Класс [Array](../../array/)
* Класс [Buffer](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)