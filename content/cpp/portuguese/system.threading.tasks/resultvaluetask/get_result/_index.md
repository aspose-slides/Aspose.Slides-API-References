---
title: get_Result()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o resultado da tarefa concluída.
type: docs
weight: 66
url: /pt/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() método


Obtém o resultado da tarefa concluída.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```


### Valor de Retorno

T O valor do resultado.

## Observações



Se a tarefa for baseada em um ResultTask<T>, este método aguardará o resultado e o armazenará em cache. Chamadas subsequentes retornarão o valor em cache sem aguardar. 

## Veja Também

* Classe [ResultValueTask](../)
* Espaço de nomes [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)