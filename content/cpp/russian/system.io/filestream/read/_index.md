---
title: Read()
second_title: Aspose.Slides для C++ справочник API
description: Считывает указанное количество байтов из потока и записывает их в указанный массив байтов.
type: docs
weight: 183
url: /ru/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) метод


Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив байтов, в который будут записаны прочитанные байты. |
| offset | **int32_t** | Позиция с нулевым основанием в **buffer**, с которой начинать запись. |
| count | **int32_t** | Количество байтов для чтения. |

### Возвращаемое значение

Количество прочитанных байтов.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) метод


Читает указанное количество байтов из потока и записывает их в указанный массив байтов.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Вид массива байтов, в который будут записаны прочитанные байты. |
| offset | **int32_t** | Позиция с нулевым основанием в **buffer**, с которой начинать запись. |
| count | **int32_t** | Количество байтов для чтения. |

### Возвращаемое значение

Количество прочитанных байтов.

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)