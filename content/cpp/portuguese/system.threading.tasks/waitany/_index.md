---
title: WaitAny()
second_title: Referência da API Aspose.Slides para C++
description: Aguarda que qualquer um dos objetos Task fornecidos conclua a execução.
type: docs
weight: 183
url: /pt/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) função

Aguarda que qualquer um dos objetos [Task](../task/) fornecidos conclua a execução.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Uma matriz de instâncias [Task](../task/) nas quais aguardar. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Um [CancellationToken](../../system.threading/cancellationtoken/) a observar enquanto aguarda a conclusão das tarefas. |

### Valor de Retorno

O índice da tarefa concluída na matriz de tarefas.

## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) função

Aguarda que qualquer um dos objetos [Task](../task/) fornecidos conclua a execução.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tasks | const [ArrayPtr](../../system/arrayptr/)\<[TaskPtr](../../system/taskptr/)\>\& | Uma matriz de instâncias [Task](../task/) nas quais aguardar. |

### Valor de Retorno

O índice da tarefa concluída na matriz de tarefas.

## Veja Também

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)