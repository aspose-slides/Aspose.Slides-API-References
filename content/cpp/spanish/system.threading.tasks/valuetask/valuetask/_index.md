---
title: ValueTask()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye un ValueTask vacío y no inicializado.
type: docs
weight: 1
url: /es/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() constructor

Construye un [ValueTask](../) vacío y no inicializado.

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Observaciones

La tarea no está completada y no contiene ningún resultado. Intentar obtener el resultado lanzará una excepción.

## ValueTask::ValueTask(const TaskPtr\&) constructor

Construye un [ValueTask](../) a partir de un puntero compartido a un [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| task | const [TaskPtr](../../../system/taskptr/)\& | La tarea a envolver. Puede ser nula para una tarea vacía. |
## Observaciones

El [ValueTask](../) representará el estado de la tarea proporcionada.

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Clase [ValueTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)