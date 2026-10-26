---
title: OpenText()
second_title: Справочник API Aspose.Slides для C++
description: Открывает указанный существующий файл для чтения текста с использованием кодировки UTF-8 без совместного доступа.
type: docs
weight: 261
url: /ru/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) метод


Открывает указанный существующий файл для чтения текста с использованием кодировки UTF-8 без совместного доступа.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, который нужно открыть |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка символов, которую следует использовать |

### Возвращаемое значение

Указатель std::shared_ptr на объект [StreamWriter](../../streamwriter/), связанный с открытым файлом

## См. также

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Класс [String](../../../system/string/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)