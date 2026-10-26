---
title: ResourceLoading()
second_title: Referencia de API de Aspose.Slides para C++
description: Método de devolución de llamada que regula la carga de recursos externos.
type: docs
weight: 1
url: /es/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) método

Método de devolución de llamada que regula la carga de recursos externos.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | Los datos del recurso de carga [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Valor de retorno

La decisión de carga del recurso [ResourceLoadingAction](../../resourceloadingaction/).

## Ver también

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IResourceLoadingArgs](../../iresourceloadingargs/)
* Clase [IResourceLoadingCallback](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)