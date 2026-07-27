---
title: QueueUserWorkItem()
second_title: Referencia de la API de Aspose.Slides para C++
description: Añade un elemento de trabajo a la cola.
type: docs
weight: 1
url: /es/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) método


Añade un elemento de trabajo a la cola.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Función de devolución de llamada a ejecutar. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argumento de la función de devolución de llamada. |

### Valor devuelto

Siempre devuelve true.

## Ver también

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [ThreadPoolImpl](../)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)