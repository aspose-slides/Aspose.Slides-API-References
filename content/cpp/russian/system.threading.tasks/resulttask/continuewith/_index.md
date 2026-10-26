---
title: ContinueWith()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт продолжение, которое выполняется при завершении задачи-результата.
type: docs
weight: 40
url: /ru/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) метод

Создаёт продолжение, которое выполняется при завершении задачи-результата.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Action to execute when this task completes, receiving this result task |

### Возвращаемое значение

TaskPtr Новый объект задачи, представляющий продолжение

## Замечания

Действие продолжения получает этот [ResultTask](../), чтобы получить доступ к значению результата 

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) метод

Создаёт продолжение, которое выполняется при завершении задачи-результата.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TNewResult | Тип результата продолжения задачи |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Функция для получения результата продолжения, когда эта задача завершится, принимая эту задачу-результат |

### Возвращаемое значение

RTaskPtr Новый объект задачи, представляющий продолжение

## Замечания

Функция продолжения получает этот [ResultTask](../), чтобы получить доступ к значению результата 

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) метод

Создаёт продолжение, которое выполняется при завершении задачи.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Действие, которое будет выполнено при завершении этой задачи |

### Возвращаемое значение

TaskPtr Новый объект задачи, представляющий продолжение

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) метод

Создаёт продолжение, которое выполняется при завершении задачи.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TResult | Тип результата задачи |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Функция для получения результата, когда эта задача завершится |

### Возвращаемое значение

RTaskPtr Новый объект задачи, представляющий продолжение

## См. также

* Типовое определение [TaskPtr](../../../system/taskptr/)
* Типовое определение [Action](../../../system/action/)
* Типовое определение [RTaskPtr](../../../system/rtaskptr/)
* Класс [ResultTask](../)
* Класс [Func](../../../system/func/)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)