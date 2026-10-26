---
title: ResultValueTask()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un ResultValueTask vacío y no inicializado.
type: docs
weight: 1
url: /es/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() constructor

Construye un [ResultValueTask](../) vacío y no inicializado.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Observaciones

La tarea no está completada y no contiene ningún resultado. Intentar obtener el resultado lanzará una excepción.

## ResultValueTask::ResultValueTask(const T\&) constructor

Construye un [ResultValueTask](../) completado con el resultado especificado.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| result | const T\& | El valor del resultado a encapsular en una tarea completada. |
## Observaciones

Esto crea una tarea completada con éxito que devuelve el valor inmediatamente.

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) constructor

Construye un [ResultValueTask](../) a partir de un puntero compartido a un ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | La tarea a encapsular. Puede ser nula para una tarea vacía. |
## Observaciones

El [ResultValueTask](../) representará el estado y el resultado de la tarea proporcionada.

## Véase también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Clase [ResultValueTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)