---
title: ResultTask()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un ResultTask con una función que devuelve un valor.
type: docs
weight: 1
url: /es/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) constructor

Construye un [ResultTask](../) con una función que devuelve un valor.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | La función a ejecutar de forma asíncrona que devuelve un resultado |

## ResultTask::ResultTask() constructor

Implementación interna. No es para código de usuario.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Observaciones

Constructor interno para crear tareas de resultado no inicializadas

## ResultTask::ResultTask(const T\&) constructor

Constructor interno para crear tareas de resultado con un resultado especificado.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Ver también

* Clase [Func](../../../system/func/)
* Clase [ResultTask](../)
* Espacio de nombres [System::Threading::Tasks](../../)
* Biblioteca [Aspose.Slides](../../../)