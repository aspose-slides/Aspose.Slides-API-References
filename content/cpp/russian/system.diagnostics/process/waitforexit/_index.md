---
title: WaitForExit()
second_title: Справочник API Aspose.Slides для C++
description: Ожидает завершения процесса. Не реализовано.
type: docs
weight: 27
url: /ru/system.diagnostics/process/waitforexit/
---
## Process::WaitForExit(int) метод

Ожидает завершения процесса. Не реализовано.

```cpp
bool System::Diagnostics::Process::WaitForExit(int milliseconds)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| milliseconds | int | Максимальная задержка ожидания. |

### Возвращаемое значение

True если процесс завершён, false если превышено время ожидания.

## Process::WaitForExit() метод

Ожидает завершения процесса, не возвращает управление, пока процесс не завершится.

```cpp
void System::Diagnostics::Process::WaitForExit()
```

## См. также

* Класс [Process](../)
* Пространство имён [System::Diagnostics](../../)
* Библиотека [Aspose.Slides](../../../)