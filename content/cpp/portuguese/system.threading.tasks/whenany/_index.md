---
title: WhenAny()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída.
type: docs
weight: 209
url: /pt/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) função


Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | As tarefas que devem ser aguardadas para conclusão. |

### Valor de Retorno

Uma tarefa que representa a conclusão de uma das tarefas fornecidas.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) função


Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | As tarefas que devem ser aguardadas para conclusão. |

### Valor de Retorno

Uma tarefa que representa a conclusão de uma das tarefas fornecidas.

## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) função


Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TResult | O tipo do resultado da tarefa concluída. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | As tarefas que devem ser aguardadas para conclusão. |

### Valor de Retorno

Uma tarefa que devolve a primeira tarefa concluída quando qualquer tarefa for concluída.

## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) função


Cria uma tarefa que será concluída quando qualquer uma das tarefas fornecidas for concluída.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TResult | O tipo do resultado da tarefa concluída. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | As tarefas que devem ser aguardadas para conclusão. |

### Valor de Retorno

Uma tarefa que devolve a primeira tarefa concluída quando qualquer tarefa for concluída.

## Ver Também

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)