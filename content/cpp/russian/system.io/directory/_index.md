---
title: Directory
second_title: Справочник API Aspose.Slides для C++
description: Содержит методы для работы с каталогами. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.
type: docs
weight: 235
url: /ru/system.io/directory/
---
## Directory класс

Содержит методы для работы с каталогами. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.

```cpp
class Directory
```

## Методы

| Метод | Описание |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | Создает все каталоги в указанном пути, если они не существуют. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | Удаляет указанный файл или каталог. Не генерирует исключений. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет каталоги, отвечающие указанным критериям поиска, либо в указанном каталоге, либо во всем дереве каталогов, корень которого — указанный каталог. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет файлы, отвечающие указанным критериям поиска, либо в указанном каталоге, либо во всем дереве каталогов, корень которого — указанный каталог. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет файлы и каталоги, отвечающие указанным критериям поиска, либо в указанном каталоге, либо во всем дереве каталогов, корень которого — указанный каталог. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Определяет, указывает ли указанный путь на существующий каталог. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Возвращает время создания указанного объекта в локальном времени. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Возвращает время создания указанного объекта в UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | Возвращает полное имя (включая путь) текущего каталога. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет каталоги, отвечающие указанным критериям поиска, либо в указанном каталоге, либо во всем дереве каталогов, корень которого — указанный каталог. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | Возвращает корневой каталог указанного пути. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет файлы, отвечающие указанным критериям поиска, либо в указанном каталоге, либо во всем дереве каталогов, корень которого — указанный каталог. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет файлы и каталоги, отвечающие указанным критериям поиска, либо в указанном каталоге, либо во всем дереве каталогов, корень которого — указанный каталог. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Возвращает время последнего доступа к указанному объекту в локальном времени. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Возвращает время последнего доступа к указанному объекту в UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Возвращает время последней записи указанного объекта в локальном времени. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Возвращает время последней записи указанного объекта в UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | НЕ РЕАЛИЗОВАНО. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | Возвращает разделяемый указатель на объект [DirectoryInfo](../directoryinfo/), представляющий родительский каталог указанного объекта. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Перемещает указанный объект в новое место. Если перемещаемый объект является каталогом, он перемещается со всем содержимым. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Устанавливает время создания указанного объекта в локальном времени. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Устанавливает время создания указанного объекта в UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | Устанавливает текущий каталог. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Устанавливает время последнего доступа к указанному объекту в локальном времени. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Устанавливает время последнего доступа к указанному объекту в UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Устанавливает время последней записи указанного объекта в локальном времени. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Устанавливает время последней записи указанного объекта в UTC. |

## Псевдонимы

| Псевдоним | Описание |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | Псевдоним разделяемого указателя на объект IEnumerable, который перечисляет набор объектов [String](../../system/string/). |

## Примечания

```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // Создаёт строки, содержащие пути к каталогам.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // Проверяет, существуют ли каталоги.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // Выводит информацию о временном каталоге.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
Этот пример кода выводит следующее:
Directory 'C:\' существует.
Directory 'C:\Some directory' не существует.
Directory 'C:\Users\lanor\AppData\Local\Temp\' существует.
Время создания: 27.08.2021 14:21:42
Время последнего доступа: 07.10.2021 12:16:41
Время последней записи: 07.10.2021 12:16:41
*/
```

## См. также

* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)