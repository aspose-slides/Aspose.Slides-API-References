---
title: ReadBlock()
second_title: Справочник API Aspose.Slides для C++
description: Считывает указанное максимальное количество символов из текущего текстового считывателя и записывает данные в буфер, начиная с указанного индекса.
type: docs
weight: 53
url: /ru/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) метод

Считывает указанное максимальное количество символов из текущего текстового считывателя и записывает данные в буфер, начиная с указанного индекса.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов для записи прочитанных данных |
| index | int | Индекс, начинающийся с 0, в **buffer**, с которого начинать запись |
| count | int | Максимальное количество символов для чтения |

### Возвращаемое значение

Фактическое количество прочитанных символов

## Смотрите также

* Определение типа [ArrayPtr](../../../system/arrayptr/)
* Класс [TextReader](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)