---
title: ResourceLoading()
second_title: Aspose.Slides für C++ API-Referenz
description: Callback-Methode, die das Laden externer Ressourcen regelt.
type: docs
weight: 1
url: /de/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) Methode

Callback-Methode, die das Laden externer Ressourcen regelt.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | Die ladenden Ressourcendaten [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Rückgabewert

Die Entscheidung zum Laden der Ressource [ResourceLoadingAction](../../resourceloadingaction/).

## Siehe auch

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IResourceLoadingArgs](../../iresourceloadingargs/)
* Klasse [IResourceLoadingCallback](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)