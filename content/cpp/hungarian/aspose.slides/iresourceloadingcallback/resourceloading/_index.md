---
title: ResourceLoading()
second_title: Aspose.Slides C++ API Referenciája
description: Visszahívási metódus, amely szabályozza a külső erőforrások betöltését.
type: docs
weight: 1
url: /hu/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) metódus


Visszahívási metódus, amely szabályozza a külső erőforrások betöltését.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | A betöltésre kerülő erőforrás adatai [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Visszatérési érték

Az erőforrás betöltésének döntése [ResourceLoadingAction](../../resourceloadingaction/).

## Lásd még

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IResourceLoadingArgs](../../iresourceloadingargs/)
* Class [IResourceLoadingCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)