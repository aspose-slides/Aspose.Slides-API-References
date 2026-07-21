---
title: get_Result()
second_title: Aspose.Slides для справочника API C++
description: Получает результат завершённого задания.
type: docs
weight: 66
url: /ru/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() метод


Получает результат завершённого задания.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```


### Возвращаемое значение

T Значение результата.
## Примечания



Если задача поддерживается ResultTask<T>, этот метод будет ожидать результат и кэшировать его. Последующие вызовы вернут кэшированное значение без ожидания. 

## См. также

* Класс [ResultValueTask](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)