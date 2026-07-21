---
title: FileStream()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр класса FileStream и инициализирует его указанными параметрами.
type: docs
weight: 1
url: /ru/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) constructor

Создаёт новый экземпляр класса [FileStream](../) и инициализирует его указанными параметрами.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу для открытия. |
| mode | [FileMode](../../filemode/) | Указывает режим, в котором открывается файл. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) constructor

Создаёт новый экземпляр класса [FileStream](../) и инициализирует его указанными параметрами.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу для открытия. |
| mode | [FileMode](../../filemode/) | Указывает режим, в котором открывается файл. |
| access | [FileAccess](../../fileaccess/) | Запрашиваемый тип доступа. |
| share | [FileShare](../../fileshare/) | Тип доступа, который другие объекты [FileStream](../) имеют к открытому файлу. |
| buffer_size | **int32_t** | Количество байтов, буферизуемых во время операций чтения и записи. |
| options | [FileOptions](../../fileoptions/) | Дополнительные параметры. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) constructor

Создаёт новый экземпляр класса [FileStream](../) и инициализирует его указанными параметрами.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу для открытия. |
| mode | [FileMode](../../filemode/) | Указывает режим, в котором открывается файл. |
| access | [FileAccess](../../fileaccess/) | Запрашиваемый тип доступа. |
| share | [FileShare](../../fileshare/) | Тип доступа, который другие объекты [FileStream](../) имеют к открытому файлу. |
| buffer_size | **int32_t** | Количество байтов, буферизуемых во время операций чтения и записи. |
| useAsync | **bool** | Указывает, использовать ли асинхронный ввод-вывод или синхронный ввод-вывод. |

## Замечания

Операционная система может не поддерживать асинхронный ввод-вывод. 

## FileStream::FileStream(const FileStream\&) constructor

```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## См. также

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Класс [String](../../../system/string/)
* Класс [FileStream](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)