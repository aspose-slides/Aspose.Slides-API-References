---
title: WaitAny()
second_title: Referencia de API de Aspose.Slides para C++
description: Espera a que cualquiera de los manejadores se dispare.
type: docs
weight: 14
url: /es/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) método


Espera a que cualquiera de los manejadores se dispare.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manejadores a esperar. |
| millisecondsTimeout | int | [Timeout](../../timeout/) a esperar, en milisegundos; -1 significa espera infinita, 0 significa comprobar y devolver, los valores positivos son tiempos de espera. |

### Valor devuelto

True si cualquier manejador se disparó, false si se excedió el tiempo de espera.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) método


Espera a que cualquiera de los manejadores se dispare.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manejadores a esperar. |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) que representa la cantidad de milisegundos a esperar, o un [System::TimeSpan](../../../system/timespan/) que representa -1 milisegundos para esperar indefinidamente. |

### Valor devuelto

True si cualquier manejador se disparó, false si se excedió el tiempo de espera.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) método


Espera a que cualquiera de los manejadores se dispare.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Manejadores a esperar. |

### Valor devuelto

True cuando cada elemento en waitHandles ha recibido una señal; de lo contrario, el método nunca retorna.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)