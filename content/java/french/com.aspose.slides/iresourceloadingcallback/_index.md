---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /fr/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Interface de rappel utilisée pour gérer le chargement des ressources externes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Méthode de rappel qui régule le chargement des ressources externes. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


Méthode de rappel qui régule le chargement des ressources externes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Les données de la ressource en cours de chargement [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Retour:**
int - La décision de chargement de la ressource [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).