---
title: ReadLines()
second_title: Справочник API Aspose.Slides для C++
description: Читает содержимое указанного текстового файла построчно, используя заданную кодировку символов, и возвращает перечисляемую коллекцию строк, каждая из которых представляет отдельную строку содержимого файла.
type: docs
weight: 326
url: /ru/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) метод


Читает содержимое указанного текстового файла построчно, используя заданную кодировку символов, и возвращает перечисляемую коллекцию строк, каждая из которых представляет отдельную строку содержимого файла.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу для чтения |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка символов, используемая |

### Возвращаемое значение

Перечисляемая коллекция строк, представляющая содержимое указанного файла

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [EncodingPtr](../../../system/encodingptr/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Класс [String](../../../system/string/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)