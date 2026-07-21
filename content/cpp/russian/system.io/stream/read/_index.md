---
title: Read()
second_title: Справочная документация Aspose.Slides для C++ API
description: Считывает указанное количество байтов из потока и записывает их в указанный массив байтов.
type: docs
weight: 27
url: /ru/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод


Считывает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который записываются прочитанные байты |
| offset | **int32_t** | Нулевая позиция в **buffer**, с которой начинать запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод


Считывает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива байтов, в которое записываются прочитанные байты |
| offset | **int32_t** | Нулевая позиция в **buffer**, с которой начинать запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) метод


Считывает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| N | Размер стекового массива |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Стековый массив байтов, в который записываются прочитанные байты |
| offset | **int32_t** | Нулевая позиция в **buffer**, с которой начинать запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## Stream::Read(const System::Span\<uint8_t\>\&) метод


Считывает указанное количество байтов из потока и записывает их в указанный спан байтов.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | Спан байтов, в который записываются прочитанные байты |

### Возвращаемое значение

Количество прочитанных байтов

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Stream](../)
* Класс [Span](../../../system/span/)
* Пространство имен [System::IO](../../)
* Library [Aspose.Slides](../../../)