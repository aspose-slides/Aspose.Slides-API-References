---
title: Replace()
second_title: Справочник API Aspose.Slides для C++
description: Заменяет содержимое указанного целевого файла файлом, представляемым текущим объектом FileInfo, и создаёт резервную копию заменяемого файла.
type: docs
weight: 131
url: /ru/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) метод


Заменяет содержимое указанного целевого файла файлом, представляемым текущим объектом [FileInfo](../), и создаёт резервную копию заменяемого файла.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Имя файла, который будет заменён |
| destinationBackupFileName | const [String](../../../system/string/)\& | Имя файла резервной копии |

### Возвращаемое значение

Объект FileInfor, представляющий файл, указанный в **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) метод


Заменяет содержимое указанного целевого файла файлом, представляемым текущим объектом [FileInfo](../), и создаёт резервную копию заменяемого файла.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Имя файла, который будет заменён |
| destinationBackupFileName | const [String](../../../system/string/)\& | Имя файла резервной копии |
| ignoreMetadataErrors | **bool** | Указывает, следует ли игнорировать ошибки объединения из заменяемого файла в файл-замену (true) или нет (false) |

### Возвращаемое значение

Объект FileInfor, представляющий файл, указанный в **destinationFileName**

## См. также

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)