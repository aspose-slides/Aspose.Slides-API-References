---
title: Read()
second_title: Aspose.Slides для C++ справка по API
description: Читает указанное количество байтов из базового потока и записывает их в указанный массив байтов.
type: docs
weight: 53
url: /ru/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Читает указанное количество байтов из базового потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который записываются прочитанные байты |
| offset | **int32_t** | Позиция в **buffer**, начинающаяся с 0, с которой начинать запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Читает указанное количество байтов из базового потока и записывает их в указанный массив байтов.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Массив байтов, в который записываются прочитанные байты |
| offset | **int32_t** | Позиция в **buffer**, начинающаяся с 0, с которой начинать запись |
| count | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [BufferedStream](../)
* Пространство имен [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)