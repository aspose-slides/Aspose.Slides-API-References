---
title: Start()
second_title: Aspose.Slides для C++ справочник API
description: Запускает процесс с предопределёнными параметрами.
type: docs
weight: 14
url: /ru/system.diagnostics/process/start/
---
## Process::Start() метод

Запускает процесс с предопределёнными параметрами.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) метод

Запускает процесс с указанным путем и аргументами.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) путь. |
| arguments | const [String](../../../system/string/)\& | [Process](../) параметры. |

### Возвращаемое значение

[Object](../../../system/object/) привязан к только что запущенному процессу.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) метод

Запускает процесс с указанным путем и аргументами.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Информация о процессе, который необходимо запустить. |

### Возвращаемое значение

[Object](../../../system/object/) привязан к только что запущенному процессу.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Process](../)
* Класс [String](../../../system/string/)
* Класс [ProcessStartInfo](../../processstartinfo/)
* Пространство имён [System::Diagnostics](../../)
* Библиотека [Aspose.Slides](../../../)