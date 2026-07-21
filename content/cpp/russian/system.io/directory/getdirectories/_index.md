---
title: GetDirectories()
second_title: Aspose.Slides для C++ справочник API
description: Ищет каталоги, которые удовлетворяют указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корневым которым является указанный каталог.
type: docs
weight: 66
url: /ru/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) метод


Ищет каталоги, которые удовлетворяют указанным критериям поиска, либо в указанном каталоге, либо во всём дереве каталогов, корневым которым является указанный каталог.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Полный или относительный путь к каталогу, в котором выполняется поиск |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени каталогов, которые нужно найти |
| searchOption | [SearchOption](../../searchoption/) | Указывает, должен ли поиск выполняться только в указанном каталоге или во всём дереве каталогов, корневым которым является указанный каталог |

### Возвращаемое значение

Массив полных путей найденных каталогов, имена которых соответствуют **searchPattern**

## См. также

* Перечисление [SearchOption](../../searchoption/)
* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [Directory](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)