---
title: Task()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye un Task con una acción para ejecutar.
type: docs
weight: 1
url: /es/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) constructor


Construye un [Task](../) con una acción para ejecutar.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | La acción que se ejecutará de forma asíncrona |

## Task::Task(const Action<>\&, const CancellationToken\&) constructor


Construye un [Task](../) con una acción y un token de cancelación.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | La acción que se ejecutará de forma asíncrona |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token para monitorizar solicitudes de cancelación |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructor


Construye un [Task](../) con una acción con estado y un objeto de estado.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | La acción que se ejecutará (acepta un objeto de estado) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objeto de estado definido por el usuario que se pasa a la acción |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor


Construye un [Task](../) con una acción con estado, estado y token de cancelación.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | La acción que se ejecutará (acepta un objeto de estado) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objeto de estado definido por el usuario que se pasa a la acción |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token para monitorizar solicitudes de cancelación |

## Task::Task() constructor


Constructor interno para crear tareas no inicializadas.

```cpp
System::Threading::Tasks::Task::Task()
```

## Ver también

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Task](../)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Object](../../../system/object/)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)