---
title: EnumerateFiles()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает перечисляемую коллекцию, содержащую все файлы, находящиеся в каталоге, представляемом текущим объектом.
type: docs
weight: 118
url: /ru/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() метод

Возвращает перечисляемую коллекцию, содержащую все файлы, находящиеся в каталоге, представляемом текущим объектом.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) метод

Ищет файлы, соответствующие указанным критериям поиска, в каталоге, представляемом текущим объектом.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов для поиска |

### Возвращаемое значение

Перечисляемая коллекция разделяемых указателей на объекты [FileInfo](../../fileinfo/), представляющих найденные файлы, чьи имена соответствуют **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) метод

Ищет файлы, соответствующие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всем дереве каталогов, корневым элементом которого является каталог, представляемый текущим объектом.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов для поиска |
| searchOption | [SearchOption](../../searchoption/) | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всём дереве каталогов, корневым элементом которого является каталог, представляемый текущим объектом |

### Возвращаемое значение

Перечисляемая коллекция разделяемых указателей на объекты [FileInfo](../../fileinfo/), представляющих найденные файлы, чьи имена соответствуют **searchPattern**

## См. также

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)