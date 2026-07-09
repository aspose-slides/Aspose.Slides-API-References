---
title: IResourceLoadingCallback
second_title: Aspose.Slides pour Android via Java API Référence
description: Interface de rappel utilisée pour gérer le chargement des ressources externes.
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
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Les données de la ressource chargée [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Renvoie:**
int - La décision de chargement de la ressource [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).