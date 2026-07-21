---
title: Delay()
second_title: Aspose.Slides для C++ справочник API
description: Создает задачу, которая завершается после задержки во времени.
type: docs
weight: 105
url: /ru/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) функция

Создает задачу, которая завершается после задержки во времени.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Количество миллисекунд, которое нужно ждать перед завершением возвращаемой задачи, или -1 для бесконечного ожидания. |

### Возвращаемое значение

Задача, представляющая задержку во времени.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) функция

Создает задачу, которая завершается после задержки во времени и может быть отменена.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Количество миллисекунд, которое нужно ждать перед завершением возвращаемой задачи, или -1 для бесконечного ожидания. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Токен отмены, который может быть использован для отмены задержки. |

### Возвращаемое значение

Задача, представляющая задержку во времени.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Класс [CancellationToken](../../system.threading/cancellationtoken/)
* Пространство имён [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)