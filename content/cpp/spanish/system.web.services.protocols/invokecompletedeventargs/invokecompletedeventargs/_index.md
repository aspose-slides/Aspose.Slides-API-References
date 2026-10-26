---
title: InvokeCompletedEventArgs()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 14
url: /es/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) constructor

Construye una nueva instancia.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | Cualquier error que ocurrió durante una operación asíncrona. |
| cancelled | **bool** | Un valor que indica si una operación asíncrona está cancelada. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | El objeto de estado opcional suministrado por el usuario que se pasa al método [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Una colección de resultados de operaciones asíncronas. |

## Ver también

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Object](../../../system/object/)
* Clase [InvokeCompletedEventArgs](../)
* Espacio de nombres [System::Web::Services::Protocols](../../)
* Library [Aspose.Slides](../../../)