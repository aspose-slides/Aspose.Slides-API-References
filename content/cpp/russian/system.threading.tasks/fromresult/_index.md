---
title: FromResult()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт задачу, успешно завершившуюся с указанным результатом.
type: docs
weight: 144
url: /ru/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult(TResult) функция

Создаёт задачу, успешно завершившуюся с указанным результатом.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TResult | Тип результата задачи. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| result | TResult | Значение результата, с которым должна быть завершена задача. |

### Возвращаемое значение

Задача, успешно завершившаяся.

## См. также

* Тип [RTaskPtr](../../system/rtaskptr/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)