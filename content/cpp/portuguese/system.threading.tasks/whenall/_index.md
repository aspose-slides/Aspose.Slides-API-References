---
title: WhenAll()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma tarefa que será concluída quando todas as tarefas fornecidas forem concluídas.
type: docs
weight: 196
url: /pt/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) função


Cria uma tarefa que será concluída quando todas as tarefas fornecidas forem concluídas.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | As tarefas a aguardar para conclusão. |

### Valor de retorno

Uma tarefa que representa a conclusão de todas as tarefas fornecidas.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) função


Cria uma tarefa que será concluída quando todas as tarefas fornecidas forem concluídas.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[TaskPtr](../../system/taskptr/)\>\>\& | As tarefas a aguardar para conclusão. |

### Valor de retorno

Uma tarefa que representa a conclusão de todas as tarefas fornecidas.

## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) função


Cria uma tarefa que será concluída quando todas as tarefas fornecidas forem concluídas.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TResult | O tipo dos resultados das tarefas concluídas. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\>\& | As tarefas a aguardar para conclusão. |

### Valor de retorno

Uma tarefa que retorna um array de todos os resultados quando todas as tarefas são concluídas.

## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) função


Cria uma tarefa que será concluída quando todas as tarefas fornecidas forem concluídas.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TResult | O tipo dos resultados das tarefas concluídas. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[RTaskPtr](../../system/rtaskptr/)\<TResult\>\>\& | As tarefas a aguardar para conclusão. |

### Valor de retorno

Uma tarefa que retorna um array de todos os resultados quando todas as tarefas são concluídas.

## Veja também

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Classe [IEnumerable](../../system.collections.generic/ienumerable/)
* Espaço de nomes [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)