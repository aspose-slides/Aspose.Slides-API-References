---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает перечисляемую коллекцию, содержащую все файлы и каталоги, находящиеся в каталоге, представляемом текущим объектом.
type: docs
weight: 131
url: /ru/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() метод


Возвращает перечисляемую коллекцию, содержащую все файлы и каталоги, находящиеся в каталоге, представляемом текущим объектом.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) метод


Ищет файлы и каталоги, удовлетворяющие указанным критериям поиска, в каталоге, представляемом текущим объектом.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов и каталогов для поиска |

### Возвращаемое значение

Перечисляемая коллекция разделяемых указателей на объекты [FileSystemInfo](../../filesysteminfo/), представляющих найденные файлы и каталоги, имена которых соответствуют **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) метод


Ищет файлы и каталоги, удовлетворяющие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов и каталогов для поиска |
| searchOption | [SearchOption](../../searchoption/) | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### Возвращаемое значение

Перечисляемая коллекция разделяемых указателей на объекты [FileSystemInfo](../../filesysteminfo/), представляющих найденные файлы и каталоги, имена которых соответствуют **searchPattern**

## См. также

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)