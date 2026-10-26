---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides для C++ справка по API
description: Ищет файлы и каталоги, соответствующие указанным критериям поиска, либо в заданном каталоге, либо во всём дереве каталогов, корневым элементом которого является указанный каталог.
type: docs
weight: 53
url: /ru/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) метод

Ищет файлы и каталоги, соответствующие указанным критериям поиска, либо в заданном каталоге, либо во всём дереве каталогов, корневым элементом которого является указанный каталог.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Полный или относительный путь к каталогу, в котором выполняется поиск |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов и каталогов, которые нужно искать |
| searchOption | [SearchOption](../../searchoption/) | Указывает, выполнить ли поиск только в указанном каталоге или во всём дереве каталогов, корневым элементом которого является указанный каталог |

### Возвращаемое значение

Перечисляемая коллекция полных путей найденных файлов и каталогов, имена которых соответствуют **searchPattern**

## См. также

* Перечисление [SearchOption](../../searchoption/)
* Тип [StringEnumerablePtr](../stringenumerableptr/)
* Класс [String](../../../system/string/)
* Класс [Directory](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)