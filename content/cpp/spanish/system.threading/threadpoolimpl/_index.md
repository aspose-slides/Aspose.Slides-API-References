---
title: ThreadPoolImpl
second_title: Aspose.Slides para C++ Referencia de API
description: Datos internos del pool de hilos. Este es un tipo singleton con la gestión de memoria realizada por la(s) función(es) de acceso. Nunca debe crear instancias de él directamente.
type: docs
weight: 235
url: /es/system.threading/threadpoolimpl/
---
## ThreadPoolImpl clase


[Thread](../thread/) datos internos del pool. Este es un tipo singleton con gestión de memoria realizada por funciones de acceso. Nunca debe crear instancias directamente.

```cpp
class ThreadPoolImpl
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Obtiene el número de hilos disponibles. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Obtiene el singleton del estado de inicialización. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Obtiene el número máximo de hilos concurrentes. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Obtiene el número mínimo de hilos creados por el pool. |
| void [JoinAll](./joinall/)() | Une todos los hilos pertenecientes. Espera indefinidamente. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Agrega un elemento de trabajo a la cola. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Establece el número de hilos pertenecientes al pool. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Establece el número mínimo de hilos pertenecientes al pool. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Constructor. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Destructor. Une todos los hilos si aún no se habían terminado. |
## Ver también

* Espacio de nombres [System::Threading](../)
* Biblioteca [Aspose.Slides](../../)