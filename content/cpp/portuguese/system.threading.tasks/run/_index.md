---
title: Run()
second_title: Referência da API Aspose.Slides para C++
description: Enfileira o trabalho especificado para ser executado no pool de threads e retorna um manipulador Task para esse trabalho.
type: docs
weight: 157
url: /pt/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) função


Enfileira o trabalho especificado para ser executado no pool de threads e retorna um manipulador [Task](../task/) para esse trabalho.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | O trabalho a ser executado de forma assíncrona. |

### Valor de Retorno

Um [Task](../task/) que representa o trabalho enfileirado para execução no pool de threads.

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) função


Enfileira o trabalho especificado para ser executado no pool de threads e retorna um manipulador [Task](../task/) para esse trabalho.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | O trabalho a ser executado de forma assíncrona. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Um token de cancelamento que pode ser usado para cancelar o trabalho se ainda não tiver começado. |

### Valor de Retorno

Um [Task](../task/) que representa o trabalho enfileirado para execução no pool de threads.

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) função


Enfileira o trabalho especificado para ser executado no pool de threads e retorna um proxy para o [Task](../task/) retornado pela função.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | O trabalho a ser executado de forma assíncrona, que retorna um [Task](../task/). |

### Valor de Retorno

Um [Task](../task/) que representa um proxy para o [Task](../task/) retornado pela função.

## System::Threading::Tasks::Run(const Func\<TResult\>\&) função


Enfileira o trabalho especificado para ser executado no pool de threads e retorna um manipulador Task<TResult> para esse trabalho.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TResult | O tipo do resultado retornado pela tarefa. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | O trabalho a ser executado de forma assíncrona. |

### Valor de Retorno

Um Task<TResult> que representa o trabalho enfileirado para execução no pool de threads.

## Veja também

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Classe [CancellationToken](../../system.threading/cancellationtoken/)
* Classe [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Biblioteca [Aspose.Slides](../../)