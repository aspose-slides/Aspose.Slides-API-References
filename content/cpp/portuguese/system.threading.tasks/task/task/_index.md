---
title: Task()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um Task com uma ação para executar.
type: docs
weight: 1
url: /pt/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) construtor


Constrói um [Task](../) com uma ação para executar.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | A ação para executar de forma assíncrona |

## Task::Task(const Action<>\&, const CancellationToken\&) construtor


Constrói um [Task](../) com uma ação e um token de cancelamento.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | A ação para executar de forma assíncrona |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token para monitorar solicitações de cancelamento |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) construtor


Constrói um [Task](../) com uma ação com estado e um objeto de estado.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | A ação para executar (aceita objeto de estado) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objeto de estado definido pelo usuário passado para a ação |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) construtor


Constrói um [Task](../) com ação com estado, estado e token de cancelamento.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | A ação para executar (aceita objeto de estado) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objeto de estado definido pelo usuário passado para a ação |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token para monitorar solicitações de cancelamento |

## Task::Task() construtor


Construtor interno para criar tarefas não inicializadas.

```cpp
System::Threading::Tasks::Task::Task()
```

## Veja Também

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Task](../)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)