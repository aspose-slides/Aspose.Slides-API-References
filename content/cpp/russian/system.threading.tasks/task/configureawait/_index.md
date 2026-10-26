---
title: ConfigureAwait()
second_title: Справочник API Aspose.Slides для C++
description: Настраивает, как ожидания в этой задаче должны вести себя относительно захвата контекста.
type: docs
weight: 144
url: /ru/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait(bool) const метод

Настраивает, как ожидания в этой задаче должны вести себя относительно захвата контекста.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Нужно ли продолжать выполнение в захваченном контексте |

### Возвращаемое значение

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) Настроенный awaitable

## См. также

* Класс [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Класс [Task](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)