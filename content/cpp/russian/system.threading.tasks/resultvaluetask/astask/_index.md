---
title: AsTask()
second_title: Aspose.Slides для C++ Справочник API
description: Преобразует этот ResultValueTask в shared pointer к ResultTask<T>.
type: docs
weight: 79
url: /ru/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const метод

Преобразует этот [ResultValueTask](../) в shared pointer к ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### Возвращаемое значение

RTaskPtr<T> shared pointer к ResultTask<T>, представляющий эту операцию.
## Примечания

Если [ResultValueTask](../) содержит непосредственный результат, создаёт завершённую задачу с этим результатом. Если он содержит задачу, возвращает shared pointer к этой задаче.

## См. также

* Типовое определение [RTaskPtr](../../../system/rtaskptr/)
* Класс [ResultValueTask](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)