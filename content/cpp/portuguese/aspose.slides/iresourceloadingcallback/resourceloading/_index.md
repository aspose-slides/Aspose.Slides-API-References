---
title: ResourceLoading()
second_title: Referência da API Aspose.Slides para C++
description: Método de retorno de chamada que regula o carregamento de recursos externos.
type: docs
weight: 1
url: /pt/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) método


Método de retorno de chamada que regula o carregamento de recursos externos.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | Os dados de carregamento do recurso [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Valor de Retorno

A decisão de carregamento do recurso [ResourceLoadingAction](../../resourceloadingaction/).

## Veja Também

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IResourceLoadingArgs](../../iresourceloadingargs/)
* Classe [IResourceLoadingCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)