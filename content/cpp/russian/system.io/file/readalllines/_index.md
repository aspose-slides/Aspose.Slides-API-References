---
title: ReadAllLines()
second_title: Справочник API Aspose.Slides для C++
description: Читает содержимое указанного текстового файла построчно в массив строк, используя указанную кодировку символов.
type: docs
weight: 300
url: /ru/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) метод

Читает содержимое указанного текстового файла построчно в массив строк, используя указанную кодировку символов.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу для чтения |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка символов, которая будет использоваться |

### Возвращаемое значение

Массив строк, каждый элемент которого представляет отдельную строку из указанного файла

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Класс [String](../../../system/string/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)