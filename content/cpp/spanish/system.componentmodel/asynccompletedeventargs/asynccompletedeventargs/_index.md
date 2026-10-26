---
title: AsyncCompletedEventArgs()
second_title: Referencia de API de Aspose.Slides para C++
description: Constructor.
type: docs
weight: 1
url: /es/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() constructor


Constructor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) constructor


Inicializa una nueva instancia de la clase [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Cualquier error que ocurrió durante la operación asincrónica. |
| canceled | **bool** | Un valor que indica si la operación asincrónica fue cancelada. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | El objeto de estado opcional proporcionado por el usuario que se pasa al método [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Ver también

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [AsyncCompletedEventArgs](../)
* Clase [Object](../../../system/object/)
* Espacio de nombres [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)