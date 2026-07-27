---
title: GetAwaiter()
second_title: Referência da API Aspose.Slides para C++
description: Obtém um awaiter para esta tarefa de resultado para uso com Await.
type: docs
weight: 53
url: /pt/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const método


Obtém um awaiter para esta tarefa de resultado para uso com Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### Valor de Retorno

Runtime::CompilerServices::ResultTaskAwaiter<T> Uma instância de awaiter que retorna o resultado
## Observações



Quando aguardado, a coroutine retoma com o valor do resultado disponível 

## Veja Também

* Classe [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Classe [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)