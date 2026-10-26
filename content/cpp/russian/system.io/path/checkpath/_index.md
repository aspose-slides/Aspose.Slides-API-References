---
title: CheckPath()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, является ли указанный путь допустимым, проверяя, содержит ли он недопустимые символы. Исключение бросается, если путь содержит недопустимые символы.
type: docs
weight: 209
url: /ru/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) метод

Определяет, является ли указанный путь допустимым, проверяя, содержит ли он недопустимые символы. Исключение бросается, если путь содержит недопустимые символы.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь, который необходимо проверить |
| msg | const [String](../../../system/string/)\& | Сообщение, передаваемое конструктору объекта исключения |
| allow_empty | **bool** | Указывает, следует ли рассматривать пустую или нулевую строку как корректный путь (true) или нет (false); если этот параметр равен false и **path** пуст, выбрасывается ArgumentException; если этот параметр равен false и **path** null, выбрасывается ArgumentNullException |

## См. также

* Класс [String](../../../system/string/)
* Класс [Path](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)