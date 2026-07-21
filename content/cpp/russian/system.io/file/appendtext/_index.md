---
title: AppendText()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт объект StreamWriter, который добавляет текст в указанный файл, используя кодировку UTF-8. Если указанный файл не существует, он создаётся.
type: docs
weight: 27
url: /ru/system.io/file/appendtext/
---
## File::AppendText(const String\&) method

Создает объект [StreamWriter](../../streamwriter/), который добавляет текст в указанный файл, используя кодировку UTF-8. Если указанный файл не существует, он создаётся.

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, который нужно открыть или создать |

### Возвращаемое значение

Умный указатель на созданный объект [StreamWriter](../../streamwriter/), связанный с указанным файлом

## См. также

* Typedef [StreamWriterPtr](../../../system/streamwriterptr/)
* Класс [String](../../../system/string/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)