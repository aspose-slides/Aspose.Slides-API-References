---
title: FromException()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт задачу, завершившуюся с указанным исключением.
type: docs
weight: 131
url: /ru/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) функция

Создаёт задачу, которая завершилась с указанным исключением.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Исключение, с которым необходимо завершить задачу. |

### Возвращаемое значение

Задача с ошибкой.

## System::Threading::Tasks::FromException(const Exception\&) функция

Создаёт задачу, которая завершилась с указанным исключением и типом результата.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TResult | Тип результата задачи. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Исключение, с которым необходимо завершить задачу. |

### Возвращаемое значение

Задача с ошибкой указанного типа результата.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Пространство имён [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)