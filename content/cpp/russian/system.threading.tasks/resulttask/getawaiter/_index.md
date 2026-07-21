---
title: GetAwaiter()
second_title: Aspose.Slides для C++ справочник API
description: Получает объект awaiter для этой задачи результата для использования с Await.
type: docs
weight: 53
url: /ru/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const метод


Получает объект awaiter для этой задачи результата для использования с Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### Возвращаемое значение

Runtime::CompilerServices::ResultTaskAwaiter<T> Экземпляр awaiter, который возвращает результат
## Примечания



При ожидании корутина возобновится, когда значение результата будет доступно 

## См. также

* Класс [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Класс [ResultTask](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)