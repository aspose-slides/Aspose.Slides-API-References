---
title: Create()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый файл (или перезаписывает существующий) и открывает его для чтения и записи, используя указанный размер буфера и параметры.
type: docs
weight: 53
url: /ru/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) метод

Создаёт новый файл (или перезаписывает существующий) и открывает его для чтения и записи, используя указанный размер буфера и параметры.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, который нужно создать или перезаписать |
| bufferSize | **int32_t** | Количество байтов, буферизуемых при чтении из файла и записи в файл |
| options | [FileOptions](../../fileoptions/) | Определяет, как создавать или перезаписывать файл |

### Возвращаемое значение

Разделяемый указатель на объект [FileStream](../../filestream/), связанный с указанным файлом

## См. также

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)