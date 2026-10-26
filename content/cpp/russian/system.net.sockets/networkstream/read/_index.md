---
title: Read()
second_title: Aspose.Slides для C++ справочник API
description: Читает указанное количество байтов из потока и записывает их в указанный массив байтов.
type: docs
weight: 196
url: /ru/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод

Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который будут записаны прочитанные байты. |
| offset | **int32_t** | Смещение в байтах в указанном массиве. |
| size | **int32_t** | Количество байтов для чтения. |

### Возвращаемое значение

Количество прочитанных байтов.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод

Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива байтов, в которое будут записаны прочитанные байты |
| offset | **int32_t** | Позиция в **buffer**, начинающаяся с 0, с которой начинать запись |
| size | **int32_t** | Количество байтов для чтения |

### Возвращаемое значение

Количество прочитанных байтов

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [NetworkStream](../)
* Пространство имен [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)