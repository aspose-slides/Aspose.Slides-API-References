---
title: ContinueWith()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma continuação que é executada quando a tarefa é concluída.
type: docs
weight: 118
url: /pt/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) método

Cria uma continuação que é executada quando a tarefa é concluída.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Ação a ser executada quando esta tarefa for concluída |

### Valor de Retorno

TaskPtr Uma nova tarefa que representa a continuação

## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) método

Cria uma continuação que é executada quando a tarefa é concluída.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TResult | Um tipo de resultado da tarefa |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Função para obter o resultado quando esta tarefa for concluída |

### Valor de Retorno

RTaskPtr Uma nova tarefa que representa a continuação

## Veja Também

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Task](../)
* Class [Func](../../../system/func/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)