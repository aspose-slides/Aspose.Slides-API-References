---
title: "System::Threading::Tasks"
second_title: Aspose.Slides — справочник API для C++
description: 
type: docs
weight: 1015
url: /ru/system.threading.tasks/
---
## Классы

| Class | Описание |
| --- | --- |
| [Parallel](./parallel/) | Обеспечивает поддержку параллельных циклов и областей. |
| [ParallelLoopResult](./parallelloopresult/) | Предоставляет статус завершения [Parallel](./parallel/) цикла. |
| [ParallelOptions](./paralleloptions/) | Хранит параметры, конфигурирующие работу методов класса [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Специализация [Task](./task/), возвращающая значение результата после завершения. |
| [ResultValueTask](./resultvaluetask/) | Представляет гибридный тип, похожий на задачу, который может оборачивать либо прямое значение результата, либо ResultTask<T>. |
| [Task](./task/) | Представляет асинхронную операцию, которую можно ожидать и комбинировать с другими задачами. |
| [TaskScheduler](./taskscheduler/) | Представляет объект, который обрабатывает низкоуровневую работу по постановке задач в очередь на потоки. |
| [ValueTask](./valuetask/) | Предоставляет ожидаемый результат асинхронной операции. |

## Функции

| Function | Описание |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Создает задачу, которая завершается после задержки во времени. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Создает задачу, которая завершается после задержки во времени и может быть отменена. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Создает задачу, завершившуюся из-за отмены с указанным токеном. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Создает задачу, завершившуюся с указанным исключением. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Создает задачу, завершившуюся с указанным исключением и типом результата. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Создает задачу, успешно завершившуюся с указанным результатом. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Помещает указанную работу в очередь выполнения в пуле потоков и возвращает дескриптор [Task](./task/) для этой работы. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Помещает указанную работу в очередь выполнения в пуле потоков и возвращает дескриптор [Task](./task/) для этой работы. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Помещает указанную работу в очередь выполнения в пуле потоков и возвращает прокси для [Task](./task/), возвращаемого функцией. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Помещает указанную работу в очередь выполнения в пуле потоков и возвращает дескриптор Task<TResult> для этой работы. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Ожидает завершения выполнения всех предоставленных объектов [Task](./task/). |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Ожидает завершения выполнения всех предоставленных объектов [Task](./task/). |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Ожидает завершения выполнения любого из предоставленных объектов [Task](./task/). |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Ожидает завершения выполнения любого из предоставленных объектов [Task](./task/). |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Создает задачу, которая завершится, когда все переданные задачи завершатся. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Создает задачу, которая завершится, когда все переданные задачи завершатся. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Создает задачу, которая завершится, когда все переданные задачи завершатся. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Создает задачу, которая завершится, когда все переданные задачи завершатся. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Создает задачу, которая завершится, когда любая из переданных задач завершится. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Создает задачу, которая завершится, когда любая из переданных задач завершится. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Создает задачу, которая завершится, когда любая из переданных задач завершится. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Создает задачу, которая завершится, когда любая из переданных задач завершится. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Создает ожидаемую задачу, которая асинхронно возвращает управление текущему контексту при ожидании. |

## Перечисления

| Перечисление | Описание |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |