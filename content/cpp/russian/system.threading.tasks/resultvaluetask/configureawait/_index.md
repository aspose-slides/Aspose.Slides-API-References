---
title: ConfigureAwait()
second_title: Aspose.Slides для C++ справка по API
description: Настраивает awaiter для этой задачи.
type: docs
weight: 92
url: /ru/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const метод

Настраивает awaiter для этой задачи.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true, чтобы попытаться передать продолжение обратно в оригинальный захваченный контекст; иначе false. |

### Возвращаемое значение

ConfiguredResultValueTaskAwaitable<T> Объект, который настраивает поведение awaiter'ов для этой задачи.

## См. также

* Класс [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Класс [ResultValueTask](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)