---
title: ResourceLoading()
second_title: Référence de l'API Aspose.Slides pour C++
description: Méthode de rappel qui régule le chargement des ressources externes.
type: docs
weight: 1
url: /fr/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) méthode

Méthode de rappel qui régule le chargement des ressources externes.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | Les données de la ressource à charger [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Valeur de retour

La décision de chargement de la ressource [ResourceLoadingAction](../../resourceloadingaction/).

## Voir aussi

* Enum [ResourceLoadingAction](../../resourceloadingaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IResourceLoadingArgs](../../iresourceloadingargs/)
* classe [IResourceLoadingCallback](../)
* espace de noms [Aspose::Slides](../../)
* bibliothèque [Aspose.Slides](../../../)