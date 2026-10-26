---
title: RunSynchronously()
second_title: Referencia de la API de Aspose.Slides para C++
description: Ejecuta la tarea de forma sincrónica en el hilo actual.
type: docs
weight: 157
url: /es/system.threading.tasks/task/runsynchronously/
---
## Task::RunSynchronously() método


Ejecuta la tarea de forma sincrónica en el subproceso actual.

```cpp
void System::Threading::Tasks::Task::RunSynchronously()
```


## Task::RunSynchronously(const SharedPtr\<TaskScheduler\>\&) método


Ejecuta la tarea de forma sincrónica usando el scheduler especificado.

```cpp
void System::Threading::Tasks::Task::RunSynchronously(const SharedPtr<TaskScheduler> &scheduler)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scheduler | const [SharedPtr](../../../system/sharedptr/)\<[TaskScheduler](../../taskscheduler/)\>\& | El planificador a usar para la ejecución |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Task](../)
* Clase [TaskScheduler](../../taskscheduler/)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)