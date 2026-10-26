---
title: WriteAllText()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый текстовый файл или перезаписывает существующий и записывает в него содержимое указанной строки, используя указанную кодировку.
type: docs
weight: 469
url: /ru/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) метод

Создаёт новый текстовый файл или перезаписывает существующий и записывает содержимое указанной строки в него, используя указанную кодировку.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Файл, который нужно создать или перезаписать |
| contents | const [String](../../../system/string/)\& | Массив строк |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка символов, которую следует использовать |

## См. также

* typedef [EncodingPtr](../../../system/encodingptr/)
* класс [String](../../../system/string/)
* класс [File](../)
* пространство имён [System::IO](../../)
* библиотека [Aspose.Slides](../../../)