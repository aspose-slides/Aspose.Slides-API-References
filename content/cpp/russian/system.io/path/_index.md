---
title: Path
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет методы для работы с путями. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры никакими средствами.
type: docs
weight: 339
url: /ru/system.io/path/
---
## Класс Path


Предоставляет методы для управления путями. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры никакими средствами.

```cpp
class Path
```

## Методы

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Изменяет расширение в указанном пути к файлу. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Определяет, является ли указанный путь корректным, проверяя наличие недопустимых символов. Исключение выбрасывается, если путь содержит недопустимые символы. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Объединяет указанные сегменты пути в один путь, при необходимости вставляя символы-разделители каталогов между сегментами. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Объединяет два указанных сегмента пути в один путь, при необходимости вставляя символ разделителя каталогов между сегментами. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Объединяет три указанных сегмента пути в один путь, при необходимости вставляя символы-разделители каталогов между сегментами. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Объединяет четыре указанных сегмента пути в один путь, при необходимости вставляя символы-разделители каталогов между сегментами. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | Возвращает имя каталога, на который указывает указанный путь. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | Возвращает расширение файла, на который указывает указанный путь. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | Возвращает имя файла, на который указывает указанный путь. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | Возвращает имя без расширения файла, на который указывает указанный путь. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | Преобразует указанный путь в абсолютный путь. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | Возвращает массив, содержащий символы, недопустимые в именах файлов. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | Возвращает массив, содержащий символы, недопустимые в именах путей. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | Возвращает корневой каталог указанного пути. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | Возвращает случайно сгенерированное имя файла. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | Создаёт новый файл с уникальным именем и возвращает полный путь к нему. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | Создаёт новый файл с уникальным именем и возвращает полный путь к нему. Является синонимом метода [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | Возвращает путь к временной директории текущего пользователя. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | Определяет, указывает ли указанный путь на файл с расширением. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | Определяет, содержит ли указанный путь корень. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | Нормализует указанный путь. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | Возвращает экземпляр класса boost::filesystem::path, представляющий указанный путь. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | Возвращает строковое представление указанного объекта пути Boost. |
## Пояснения

| Field | Description |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | Альтернативный символ, используемый для разделения уровней каталогов в пути. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | Символ, используемый для разделения уровней каталогов в пути. |
| static [PathSeparator](./pathseparator/) | Символ-разделитель, используемый для разделения строк путей в переменных окружения. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | Символ разделителя томов. |
## Примечания



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // Сгенерировать случайное имя файла.
  auto filename = Path::GetRandomFileName();

  // Вывести информацию о имени файла.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
Этот пример кода выводит следующее:
Имя файла: qhuzkyqv.y6p
Имя файла без расширения: qhuzkyqv
Расширение: .y6p
*/
```

## См. также

* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)