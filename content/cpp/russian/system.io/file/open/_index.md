---
title: Open()
second_title: Справочник API Aspose.Slides для C++
description: Открывает указанный файл в указанном режиме для чтения и записи без совместного доступа.
type: docs
weight: 235
url: /ru/system.io/file/open/
---
## File::Open(const String\&, FileMode) метод


Открывает указанный файл в указанном режиме для чтения и записи без совместного доступа.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к открываемому файлу |
| mode | [FileMode](../../filemode/) | Указывает режим, в котором открывается файл |

### Возвращаемое значение

Объект [FileStream](../../filestream/) , связанный с открытым файлом

## File::Open(const String\&, FileMode, FileAccess, FileShare) метод


Открывает указанный файл в указанном режиме, с указанным типом доступа и параметром совместного доступа.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к открываемому файлу |
| mode | [FileMode](../../filemode/) | Указывает режим, в котором открывается файл |
| access | [FileAccess](../../fileaccess/) | Запрашиваемый тип доступа |
| share | [FileShare](../../fileshare/) | Тип доступа, который другие объекты [FileStream](../../filestream/) имеют к открытому файлу |

### Возвращаемое значение

Объект [FileStream](../../filestream/) , связанный с открытым файлом

## См. также

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)