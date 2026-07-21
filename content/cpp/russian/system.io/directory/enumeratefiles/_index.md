---
title: EnumerateFiles()
second_title: Справочник API Aspose.Slides для C++
description: Ищет файлы, которые удовлетворяют указанным критериям поиска, как в указанном каталоге, так и во всём дереве каталогов, корнем которого является указанный каталог.
type: docs
weight: 40
url: /ru/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) метод

Ищет файлы, которые удовлетворяют указанным критериям поиска, как в указанном каталоге, так и во всём дереве каталогов, корнем которого является указанный каталог.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Полный или относительный путь к каталогу, в котором выполняется поиск |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени файлов для поиска |
| searchOption | [SearchOption](../../searchoption/) | Указывает, должен ли поиск выполняться только в указанном каталоге или во всем дереве каталогов, корнем которого является указанный каталог |

### Возвращаемое значение

Перечисляемая коллекция полных путей найденных файлов, имена которых соответствуют **searchPattern**

## См. также

* Перечисление [SearchOption](../../searchoption/)
* Типовое определение [StringEnumerablePtr](../stringenumerableptr/)
* Класс [String](../../../system/string/)
* Класс [Directory](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)