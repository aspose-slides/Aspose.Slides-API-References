---
title: FileShare
second_title: Справочник API Aspose.Slides для C++
description: Указывает, какой тип доступа могут иметь другие объекты FileStream к открываемому файлу.
type: docs
weight: 534
url: /ru/system.io/fileshare/
---
## FileShare enum


Указывает, какой тип доступа другие объекты [FileStream](../filestream/) могут иметь к открываемому файлу.

```cpp
enum class FileShare
```

### Values

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Нет доступа. |
| Read | 1 | Доступ только для чтения. |
| Write | 2 | Доступ только для записи. |
| ReadWrite | 3 | Доступ для чтения и записи. |
| Delete | 4 | Файл может быть удалён. |
| Inheritable | 16 | Делает дескриптор файла наследуемым дочерними процессами. |

## See Also

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)