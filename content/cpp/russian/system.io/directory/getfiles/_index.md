---
title: GetFiles()
second_title: Aspose.Slides для C++ справочник API
description: Ищет файлы, удовлетворяющие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корневым которым является указанный каталог.
type: docs
weight: 79
url: /ru/system.io/directory/getfiles/
---
## Directory::GetFiles(const String&, const String&, SearchOption) метод

Ищет файлы, соответствующие указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корневым которым является указанный каталог.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Полный или относительный путь к каталогу, в котором производится поиск |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов для поиска |
| searchOption | [SearchOption](../../searchoption/) | Указывает, выполнять ли поиск только в указанном каталоге или во всём дереве каталогов, корнем которого является указанный каталог |

### Возвращаемое значение

Массив полных путей найденных файлов, имена которых соответствуют **searchPattern**

## См. также

* Перечисление [SearchOption](../../searchoption/)
* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [Directory](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)