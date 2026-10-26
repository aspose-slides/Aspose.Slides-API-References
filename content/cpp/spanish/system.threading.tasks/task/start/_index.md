---
title: Start()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia la ejecución de la tarea usando el planificador predeterminado.
type: docs
weight: 170
url: /es/system.threading.tasks/task/start/
---
## Task::Start() método

Starts the task execution using the default scheduler.

```cpp
void System::Threading::Tasks::Task::Start()
```

## Task::Start(const SharedPtr\<TaskScheduler\>\&) método

Starts the task execution using the specified scheduler.

```cpp
void System::Threading::Tasks::Task::Start(const SharedPtr<TaskScheduler> &scheduler)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | El planificador a usar para la ejecución |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Task](../)
* Clase [TaskScheduler](../../taskscheduler/)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)