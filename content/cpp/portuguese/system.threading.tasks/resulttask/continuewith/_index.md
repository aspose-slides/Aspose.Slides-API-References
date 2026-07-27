---
title: ContinueWith()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma continuação que é executada quando a tarefa de resultado é concluída.
type: docs
weight: 40
url: /pt/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) método

Cria uma continuação que é executada quando a tarefa de resultado é concluída.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>\>\& | Ação a ser executada quando esta tarefa é concluída, recebendo esta tarefa de resultado |

### Valor de retorno

TaskPtr Uma nova tarefa que representa a continuação

## Observações

A ação de continuação recebe este [ResultTask](../) para acessar o valor do resultado

## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) método

Cria uma continuação que é executada quando a tarefa de resultado é concluída.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TNewResult | Tipo de resultado da continuação da tarefa |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| continuationFunction | const [Func](../../../system/func/)\<[RTaskPtr](../../../system/rtaskptr/)\<T\>, TNewResult\>\& | Função para obter o resultado da continuação quando esta tarefa é concluída, recebendo esta tarefa de resultado |

### Valor de retorno

RTaskPtr Uma nova tarefa que representa a continuação

## Observações

A função de continuação recebe este [ResultTask](../) para acessar o valor do resultado

## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) método

Cria uma continuação que é executada quando a tarefa é concluída.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| continuationAction | const [Action](../../../system/action/)\<[TaskPtr](../../../system/taskptr/)\>\& | Ação a ser executada quando esta tarefa é concluída |

### Valor de retorno

TaskPtr Uma nova tarefa que representa a continuação

## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) método

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
| continuationFunction | const [Func](../../../system/func/)\<[TaskPtr](../../../system/taskptr/), TResult\>\& | Função para obter o resultado quando esta tarefa é concluída |

### Valor de retorno

RTaskPtr Uma nova tarefa que representa a continuação

## Veja também

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Classe [ResultTask](../)
* Classe [Func](../../../system/func/)
* Espaço de nomes [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)