---
title: Trace
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет интерфейс для доступа к трассировке отладчика (если она есть). Работает только в режиме Debug. Это статический тип без сервисов экземпляра. Ни в каких случаях не следует создавать его экземпляры любыми способами.
type: docs
weight: 131
url: /ru/system.diagnostics/trace/
---
## Trace структура

Предоставляет интерфейс для доступа к трассировке отладчика (если она есть). Работает только в режиме [Debug](../debug/). Это статический тип без сервисов экземпляра. Ни в каких случаях не следует создавать его экземпляры.

```cpp
class Trace
```

## Методы

| Метод | Описание |
| --- | --- |
| static void [Flush](./flush/)() | Flushes the output buffer, and causes buffered data to be written to the listeners. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Writes line to debugger trace. |

## См. также

* Простейство имён [System::Diagnostics](../)
* Библиотека [Aspose.Slides](../../)