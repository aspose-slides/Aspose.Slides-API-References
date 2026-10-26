---
title: Read()
second_title: Aspose.Slides для C++: справочник API
description: Читает указанное количество байтов из потока и записывает их в указанный массив байтов.
type: docs
weight: 79
url: /ru/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который записываются прочитанные байты |
| offset | **int32_t** | Позиция с нулевым индексом в **buffer**, с которой начинается запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива байтов, в которое записываются прочитанные байты |
| offset | **int32_t** | Позиция с нулевым индексом в **buffer**, с которой начинается запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [MemoryStream](../)
* Пространство имен [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)