---
title: Copy()
second_title: Aspose.Slides для C++ справка API
description: Копирует указанный файл в указанное место. Если файл назначения уже существует, параметр указывает, следует ли его перезаписать.
type: docs
weight: 40
url: /ru/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) метод

Копирует указанный файл в указанное место. Если файл назначения уже существует, параметр указывает, следует ли его перезаписать.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Путь к файлу, который будет скопирован |
| destFileName | const [String](../../../system/string/)\& | Путь к новому расположению копируемого файла |
| overwrite | **bool** | True, если существующий файл назначения следует перезаписать, false, если копирование должно завершиться ошибкой, когда файл назначения уже существует |

## Смотрите также

* Класс [String](../../../system/string/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)