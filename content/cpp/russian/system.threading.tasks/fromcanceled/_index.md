---
title: FromCanceled()
second_title: Aspose.Slides для справочника API C++
description: Создаёт задачу, которая завершилась из-за отмены с указанным токеном.
type: docs
weight: 118
url: /ru/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) function

Создает задачу, которая завершилась из-за отмены с указанным токеном.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Токен отмены, который вызвал отмену задачи. |

### Возвращаемое значение

Отменённая задача.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Класс [CancellationToken](../../system.threading/cancellationtoken/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)