---
title: WaitAll()
second_title: Referencia de la API de Aspose.Slides para C++
description: Espera a que todos los manejadores se activen.
type: docs
weight: 1
url: /es/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


Espera a que todos los manejadores se activen.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manejadores a esperar. |
| millisecondsTimeout | int | [Timeout](../../timeout/) para esperar, en milisegundos; -1 significa espera infinita, 0 significa comprobar y devolver, los valores positivos son tiempos de espera. |

### Valor de retorno

True if all handles fired, false if timeout exceeded.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


Espera a que todos los manejadores se activen.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manejadores a esperar. |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) que representa el número de milisegundos a esperar, o un [System::TimeSpan](../../../system/timespan/) que representa -1 milisegundos para esperar indefinidamente. |

### Valor de retorno

True if all handles fired, false if timeout exceeded.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


Espera a que todos los manejadores se activen.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manejadores a esperar. |

### Valor de retorno

True cuando cada elemento en waitHandles ha recibido una señal; de lo contrario el método nunca retorna.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [WaitHandle](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Threading](../../)
* Library [Aspose.Slides](../../../)