---
title: WaitOne()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera a que el manejador se active durante un período ilimitado.
type: docs
weight: 27
url: /es/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() método


Espera a que el manejador se active durante un período ilimitado.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### Valor devuelto

Siempre devuelve true ya que no ocurre ningún tiempo de espera.

## WaitHandle::WaitOne(int) método


Espera a que el manejador se active.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) para esperar, en milisegundos; -1 significa espera infinita, 0 significa comprobar y regresar, los valores positivos son tiempos de espera. |

### Valor devuelto

True si el manejador se activó, false si se superó el tiempo de espera.

## WaitHandle::WaitOne(TimeSpan) método


Espera a que el manejador se active.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) que representa el número de milisegundos a esperar, o un [System::TimeSpan](../../../system/timespan/) que representa -1 milisegundos para esperar indefinidamente. |

### Valor devuelto

True si el manejador se activó, false si se superó el tiempo de espera.

## WaitHandle::WaitOne(int, bool) método


Espera a que el manejador se active.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) para esperar, en milisegundos; -1 significa espera infinita, 0 significa comprobar y regresar, los valores positivos son tiempos de espera. |
| exitContext | **bool** | Si es true, la espera debe liberar el bloqueo del manejador antes de esperar por él. |

### Valor devuelto

True si el manejador se activó, false si se superó el tiempo de espera.

## Ver también

* Clase [WaitHandle](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Threading](../../)
* Library [Aspose.Slides](../../../)