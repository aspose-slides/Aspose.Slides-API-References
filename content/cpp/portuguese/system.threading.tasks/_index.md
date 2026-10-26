---
title: "System::Threading::Tasks"
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 1015
url: /pt/system.threading.tasks/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [Parallel](./parallel/) | Fornece suporte para loops e regiões paralelas. |
| [ParallelLoopResult](./parallelloopresult/) | Fornece o status de conclusão de um loop [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | Armazena opções que configuram a operação dos métodos na classe [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Uma especialização [Task](./task/) que retorna um valor de resultado ao concluir. |
| [ResultValueTask](./resultvaluetask/) | Representa um tipo híbrido semelhante a tarefa que pode envolver tanto um valor de resultado direto quanto um ResultTask<T>. |
| [Task](./task/) | Representa uma operação assíncrona que pode ser aguardada e composta com outras tarefas. |
| [TaskScheduler](./taskscheduler/) | Representa um objeto que lida com o trabalho de baixo nível de enfileirar tarefas em threads. |
| [ValueTask](./valuetask/) | Fornece um resultado aguardável de uma operação assíncrona. |

## Functions

| Função | Descrição |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Cria uma tarefa que termina após um atraso de tempo. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Cria uma tarefa que termina após um atraso de tempo e pode ser cancelada. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Cria uma tarefa que foi concluída devido ao cancelamento com o token especificado. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Cria uma tarefa que foi concluída com uma exceção especificada. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Cria uma tarefa que foi concluída com uma exceção especificada e tipo de resultado. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Cria uma tarefa que foi concluída com sucesso com o resultado especificado. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Enfileira o trabalho especificado para ser executado na thread pool e retorna um manipulador [Task](./task/) para esse trabalho. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Enfileira o trabalho especificado para ser executado na thread pool e retorna um manipulador [Task](./task/) para esse trabalho. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Enfileira o trabalho especificado para ser executado na thread pool e retorna um proxy para o [Task](./task/) retornado pela função. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Enfileira o trabalho especificado para ser executado na thread pool e retorna um manipulador Task<TResult> para esse trabalho. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Aguarda todos os objetos [Task](./task/) fornecidos concluírem a execução. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Aguarda todos os objetos [Task](./task/) fornecidos concluírem a execução. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Aguarda que qualquer um dos objetos [Task](./task/) fornecidos conclua a execução. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Aguarda que qualquer um dos objetos [Task](./task/) fornecidos conclua a execução. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Cria uma tarefa que será concluída quando todas as tarefas fornecidas tiverem sido concluídas. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Cria uma tarefa que será concluída quando todas as tarefas fornecidas tiverem sido concluídas. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Cria uma tarefa que será concluída quando todas as tarefas fornecidas tiverem sido concluídas. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Cria uma tarefa que será concluída quando todas as tarefas fornecidas tiverem sido concluídas. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Cria uma tarefa aguardável que devolve assíncronamente ao contexto atual quando aguardada. |

## Enums

| Enum | Descrição |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |