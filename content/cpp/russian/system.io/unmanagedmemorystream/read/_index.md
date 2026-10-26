---
title: Read()
second_title: Справка API Aspose.Slides для C++
description: Читает указанное количество байтов из потока и записывает их в указанный массив байтов.
type: docs
weight: 144
url: /ru/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который записываются прочитанные байты |
| offset | **int32_t** | Нулевая позиция в **buffer**, с которой начинается запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива байтов, в которое записываются прочитанные байты |
| offset | **int32_t** | Нулевая позиция в **buffer**, с которой начинается запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [UnmanagedMemoryStream](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)