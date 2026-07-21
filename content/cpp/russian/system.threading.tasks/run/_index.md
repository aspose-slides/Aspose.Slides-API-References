---
title: Run()
second_title: Справочник API Aspose.Slides для C++
description: Помещает указанную работу в пул потоков и возвращает дескриптор Task для этой работы.
type: docs
weight: 157
url: /ru/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) функция


Помещает указанную работу в пул потоков и возвращает [Task](../task/) дескриптор для этой работы.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Работа, которую необходимо выполнить асинхронно. |

### Возвращаемое значение

[Task](../task/) представляющий работу, поставленную в очередь для выполнения в пуле потоков.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) функция


Помещает указанную работу в пул потоков и возвращает [Task](../task/) дескриптор для этой работы.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Работа, которую необходимо выполнить асинхронно. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Токен отмены, который можно использовать для отмены работы, если она ещё не началась. |

### Возвращаемое значение

[Task](../task/) представляющий работу, поставленную в очередь для выполнения в пуле потоков.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) функция


Помещает указанную работу в пул потоков и возвращает прокси для [Task](../task/), возвращаемого функцией.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Работа, которую необходимо выполнить асинхронно, возвращающая [Task](../task/). |

### Возвращаемое значение

[Task](../task/) представляющий прокси для [Task](../task/), возвращаемого функцией.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) функция


Помещает указанную работу в пул потоков и возвращает дескриптор Task<TResult> для этой работы.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TResult | Тип результата, возвращаемого задачей. |

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Работа, которую необходимо выполнить асинхронно. |

### Возвращаемое значение

Task<TResult>, представляющий работу, поставленную в очередь для выполнения в пуле потоков.

## См. также

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Класс [CancellationToken](../../system.threading/cancellationtoken/)
* Класс [Func](../../system/func/)
* Пространство имён [System::Threading::Tasks](../)
* Библиотека [Aspose.Slides](../../)