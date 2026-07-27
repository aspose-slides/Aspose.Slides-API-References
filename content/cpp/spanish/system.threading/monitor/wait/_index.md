---
title: Wait()
second_title: Referencia de API de Aspose.Slides para C++
description: Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. Opcionalmente sale del dominio de sincronización para el contexto sincronizado antes de la espera y vuelve a adquirir el dominio después. No implementado.
type: docs
weight: 53
url: /es/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) método


Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. Opcionalmente sale del dominio de sincronización para el contexto sincronizado antes de la espera y vuelve a adquirir el dominio después. No implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) método


Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. Opcionalmente sale del dominio de sincronización para el contexto sincronizado antes de la espera y vuelve a adquirir el dominio después. No implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) método


Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. No implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) método


Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. Si transcurre el intervalo de tiempo de espera especificado, el hilo entra en la cola de preparados. No implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```


## Monitor::Wait(const SharedPtr\<Object\>\&) método


Libera el bloqueo de un objeto y bloquea el hilo actual hasta que vuelva a adquirir el bloqueo. No implementado.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```


## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [Monitor](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)