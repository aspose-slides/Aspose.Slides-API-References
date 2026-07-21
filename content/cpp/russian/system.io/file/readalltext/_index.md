---
title: ReadAllText()
second_title: Aspose.Slides для C++ справка по API
description: Считывает содержимое указанного текстового файла в один объект String, используя указанную кодировку символов.
type: docs
weight: 313
url: /ru/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) метод

Считывает содержимое указанного текстового файла в один объект [String](../../../system/string/), используя указанную кодировку символов.

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, который нужно считать |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка символов, которую следует использовать |

### Возвращаемое значение

Строка, содержащая содержимое указанного файла

## См. также

* Тип [EncodingPtr](../../../system/encodingptr/)
* Класс [String](../../../system/string/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)