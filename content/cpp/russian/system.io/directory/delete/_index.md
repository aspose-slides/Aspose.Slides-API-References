---
title: Delete()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет указанный файл или каталог. Не генерирует исключений.
type: docs
weight: 14
url: /ru/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) метод


Удаляет указанный файл или каталог. Не генерирует исключений.

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к каталогу или файлу, который будет удалён |
| recursive | **bool** | Если **path** указывает на непустой каталог, то **recursive** определяет, следует ли рекурсивно удалять всё содержимое каталога; если каталог, указанный в **path**, не пуст и **recursive** равно 'false', операция завершается с ошибкой |

## См. также

* Класс [String](../../../system/string/)
* Класс [Directory](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)