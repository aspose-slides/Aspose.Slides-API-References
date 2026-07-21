---
title: Replace()
second_title: Aspose.Slides для C++ Справочник API
description: Заменяет содержимое одного файла другим и создаёт резервную копию заменённого файла.
type: docs
weight: 339
url: /ru/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) метод

Заменяет содержимое одного файла другим и создает резервную копию заменённого файла.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Имя файла, которым следует заменить |
| destinationFileName | const [String](../../../system/string/)\& | Имя файла, который заменяется |
| destinationBackupFileName | const [String](../../../system/string/)\& | Имя резервного файла |
| ignoreMetadataErrors | **bool** | Указывает, следует ли игнорировать ошибки слияния из заменённого файла в файл-замену (true) или нет (false) |

## См. также

* Класс [String](../../../system/string/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)