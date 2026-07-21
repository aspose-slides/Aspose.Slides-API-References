---
title: Read()
second_title: Справочник API Aspose.Slides для C++
description: Читает один символ из потока.
type: docs
weight: 40
url: /ru/system.io/stringreader/read/
---
## StringReader::Read() метод

Читает один символ из потока.

```cpp
virtual int System::IO::StringReader::Read() override
```

### Возвращаемое значение

Считанный символ или -1, если символ не был считан

## StringReader::Read(ArrayPtr\<char_t\>, int, int) метод

Читает указанное количество символов из потока в указанный массив символов, начиная с указанной позиции.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Массив символов, в который записываются символы, считанные из потока |
| index | int | Нулевой индекс в **buffer**, с которого начинать запись |
| count | int | Количество символов, которое нужно считать из потока |

### Возвращаемое значение

Количество символов, считанных из потока

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [StringReader](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)