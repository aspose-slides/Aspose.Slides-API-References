---
title: Read()
second_title: Aspose.Slides для C++ API
description: Читает один символ из потока.
type: docs
weight: 40
url: /ru/system.io/streamreader/read/
---
## StreamReader::Read() метод

Читает один символ из потока.

```cpp
virtual int System::IO::StreamReader::Read() override
```

### Возвращаемое значение

Считывает символ, закодированный в UTF-16; если читаемый символ представлен двумя кодовыми точками в UTF-16, то возвращается только старший суррогат.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) метод

Считывает указанное количество символов из потока, преобразует их в кодировку UTF-16 и записывает полученные символы UTF-16 в указанный массив символов, начиная с указанной позиции.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Массив символов UTF-16, в который будут записываться символы, считанные из потока |
| index | int | Нулевой индекс в **buffer**, с которого начинать запись |
| count | int | Количество символов, которые нужно считать из потока |

### Возвращаемое значение

Количество символов, считанных из потока

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [StreamReader](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)