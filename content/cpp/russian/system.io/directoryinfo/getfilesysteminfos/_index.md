---
title: GetFileSystemInfos()
second_title: Aspose.Slides для C++ API Справочник
description: Возвращает массив, содержащий shared pointers к объектам FileSystemInfo, представляющим все файлы и каталоги, находящиеся в каталоге, представляемом текущим объектом.
type: docs
weight: 170
url: /ru/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() метод


Возвращает массив, содержащий shared pointers к объектам [FileSystemInfo](../../filesysteminfo/), представляющим все файлы и каталоги, находящиеся в каталоге, представляемом текущим объектом.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) метод


Ищет файлы и каталоги, удовлетворяющие заданному критерию поиска, в каталоге, представляемом текущим объектом.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов и каталогов для поиска |

### Возвращаемое значение

Массив shared pointers к объектам [FileSystemInfo](../../filesysteminfo/), представляющим найденные файлы и каталоги, имена которых соответствуют **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) метод


Ищет файлы и каталоги, удовлетворяющие заданному критерию поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов и каталогов для поиска |
| searchOption | [SearchOption](../../searchoption/) | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### Возвращаемое значение

Массив shared pointers к объектам [FileSystemInfo](../../filesysteminfo/), представляющим найденные файлы и каталоги, имена которых соответствуют **searchPattern**

## Смотрите также

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Класс [DirectoryInfo](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)