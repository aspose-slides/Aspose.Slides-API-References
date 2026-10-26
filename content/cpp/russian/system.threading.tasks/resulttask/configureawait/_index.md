---
title: ConfigureAwait()
second_title: Справочник API Aspose.Slides для C++
description: Настраивает, как await-операции на этой задаче результата должны вести себя относительно захвата контекста.
type: docs
weight: 27
url: /ru/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const метод

Настраивает, как await-операции на этой задаче результата должны вести себя относительно захвата контекста.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | Нужно ли продолжать выполнение в захваченном контексте |

### Возвращаемое значение

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> Настроенный awaitable для результата

## Примечания

Это обеспечивает точный контроль над потоком контекста для паттернов async/await

## См. также

* Класс [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Класс [ResultTask](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)