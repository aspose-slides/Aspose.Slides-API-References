---
title: QueueUserWorkItem()
second_title: Referencia de la API de Aspose.Slides para C++
description: Coloca un elemento de trabajo en la cola con una devolución de llamada sin parámetros.
type: docs
weight: 14
url: /es/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) método

Coloca un elemento de trabajo en la cola con una devolución de llamada sin parámetros.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Función de devolución de llamada que se usará como trabajo. |

### Valor devuelto

Always returns true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) método

Coloca un elemento de trabajo en la cola con una devolución de llamada sin parámetros.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Función de devolución de llamada que se usará como trabajo. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Parámetro de la función de trabajo. |

### Valor devuelto

Always returns true.

## Ver también

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ThreadPool](../)
* Clase [Object](../../../system/object/)
* Espacio de nombres [System::Threading](../../)
* Library [Aspose.Slides](../../../)