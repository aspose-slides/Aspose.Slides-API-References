---
title: AsTask()
second_title: Referência da API Aspose.Slides para C++
description: Converte este ResultValueTask em um ponteiro compartilhado para ResultTask<T>.
type: docs
weight: 79
url: /pt/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const método

Converte este [ResultValueTask](../) em um ponteiro compartilhado para ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### Valor de Retorno

RTaskPtr<T> Um ponteiro compartilhado para um ResultTask<T> que representa esta operação.
## Observações


Se o [ResultValueTask](../) contém um resultado direto, cria uma tarefa concluída com esse resultado. Se ele contém uma tarefa, retorna um ponteiro compartilhado para essa tarefa. 

## Veja Também

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Classe [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)