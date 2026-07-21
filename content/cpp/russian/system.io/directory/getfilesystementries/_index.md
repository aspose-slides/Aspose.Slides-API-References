---
title: GetFileSystemEntries()
second_title: Aspose.Slides для C++ справочник API
description: Ищет файлы и каталоги, удовлетворяющие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог.
type: docs
weight: 92
url: /ru/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) метод

Ищет файлы и каталоги, удовлетворяющие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корнем которого является указанный каталог.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Полный или относительный путь к каталогу, в котором производится поиск |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов и каталогов, которые нужно искать |
| searchOption | [SearchOption](../../searchoption/) | Указывает, должен ли поиск выполняться только в указанном каталоге или во всём дереве каталогов, корнем которого является указанный каталог |

### Возвращаемое значение

Массив полных путей найденных файлов и каталогов, имена которых соответствуют **searchPattern**

## См. также

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [Directory](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)