---
title: WaitAll()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda até que todos os objetos Task fornecidos concluam a execução.
type: docs
weight: 170
url: /pt/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) função


Aguarda até que todos os objetos [Task](../task/) fornecidos concluam a execução.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Um array de instâncias [Task](../task/) para aguardar. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Um [CancellationToken](../../system.threading/cancellationtoken/) a ser observado enquanto aguarda a conclusão das tarefas. |

## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) função


Aguarda até que todos os objetos [Task](../task/) fornecidos concluam a execução.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Um array de instâncias [Task](../task/) para aguardar. |

## Veja também

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)