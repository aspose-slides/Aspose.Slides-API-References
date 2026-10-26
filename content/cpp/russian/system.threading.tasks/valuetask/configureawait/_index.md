---
title: ConfigureAwait()
second_title: Aspose.Slides для C++ справочник API
description: Настраивает ожидатель для этой задачи.
type: docs
weight: 79
url: /ru/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait(bool) const метод

Настраивает ожидатель для этой задачи.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true — попытка направить продолжение обратно в исходный захваченный контекст; иначе false. |

### Возвращаемое значение

ConfiguredValueTaskAwaitable Объект, который настраивает поведение ожидателей для этой задачи.

## См. также

* Класс [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Класс [ValueTask](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)