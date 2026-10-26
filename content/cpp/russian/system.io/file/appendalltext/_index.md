---
title: AppendAllText()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет указанную строку в указанный файл, используя указанную кодировку.
type: docs
weight: 14
url: /ru/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) метод

Добавляет указанную строку в указанный файл, используя указанную кодировку.

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, в который нужно добавить строку |
| contents | const [String](../../../system/string/)\& | Строка, которую нужно записать в файл |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка символов, которую следует использовать |

## См. также

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Класс [String](../../../system/string/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)