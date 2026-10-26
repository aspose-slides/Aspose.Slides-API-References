---
title: GetFiles()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает массив, содержащий shared pointers к объектам FileInfo, представляющим все каталоги, расположенные в каталоге, представляемом текущим объектом.
type: docs
weight: 157
url: /ru/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() метод


Возвращает массив, содержащий shared pointers к объектам [FileInfo](../../fileinfo/), представляющим все каталоги, расположенные в каталоге, представляемом текущим объектом.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) метод


Ищет файлы, удовлетворяющие указанным критериям поиска, в каталоге, представляемом текущим объектом.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов для поиска |

### Возвращаемое значение

Массив shared pointers к объектам [FileInfo](../../fileinfo/), представляющим найденные файлы, имена которых соответствуют **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) метод


Ищет файлы, удовлетворяющие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов для поиска |
| searchOption | [SearchOption](../../searchoption/) | Указывает, нужно ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### Возвращаемое значение

Массив shared pointers к объектам [FileInfo](../../fileinfo/), представляющим найденные файлы, имена которых соответствуют **searchPattern**

## См. также

* Перечисление [SearchOption](../../searchoption/)
* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Типовое определение [FileInfoPtr](../../../system/fileinfoptr/)
* Класс [DirectoryInfo](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)