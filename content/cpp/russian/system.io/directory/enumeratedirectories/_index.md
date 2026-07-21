---
title: EnumerateDirectories()
second_title: Aspose.Slides для C++ справка API
description: Ищет каталоги, соответствующие указанным критериям поиска, либо в указанном каталоге, либо во всем дереве каталогов, корневым элементом которого является указанный каталог.
type: docs
weight: 27
url: /ru/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String&, const String&, SearchOption) метод

Ищет каталоги, соответствующие указанным критериям поиска, либо в заданном каталоге, либо во всём дереве каталогов, корневым элементом которого является указанный каталог.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Полный или относительный путь к каталогу, в котором выполняется поиск |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени каталогов, которые необходимо найти |
| searchOption | [SearchOption](../../searchoption/) | Указывает, следует ли выполнять поиск только в указанном каталоге или во всём дереве каталогов, корневым элементом которого является указанный каталог |

### Возвращаемое значение

Перечисляемая коллекция полных путей найденных каталогов, имена которых соответствуют **searchPattern**

## Смотрите также

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Класс [String](../../../system/string/)
* Класс [Directory](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)