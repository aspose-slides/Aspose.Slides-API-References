---
title: ResourceLoading()
second_title: Riferimento API Aspose.Slides per C++
description: Metodo di callback che regola il caricamento delle risorse esterne.
type: docs
weight: 1
url: /it/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) metodo

Metodo di callback che regola il caricamento delle risorse esterne.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | I dati della risorsa in caricamento [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Valore di ritorno

La decisione di caricamento della risorsa [ResourceLoadingAction](../../resourceloadingaction/).

## Vedi anche

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IResourceLoadingArgs](../../iresourceloadingargs/)
* Class [IResourceLoadingCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)