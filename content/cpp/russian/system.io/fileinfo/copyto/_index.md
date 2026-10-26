---
title: CopyTo()
second_title: Справочник API Aspose.Slides для C++
description: Копирует файл, представленный текущим объектом, в указанное место. Если файл назначения уже существует, копирование завершается ошибкой.
type: docs
weight: 105
url: /ru/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) метод

Копирует файл, представленный текущим объектом, в указанное место. Если файл назначения уже существует, копирование завершается с ошибкой.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Имя файла назначения |

### Возвращаемое значение

Объект [FileInfo](../), представляющий копию

## FileInfo::CopyTo(const String\&, bool) метод

Копирует файл, представленный текущим объектом, в указанное место. Параметр указывает, следует ли перезаписать существующий файл назначения.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Имя файла назначения |
| overwrite | **bool** | True, если существующий файл назначения должен быть перезаписан; false, если копирование должно завершиться с ошибкой, если файл назначения уже существует |

### Возвращаемое значение

Объект [FileInfo](../), представляющий копию

## См. также

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Класс [String](../../../system/string/)
* Класс [FileInfo](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)