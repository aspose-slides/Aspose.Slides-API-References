---
title: ResultTask()
second_title: Aspose.Slides para C++ Referência da API
description: Constrói um ResultTask com uma função que retorna um valor.
type: docs
weight: 1
url: /pt/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) construtor

Constrói um [ResultTask](../) com uma função que retorna um valor.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | A função a ser executada assincronamente que retorna um resultado |

## ResultTask::ResultTask() construtor

Implementação interna. Não para código do usuário.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Observações

Construtor interno para criar tarefas de resultado não inicializadas

## ResultTask::ResultTask(const T\&) construtor

Construtor interno para criar tarefas de resultado com resultado especificado.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Ver Também

* Classe [Func](../../../system/func/)
* Classe [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)