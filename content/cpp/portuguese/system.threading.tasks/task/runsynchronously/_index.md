---
title: RunSynchronously()
second_title: Referência da API Aspose.Slides para C++
description: Executa a tarefa de forma síncrona na thread atual.
type: docs
weight: 157
url: /pt/system.threading.tasks/task/runsynchronously/
---
## Task::RunSynchronously() método

Executa a tarefa de forma síncrona na thread atual.

```cpp
void System::Threading::Tasks::Task::RunSynchronously()
```

## Task::RunSynchronously(const SharedPtr\<TaskScheduler\>\&) método

Executa a tarefa de forma síncrona usando o agendador especificado.

```cpp
void System::Threading::Tasks::Task::RunSynchronously(const SharedPtr<TaskScheduler> &scheduler)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | O agendador a ser usado para execução |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Task](../)
* Classe [TaskScheduler](../../taskscheduler/)
* Namespace [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)