---
title: Delay()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma tarefa que é concluída após um atraso de tempo.
type: docs
weight: 105
url: /pt/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) função


Cria uma tarefa que é concluída após um atraso de tempo.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | O número de milissegundos a aguardar antes de concluir a tarefa retornada, ou -1 para aguardar indefinidamente. |

### Valor de Retorno

Uma tarefa que representa o atraso de tempo.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) função


Cria uma tarefa que é concluída após um atraso de tempo e pode ser cancelada.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | O número de milissegundos a aguardar antes de concluir a tarefa retornada, ou -1 para aguardar indefinidamente. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | O token de cancelamento que pode ser usado para cancelar o atraso. |

### Valor de Retorno

Uma tarefa que representa o atraso de tempo.

## Veja Também

* Typedef [TaskPtr](../../system/taskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)