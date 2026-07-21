---
title: Read()
second_title: Aspose.Slides для C++ справочник API
description: Читает один символ из входного потока.
type: docs
weight: 66
url: /ru/system.io/binaryreader/read/
---
## BinaryReader::Read() method

Читает один символ из входного потока.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Return Value

Считанный символ закодирован в кодировке UTF-16; если считанный символ представлен двумя кодовыми точками в кодировке UTF-16, то возвращается только старший surragate.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) method

Читает указанное количество байтов из входного потока и записывает их в указанный массив байтов.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов, в который записываются считанные байты |
| index | int | Позиция в **buffer**, начинающаяся с нуля, в которой следует начать запись |
| count | int | Количество байтов для чтения |

### Return Value

Количество считанных байтов

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) method

Читает указанное количество символов из входного потока, преобразует их в кодировку UTF-16 и записывает полученные символы UTF-16 в указанный массив символов, начиная с указанной позиции.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Массив символов UTF-16, в который записываются символы, считанные из входного потока |
| index | int | Индекс в **buffer**, начинающийся с нуля, с которого следует начать запись |
| count | int | Количество символов для чтения из потока |

### Return Value

Количество символов, считанных из входного потока

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [BinaryReader](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)