---
title: Open()
second_title: Справочник API Aspose.Slides для C++
description: Открывает файл, представленный текущим объектом, в указанном режиме для чтения и записи без совместного доступа.
type: docs
weight: 183
url: /ru/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) метод


Открывает файл, представленный текущим объектом, в указанном режиме для чтения и записи без совместного доступа.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Указывает режим, в котором следует открыть файл |

### Return Value

Объект [FileStream](../../filestream/), связанный с файлом, представленным текущим объектом

## FileInfo::Open(FileMode, FileAccess) метод


Открывает файл, представленный текущим объектом, в указанном режиме, с указанным типом доступа и без совместного доступа.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Указывает режим, в котором следует открыть файл |
| access | [FileAccess](../../fileaccess/) | Запрашиваемый тип доступа |

### Return Value

Объект [FileStream](../../filestream/), связанный с файлом, представленным текущим объектом

## FileInfo::Open(FileMode, FileAccess, FileShare) метод


Открывает файл, представленный текущим объектом, в указанном режиме, с указанным типом доступа и параметром совместного доступа.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Указывает режим, в котором следует открыть файл |
| access | [FileAccess](../../fileaccess/) | Запрашиваемый тип доступа |
| share | [FileShare](../../fileshare/) | Тип доступа, который другие объекты [FileStream](../../filestream/) имеют к открытому файлу |

### Return Value

Объект [FileStream](../../filestream/), связанный с файлом, представленным текущим объектом

## See Also

* Перечисление [FileMode](../../filemode/)
* Перечисление [FileAccess](../../fileaccess/)
* Перечисление [FileShare](../../fileshare/)
* Типовое определение [FileStreamPtr](../../../system/filestreamptr/)
* Класс [FileInfo](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)